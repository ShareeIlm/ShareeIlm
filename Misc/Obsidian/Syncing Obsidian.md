Obsidian can be synced for **Free** using the plugin "Remotely Save".

# Desktop Side
- Go to Settings > Community Plugins > Browse > Search "Remotely Save" > Install
![](Syncing%20Obsidian%20rem.png)
- then go to Settings > Remotely Save
	- In "Choose Remote Service", Select "Onedrive for personal"
	- Go to the link provided, perform authentication and wait.
	- After authentication, set the sync timers:
		- Remotely Save > Schedule for auto Run > 10 minute
		- Remotely Save > Run Once on startup Automatically > 1 second
- You can run sync manually from the command palette (Ctrl-P) by typing "Start Sync"
- Now Sync your vault once.

# Phone Side
1. Create a vault with the **same name** as the desktop vault
2. Install remotely save following the same steps as above ^^^^. Copy the sync timers too.
3. Run "Start Sync" from the command palette by swiping down at the home screen of the vault.

Now you vault will sync automatically once every 10 minutes.