# Mission 0 — Create Your GitHub Workspace

## 1. Task / Objective

The objective of this mission was to create a GitHub repository with the required folder structure for all eight subsequent missions and prepare a workspace for completing the Digital Detective assignment.

**Repository name:** `digital-detective-8549`

**GitHub username:** `reva572`

**Repository URL:** https://github.com/reva572/digital-detective-8549

**Visibility:** Public

## 2. Work Completed

- Created the local project folder on the Desktop.
- Created all nine mission folders (Mission 0 to Mission 8).
- Created individual README.md files for each mission.
- Created the `number_converter.py` file for Mission 5.
- Created an `evidence` folder for storing screenshots and outputs.
- Prepared the root README.md.
- Initialized Git and connected the local repository to GitHub.
- Created the initial commit and successfully pushed the project to GitHub.

## 3. Commands / Tools Used

| Command / Tool | Purpose |
|---|---|
| `python3 --version` | Checked the installed Python version. |
| `git --version` | Checked the installed Git version. |
| `pwd` | Displayed the current working directory. |
| `mkdir -p` | Created the mission directories. |
| `cd` | Navigated into the project directory. |
| `touch` | Created empty files. |
| `find` | Verified the folder and file structure. |
| `git init` | Initialized the local Git repository. |
| `git status` | Checked the repository status. |
| `git remote add` | Connected the local repository to GitHub. |
| `git remote -v` | Verified the remote repository URL. |
| `git branch -M main` | Renamed the branch to main. |
| `git add .` | Staged project files for committing. |
| `git commit` | Saved the initial project snapshot. |
| `git push` | Uploaded the commit to GitHub. |
| `gh auth login` | Authenticated GitHub CLI using a browser. |

**Tools and versions:**
- Python: 3.15.0
- Git: 2.56.0
- GitHub CLI: Installed using Homebrew
- Editor: Visual Studio Code
- Platform: macOS

## 4. My Understanding

A GitHub repository is an online storage space for a project that also maintains its version history through Git.

Git allows developers to track modifications, save checkpoints using commits and upload their work to GitHub using push.

The folder structure is organised by mission so that every activity has a separate location. This makes the project easier to navigate, maintain and review. Each mission can also be documented and committed independently.

## 5. Difficulties Faced

- GitHub rejected normal password authentication while attempting to push through HTTPS.
- GitHub CLI was initially unavailable on the system.
- Terminal did not display characters while entering password input, which caused confusion.

## 6. How I Resolved Them

- Installed GitHub CLI using Homebrew.
- Used `gh auth login` to authenticate through the GitHub browser device-authorisation process.
- Verified authentication and successfully pushed the repository.
- Learned that Terminal does not display password characters during secure input.

## 7. Evidence / Files

- Root `README.md`
- Mission folders from `mission-00-setup` to `mission-08-final-report`
- Individual mission README files
- `mission-05-numbers-data/number_converter.py`
- `evidence/` directory
- Public GitHub repository

## 8. Commit Details

The initial workspace commit was created and successfully pushed to the `main` branch on GitHub.

## 9. Completion Status

- [x] Python and Git versions verified.
- [x] Local project directory created.
- [x] Required mission folders and files created.
- [x] Git repository initialized.
- [x] GitHub remote configured.
- [x] Public GitHub repository created.
- [x] Initial commit pushed successfully.
- [x] Mission 0 documentation committed and pushed