# Security policy: Offline Mermaid Diagrams for Confluence

## How the app handles data

- Runs on Atlassian (Forge). The Mermaid engine is bundled in the app and renders in the user's browser.
- No egress: the app makes no external network calls and uses no third-party services, analytics or tracking.
- No Confluence API scopes are requested.
- Diagram text is stored only in the Confluence page's macro configuration, under Confluence's own permissions, history and data residency.
- No logs containing end-user data are kept outside Atlassian.
- Mermaid runs in strict security mode: labels are sanitised and click-to-script is disabled.

## Reporting a vulnerability

Report privately via a [GitHub security advisory](https://github.com/cprussin/mermaid-for-confluence/security/advisories/new). Please don't open a public issue. You'll get a response within 5 business days, and confirmed issues are fixed and released as soon as practical.

## Supported versions

Only the current Marketplace version is supported. Forge apps update automatically.
