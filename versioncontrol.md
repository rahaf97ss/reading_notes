## Version Control: is a system that allows you to revisit various versions of a file or a set of files by recording changes.

### Local version control: entails one database on your hard disk that stores changes to files.
### Centralized version control: entails a single server storing all changes and file versions, which can be accessed by clients.
### Distributed version control: addresses the major vulnerability of the cvs.
### -What is GIT? Snapshots: stores data in a file system made up of snapshots. Local operations: Git relies on on local operations because most necessary information can be found in local resources.Tracking changes: every single change applied to any file or directory is tracked by Git.Loss of data: Git is set up to greatly minimize the possibility of irreversible damage to files.
### States: Three main states:
1. committed: Data is securely stored in a local database.
2. modified: File has been changed but not committed.
3. Staged: Flagged a file's changed version to be committed in the next snapshot.
### Download Git: You can download it by Github and Git website for windows users, and for Mac users from terminal and Git website and Github, and for linux by Git website and package manager.
## Graphical clients: Git includes inherent graphical user interface.
### Initial customization:  by two steps:
1. configuration of variables: (git config) allows the setting of configuration variables that control aspects of Git’s operation and look.
2. Identify setting: set you name and password, and then confirm it.
### Default text editor: without configuration, Git will use the system's editor.
### Check settings: by git config--list.Getting help: by git help command.
### Setting up a Git Repository:
1. Importing: we have to follow these steps: 1-cd/2-git init/3-git add*.c to track it.
2. cloning: by tyoing git clone url.
### Local repository has three components: 1- Working directory.2-Index.3-Head.
### Saving changes:( it's either tracked or untracked)-Tracked: Tracked files can be modified or unmodified or staged.-Untracked: it's not in the last snapshot and do not currently reside in the staging area.
### The life cycle of file status: check file status: determine the state of files, by utilizing the git status.
### Tracking and staging a new file: - Single file: track one file only by git add filename.-All files: Track all files in repository by git add *.
### Committing a file: by typing git commit-m.Committing all changes: git commit -a.
### pushing changes: git push origin master.
### Stashing changes: When you are not ready to commit changes but do not want to lose them either you type  git stash, and when you are ready you type git stash apply. 
### Remote repositories: you can work with multiple repositories by it.
