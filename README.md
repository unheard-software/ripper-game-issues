# RIPPER - issue reports

> [!IMPORTANT]
> **Before creating an issue here, please check that you are in the right place.**
> 
> We do not care about issues related to *user created* modifications. Please submit here only issues or feedback *related to the base game*.
> 
> Please read the instructions on [how to report issues](#how-to-report-issues).

- **Base game issues & feedback**: https://github.com/unheard-software/ripper-game-issues/issues/
- **Modding**: _(repository still in works)_
- **Documentation**: _(repository still in works)_
- **Check our roadmap!**: https://github.com/unheard-software/ripper-game-issues/issues/1

## How to Report Issues

We’ve split issue reports into categories so developers can address them quickly.  
When you [open a new issue](https://github.com/unheard-software/ripper-game-issues/issues/new/choose), **choose the appropriate template**.  
If you’re unsure which category fits, pick the one that seems closest or use **Uncategorized**.

---

### Before You Submit

First, **search the [existing issue list](https://github.com/unheard-software/ripper-game-issues/issues/)** to see if the problem has already been reported.  
If you find a matching issue, **add a reaction or comment** with any extra information you have instead of opening a duplicate. This keeps the tracker tidy and speeds up fixes.

---

### Issue Types

| Category                          | When to Use                                                                           | What to Include                                                               |
| --------------------------------- | ------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| **Crash / Uncategorized**         | You can’t pinpoint a specific type, or the game crashes.                              | Stack‑trace, system specs, map, environment, server setup, any other details. |
| **BUG: Interface**                | Problems with menus, UI elements, modals, navigation, translations, or accessibility. | Description, screenshots, steps to reproduce.                                 |
| **BUG: In‑Game**                  | Anything broken while playing (entities, items, furniture, de‑sync, etc.).            | Description, screenshots/video, steps to reproduce.                           |
| **BUG: Other**                    | Bugs that don’t fit the above (audio, music, unexpected behavior).                    | Description, relevant files or logs.                                          |
| **Feedback: Interface (UI/UX)**   | Suggestions to improve the UI layout, missing buttons, clutter, etc.                  | Clear suggestion, mock‑ups if possible.                                       |
| **Feedback: Gameplay**            | Ideas for balancing, gameplay flow, or overall feel.                                  | Explanation of the change and why it improves the game.                       |
| **Feedback: Other**               | Any feedback that isn’t a feature request (e.g., audio, music comments).              | Description of the feedback.                                                  |
| **Suggestions / Feature Request** | Proposals for new content, story elements, or changes to existing features.           | Detailed description, possible implementation ideas.                          |

---

### Quick Tips

1. **Select the right template** – it helps us route the issue instantly.  
2. **Provide as much detail as possible** – screenshots, logs, and step‑by‑step reproduction are invaluable.  
3. **Keep the title concise** – a brief summary makes it easier to scan the issue list.  

### F.A.Q.
1. **Where do I find the log files?**
	- There are two different kinds of log, one extending the other. *Either one of these will suffice*
	- **godot.log (recommended)**
		- **Windows**: `%APPDATA%\unheard\ripper\logs\godot.log`
		- **Linux**: `$XDG_DATA_HOME/unheard/ripper/logs/godot.log`
	- **log.txt**
		- Found in the installation folder, serves as backup if godot.log is not present. Does not contain un-handled exceptions. *If you have the game downloaded on non-default disk, you will have to locate the log yourself.*
		- **Windows**: `C:\Program Files (x86)\Steam\steamapps\common\Ripper\log.txt`
		- **Linux**: `$HOME/.steam/steam/steamapps/common/Ripper/log.txt`

Thank you for helping us keep the issue tracker clean and making the game better!
