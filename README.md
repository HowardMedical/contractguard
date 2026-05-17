# ContractGuard by Howard Medical

Landing page for ContractGuard, a free contract-to-invoice overbilling audit for independent, critical access, and rural hospitals.

**Live target:** https://contractguard.health
**Dropbox File Request:** https://www.dropbox.com/request/sc9iodwfw8gxd0ycbu3o (uploads land in `/ContractGuard/Inbound`)

## Stack

Single static HTML page. Modern AI-product aesthetic (Inter, black + indigo accent, editorial layout). No backend, no framework, no build step.

## Deploy

Auto-deploys to Vercel on push to `main`. See `vercel.json` for headers config.

## Update the Dropbox link

The submit CTA URL is set inline in `index.html`. Search for the dropbox.com/request URL and replace if needed. A new File Request can be created via Composio (Dropbox > CREATE_FILE_REQUEST).
