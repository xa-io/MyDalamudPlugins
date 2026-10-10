# XA Plugins

Aethertek's Dalamud plugins for FINAL FANTASY XIV: character data, item search, multi-character automation, gameplay utilities, and UI inspection. Companion applications provide account management, dashboards, and launcher tools.

[All plugins and tools](https://aethertek.io/) · [Documentation](https://wiki.aethertek.io/) · [Discord](https://discord.gg/g2NmYxPQCa) · [FFXIV server status](https://online.aethertek.io/)

## Installation

1. Install [XIVLauncher](https://github.com/goatcorp/FFXIVQuickLauncher), enable Dalamud in its settings, and launch the game through it.
2. Type `/xlsettings` in game chat, open **Experimental**, and find **Custom Plugin Repositories**.
3. Add **one** of the repository URLs below, click **+**, then **Save and Close**.
4. Type `/xlplugins`, open **Available Plugins**, and search for **XA Database**, **XA Slave**, **XA HUD Navigator**, **Aethertek Plugin Manager**, or **XA Zod**.

**Recommended: Aethertek's main repository**

```text
https://aethertek.io/x.json
```

**Fallback: this repository's XA plugin feed**

```text
https://raw.githubusercontent.com/xa-io/MyDalamudPlugins/master/pluginmaster.json
```

Use only one feed to avoid duplicate repository entries. The desktop applications listed under Other tools are installed separately from the website.

## [Aethertek Plugin Manager](https://aethertek.io/guides/plugin-management.html)

Open `/apm` to update installed development plugins or supported private packages from a trusted publisher's direct ZIP link.

- Match the copied link to an installed plugin and check the package and version before updating.
- Keep optional local backups and reload an updated running plugin automatically.
- Include supported public hosts to manage their private packages; private access is arranged separately.
- Continue using Dalamud for normal public-plugin updates. APM's **Automatic Updates** option allows supported plugins to request an update when you click their update button; it does not poll in the background.

## [XA Database](https://github.com/xa-io/XA-Database)

Keep a searchable local record of your characters and browse their saved data without logging into each one. [Features and usage](https://aethertek.io/plugins/xa-database.html).

- **Character overview** — Compare job levels, gil, currencies, retainers, and progression in the dashboard or browse individual saved characters.
- **Inventory and storage** — Track inventory, equipped gear, armoury, normal and premium saddlebags, crystals, retainers, armoire, and glamour dresser items.
- **Cross-character search** — Find recorded item locations and totals, view HQ/NQ ownership in tooltips, and open an exact item search from the inventory context menu.
- **Retainers and markets** — Review ventures, inventories, gil, market listings, and sale status.
- **Free Companies and housing** — Record FC members, ranks, points, master-only chest gil, workshop voyages, squadron data, personal and shared estates, and apartments.
- **Collections and travel** — Browse mounts, minions, orchestrion rolls, cards, quests, MSQ progress, and recorded aetheryte unlocks with destination search.
- **Saved data and filtering** — Keep last-observed information when storage is unavailable, save on login/logout or configured triggers, and optionally exclude AutoRetainer characters from shared views without deleting their records.
- **Exports and integrations** — Export CSV/JSON, check database health, and share character and item data with other tools through IPC.

## [XA Slave](https://github.com/xa-io/XA-Slave)

Automate multi-character tasks, coordinate item transfers, and customize everyday gameplay through searchable XA Mods. [Features and usage](https://aethertek.io/plugins/xa-slave.html).

- **Character workflows** — Run Monthly Relogger, City Chat Flooder, travel preparation, and homeworld returns, with AutoRetainer roster integration and task progress.
- **Xagman transfers** — Collect and restock items across characters and clients using Give, Take, Balance, and TopUp policies, collector rotation, and fixed-world or Server Matching meetups.
- **Submarine supplies** — Estimate remaining stock days from submarine builds and prepare ceruleum tank and repair-material targets for restocking.
- **AutoRetainer Helper** — Coordinate pre/post-processing, collection, recovery, and Company Chest gil updates with XA Database.
- **FC and housing tools** — Update FC permissions, check duplicate plots, accept FC invitations, and refresh workshop, retainer-bell, and Company Chest data.
- **XA Mods and presets** — Search grouped gameplay, UI, graphics, player, and plugin settings; save presets, share them through clipboard import/export, and use Plugin Guard to protect selected plugins from unwanted disable or unload requests.
- **Inventory and appearance** — Automate Expert Delivery, sort and move inventory, queue Dropbox trades, preview items and inspected outfits, and customize the mouse cursor.
- **Field and player tools** — Hunt Eureka instances, queue Logos Actions, browse nearby players, configure player notifications, and change glamour with the weather.
- **Data and exports** — Save character information to XA Database and export AutoRetainer, Lifestream, and database tables as JSON, CSV, or TSV.
- **Commands and extensions** — Browse the built-in command reference, load external task DLLs, and integrate through `XASlave.ExecuteCommand`, `XASlave.IsBusy`, and `XASlave.RunTask`.

Xagman remains beta and uses AutoRetainer, Lifestream, XA Database, Dropbox, and vnavmesh. Participating clients should use compatible XA Slave versions; individual tasks may have additional setup requirements in the feature guide.

## [XA HUD Navigator](https://github.com/xa-io/XA-HUD-Navigator)

Inspect live game UI addons, sheet data, and ClientStructs runtime state in a safe pre-production workspace.

- Addon list and node tree inspector for loaded UI with text, position, size, and event details.
- Logging and debug workspaces for addon timing, recursive path dumps, and targeted copy helpers.
- Lumina sheets browser with schema-aware columns, row jumping, and grid-style browsing.
- CS.Sheets runtime views for player, inventory, retainer, housing, market, FC, and target data.
- Transparent HUD overlay that outlines visible addons and highlights interactive nodes.
- Copy verified addon, sheet, and runtime data into XA Database or XA Slave workflows later.

## [XA Zod](https://aethertek.io/plugins/xa-zod.html)

Private access plugin.

## Other tools

Use the website pages below for current downloads, setup instructions, and supported platforms.

| Tool | What it does |
| --- | --- |
| [XA Sub Manager](https://aethertek.io/applications/xa-sub-manager.html) | Manage multiple accounts, submarines, and retainers with scheduled client launching/closing, 2FA, window layouts, maintenance handling, an Empire View, and an optional remote web dashboard. Windows, with experimental Linux/Wine support. |
| [XA Dashboard](https://aethertek.io/applications/xa-dashboard.html) | Read AutoRetainer, XA Database, and Lifestream data in a local browser dashboard: character and item searches, submarine tracking, FC housing/planning, gil charts, and Excel export. Available for Windows and Linux; market-sale notifications and one-click updates are Windows-only. |
| [DLL Bypasser](https://aethertek.io/guides/dalamud-bypasser.html) | The current replacement for Update Keys, with downloads and instructions for the Dalamud version-check bypasser. Use the guide's matching DLL baseline and compatibility checks; bypassing a version gate does not repair incompatible plugins. |
| [Auto 2FA Launcher](https://aethertek.io/applications/auto-2fa-launcher.html) | The same standalone XIVLauncher helper for automatic OTP entry, with its setup guide now linked through the Aethertek website. |

XA Sub Manager replaces Auto-AutoRetainer, and XA Dashboard replaces AutoRetainer Dashboard. **SND scripts are no longer supported** and are not part of the current tool list.

## Support

- Discord server: <https://discord.gg/g2NmYxPQCa>
- Open an issue on the relevant GitHub repository for bugs or feature requests.
- [XA Database Issues](https://github.com/xa-io/XA-Database/issues) | [XA Slave Issues](https://github.com/xa-io/XA-Slave/issues) | [XA HUD Navigator Issues](https://github.com/xa-io/XA-HUD-Navigator/issues)

<details>
<summary>Repository maintenance and statistics</summary>

### Aethertek Plugin Manager metadata

The repository updater reads APM's manifest from its protected release ZIP and resolves its icon from the public `AethertekPluginManager/images/icon.png` path on the main branch. Hosted Aethertek download totals remain preferred, with GitHub release-asset totals as the fallback. The Discord statistics entry uses the APM emoji.

Download-count offsets match the Aethertek website updater across all 25 repository entries. Offsets apply only to GitHub fallback totals; hosted totals already include them.

### Public Dhog host statistics

Repository title constants and Discord headings use `XA` and `Dhog`; older source-feed labels remain compatible. Repository statistics include the public `McVaxius/mom-public`, `McVaxius/dhognav-public`, and `McVaxius/dduck-public` release hosts with their dedicated Discord emojis. Hosted Aethertek totals remain authoritative. When hosted statistics are disabled, the Dhog section supplements its legacy feed with all release-asset download totals from these three repositories; existing entries are replaced once and retained if a repository is unavailable. Counting uses release metadata without downloading release ZIPs. Public installation does not grant access to private functionality.

Deep Ducking uses internal name `DDuck` and the public repository feed on `master`, with Discord emoji `<:dduck:1552408146251743324>`. Its public host does not grant private feature access.

### Community plugin statistics

Questionable (`WigglyQuest`) and Influx appear under Wiggly, followed by Questionable Companion (`QSTCompanion`) under Matsuuzo, after the Dhog statistics section. Each plugin uses its supplied Discord emoji. Hosted Aethertek totals are authoritative and are not offset or recounted.

When hosted statistics are disabled, the maintained `WigglyCorp/DalamudPlugins/main/pluginmaster.json` feed supplies exact plugin identities and metadata. Statistics count all release attachments from the current `WigglyMuffin/Questionable`, `WigglyMuffin/Influx` and `MacaronDream/QSTCompanion` repositories without downloading ZIPs. An unavailable release-count request retains that plugin's upstream feed total; a missing or ambiguous identity is skipped with a diagnostic. If the upstream feed is unavailable, community statistics are omitted for that cycle. Historical offsets for these repositories are zero.

Community entries are excluded from the XA-only publication targets and do not appear under the Dhog author group.

</details>
