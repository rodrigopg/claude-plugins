# claude-plugins

[![validate](https://github.com/rodrigopg/claude-plugins/actions/workflows/validate.yml/badge.svg)](https://github.com/rodrigopg/claude-plugins/actions/workflows/validate.yml)

Personal **Claude Code plugin marketplace** by Rodrigo Gonçalves — plugins and skills for WhatsApp (MCP), KeePass password management, EasyPanel deploys, Discord server management, Proxmox VE, GitHub branch protection and on-demand project context.

## Usage

Add the marketplace:

```
/plugin marketplace add rodrigopg/claude-plugins
```

Install a plugin:

```
/plugin install whatsapp-mcp@rodrigopg
```

## Plugins

| Plugin | Description |
|--------|-------------|
| [whatsapp-mcp](https://github.com/rodrigopg/whatsapp-mcp) | WhatsApp for Claude — messages, media, groups, opt-in audio transcription. After install, run `/whatsapp-mcp:setup` to install the bridge and pair. |
| [prime-context](https://github.com/rodrigopg/claude-skill-prime-context) | On-demand project context loading — thin AGENTS.md router, area context files loaded only when the task needs them. |
| [github-branch-protection](https://github.com/rodrigopg/claude-skill-github-branch-protection) | Protect GitHub branches against direct pushes — native protection (paid plans) or GitHub Actions workaround (free). |
| [easypanel](https://github.com/rodrigopg/claude-easypanel-skill) | Manage and diagnose EasyPanel services via Playwright — deploys, failures, redeploys, build logs. |
| [keepass](https://github.com/rodrigopg/keepass-claude-skill) | KeePass database management via keepassxc-cli — search, add, edit, merge duplicates; auth via OS secret store. |
| [discli](https://github.com/rodrigopg/discli) | Discord server management CLI for AI agents — channels, roles, messages, embeds, emojis. Requires the `discli` CLI installed. |
| proxmox | Proxmox VE hypervisor primitives via `pve` CLI — VMs, snapshots, clones, VNC console automation. *Private repo — install requires access.* |
| protheus-smartview | Talk to Protheus through SmartView reports — ask in natural language, get real data back. *Private repo — install requires access.* |
