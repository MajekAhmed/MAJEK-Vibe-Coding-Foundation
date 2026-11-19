# Safety Policy

## Default
Inspect before changing. Prefer small, reversible changes. State scope and affected paths. Never claim a check passed without evidence.

## Explicit approval required
- Production deployment/access.
- Destructive database operations, migrations, resets, or bulk changes.
- Deleting/overwriting user data.
- Changing Windows security, ExecutionPolicy, firewall, accounts, or permissions.
- Modifying H:, partitions, Docker storage, or unrelated project directories.
- Installing/removing major tools or changing system runtimes.
- External side effects: publishing, messaging, spending, or creating external resources.
- Running untrusted code outside an isolated disposable environment.

## Secrets
Never commit, print, or store credentials in chat, agent memory, issues, or logs. Redact output. Use approved secret stores or environment variables; document names, never values.

## Agent permissions
Read-only is default. File edits stay inside the selected repository. Ask before installations, system changes, network integrations, or destructive actions.

## Exposure response
Stop disclosure; identify credential scope; rotate through the supported owner-controlled mechanism; verify old credential invalidation; record a redacted incident note.
