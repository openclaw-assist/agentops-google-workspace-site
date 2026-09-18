# AgentOps Google Workspace OAuth Site

Public static disclosure site for the private, single-user Google OAuth application used by Chris Tran's AgentOps assistant.

- Intended custom domain: `agentops.gritequities.com`
- Public repository: `https://github.com/openclaw-assist/agentops-google-workspace-site`
- Hosting: GitHub Pages from `main` `/`
- DNS: GoDaddy CNAME `agentops` → `openclaw-assist.github.io`
- Homepage: `/index.html`
- Privacy policy: `/privacy.html`
- Terms: `/terms.html`
- No JavaScript, forms, analytics, tracking, credentials, or private data.

GitHub Pages TLS issuance and HTTPS enforcement are monitored by the temporary Hermes cron job `AgentOps OAuth site HTTPS activation`. OAuth client secrets and tokens must never be committed.
