# XA Plugins
A collection of Dalamud plugins for Final Fantasy XIV focused on multi-character data tracking and task automation.

## [XA Database](https://github.com/xa-io/XA-Database)
Track and browse data across all of your characters without needing to log into each one.
- Levels, Gil, currencies, and FC info for every character at a glance.
- Cross-character inventory and retainer search with item stacking.
- Retainer ventures, market listings, and inventory tracking.
- Collections progress — mounts, minions, orchestrion rolls, MSQ milestones.
- Housing and Free Company details including squadron and voyages.
- Offline character browser — select any character from the database at any time.

## [XA Slave](https://github.com/xa-io/XA-Slave)
Automate repetitive multi-character workflows so you don't have to do them manually.
- Monthly Relogger — cycle through characters with AutoRetainer integration, sorted by Region/DC/World.
- City Chat Flooder — travel through worlds and cities sending chat announcements with looping.
- Check Duplicate Plots — scan housing wards for duplicate plot ownership across characters.
- Return Alts To Homeworlds — send characters back to their home worlds automatically.
- External task loading — drop custom task DLLs into the tasks folder for additional automation.
- IPC support — other plugins can check status and trigger tasks via `XASlave.IsBusy` and `XASlave.RunTask`.

## Installation
1. Install [FFXIVQuickLauncher](https://github.com/goatcorp/FFXIVQuickLauncher) and enable Dalamud in its settings. You must run the game through FFXIVQuickLauncher for plugins to work.
2. Open Dalamud settings by typing `/xlsettings` in game chat.
3. Go to the "Experimental" tab.
4. Find the "Custom Plugin Repositories" section and paste the following URL into the text input field: 
```
https://raw.githubusercontent.com/xa-io/MyDalamudPlugins/master/pluginmaster.json
```
5. Click the "+" button, then "Save and Close".

You should now have XA plugins available in your plugin installer. <br>
Open the plugin installer by typing `/xlplugins` in game chat, go to the "Available Plugins" tab and search for **XA Database** or **XA Slave**.

### Other tools

- [Auto-AutoRetainer](https://github.com/xa-io/ffxiv-tools/tree/main/Auto-AutoRetainer) - Automated submarine and retainer farming helper that launches XIVLauncher when accounts need attention, handles 2FA, recovers from crashes, and closes clients when idle.
- [AutoRetainer Dashboard](https://github.com/xa-io/ffxiv-tools/tree/main/AutoRetainer-Dashboard) - Self-hosted web dashboard for AutoRetainer, XA Database, and Lifestream data with character overviews, submarine tracking, gil totals, FC tools, and charts.
- [Update Keys](https://github.com/xa-io/ffxiv-tools/blob/main/update_dev_beta_keys.py) - Easy way to update Dalamud keys on patch days. Live key updates are also posted in the Discord server.
- [Auto 2FA Launcher](https://github.com/xa-io/ffxiv-tools/tree/main/Auto-2FA-Launcher) - Standalone XIVLauncher helper for automatic OTP entry so you can launch faster without running a larger automation stack.
- [SND Scripts Repo](https://github.com/xa-io/ffxiv-tools/tree/main/snd) - My SND scripts repository for additional scripts and related automation helpers.

## Support

- Discord server: <https://discord.gg/g2NmYxPQCa>
- Open an issue on the relevant GitHub repository for bugs or feature requests.
- [XA Database Issues](https://github.com/xa-io/XA-Database/issues) | [XA Slave Issues](https://github.com/xa-io/XA-Slave/issues)
