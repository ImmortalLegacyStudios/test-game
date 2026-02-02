# Test Game

A Unity game project developed by **ImmortalLegacyStudios**.

This repository contains the full Unity project, set up for collaboration using GitHub.

------------------------------------------------------------------------------
Project Overview

**Genre:** _TBD_  
**Platform:** PC
**Engine:** Unity  
**Status:** Early development / Prototype

Short description of the game goes here.  

------------------------------------------------------------------------------
Unity Version

> **IMPORTANT:** Everyone must use the same Unity version.

- **Unity Version:** `6000.3.3f1` LTS
- Install via **Unity Hub**
- Do **not** upgrade Unity without team agreement

------------------------------------------------------------------------------
Project Structure

We only commit the following folders:

Assets/
Packages/
ProjectSettings/

Everything else (`Library/`, `Temp/`, `Build/`, etc.) is ignored via `.gitignore`.

------------------------------------------------------------------------------
Branching & Workflow

**Do NOT commit directly to `main`.**

### Branches
- `main` → Stable, playable builds only
- `dev` → Integration branch
- `feature/*` → Individual features or tasks

### Example

feature/player-movement
feature/enemy-ai
feature/ui-pass

------------------------------------------------------------------------------
Unity Collaboration Rules

To avoid merge conflicts:

- Unity is configured with:
  - **Visible Meta Files**
  - **Force Text Serialization**
- Prefer **prefabs** over scene edits
- Only one person edits a scene at a time
- Large systems should use separate test scenes

------------------------------------------------------------------------------
Large Files & Git LFS

Git LFS is used for large binary assets such as:
- `.psd`
- `.fbx`
- `.wav`
- `.mp4`

Do **not** commit large binary files without LFS.

------------------------------------------------------------------------------
Getting Started

Requirements
- A GitHub account (free)		https://github.com
- Unity Hub installed			https://unity.com/download
- Installed the correct version (see above)

1. Install Git
- Download from 			https://git-scm.com/downloads
- Install using default settings
- Restart your computer
- Open a terminal / Command Prompt
- Type "git --version", if you see a version number, it worked

2. Install GitHub Desktop
- Download GitHub Desktop		https://desktop.github.com
- Install and open it
- Sign in with your GitHub Account

3. Clone the project (download it)
- Open GitHub Desktop
- Click File -> Clone repository
- Select the URL tab
- Paste "https://github.com/ImmortalLegacyStudios/test-game.git"
- Choose a local folder
- Click Clone

4. Open the project in Unity
- Open Unity Hub
- Click Open
- Select the cloned project folder
- Unity will open the project
	- If Unity asks to upgrade the project: DO NOT UPGRADE!!!

5. Create your own branch (Important)
- Open the repository in GitHub Desktop
- Click the Current Branch dropdown
- Click New Branch
- Name it "feature/your-name-what-you-are-working-on"
	- Example "feature/player-movement"
- Click Create Branch

6. Make changes
- Make any changes you want

7. Commit your changes
- In GitHub Desktop, you'll see all the changes you have done
- Write a short summary of the changes
- Click Commit to your Branch

8. Push your changes (Upload)
- After commiting, Click Push Origin (in the top bar)
- Your changes have now been uploaded

If you need to Pull updates (before you begin work)
9. Pulling updates
- Before opening Unity, launch GitHub Desktop
- Select the current repository
- Check the branch and make sure it is the one you are working on
- Click Fetch Origin (If updates exist, it will change to Pull Origin)
- Open Unity

------------------------------------------------------------------------------
Notes

Keep commits small and descriptive

Test your changes before pushing

Ask before making structural changes

------------------------------------------------------------------------------
Licence

If you want, I can:
- Customize this for a **specific genre**
- Add a **Game Jam–style README**
- Add a **Contribution Guide (CONTRIBUTING.md)**
- Tighten it up for **solo dev vs team**

Just tell me:
- What kind of game this is
- Solo for now, or team starting soon 👀
