# Git Setup Guide

This guide shows how to install `Git` on `macOS` and `Windows`, check that it works, and get this repo onto your computer.

## What Git Is
`Git` is a version control tool. For this exercise, you only need a few basics:
- install `Git`
- confirm it works
- download the repo with `git clone`
- or download the repo as a ZIP file if you are not ready to use `git clone`

## Option 1: Get The Files Without Git
If you do not want to use `Git` yet, you can still use this exercise:

1. Open the GitHub repo in your browser.
2. Click the green `Code` button.
3. Click `Download ZIP`.
4. Save the ZIP file to your computer.
5. Extract it.
6. Open the extracted folder in `Cursor`, `VS Code`, or your file browser.

## Option 2: Install Git And Clone The Repo
If you want to learn the basic Git workflow, follow the steps below.

## macOS Setup
### Step 1: Check Whether Git Is Already Installed
Open `Terminal` and run:

```bash
git --version
```

If you see a version number, `Git` is already installed.

If you see a message saying the command is missing, continue to the next step.

### Step 2: Install Git On macOS
You can install `Git` in either of these ways:

Option A: install Apple command line tools

```bash
xcode-select --install
```

Option B: install with `Homebrew` if you already use it

```bash
brew install git
```

### Step 3: Confirm The Installation
Run:

```bash
git --version
```

You should now see a version number.

## Windows Setup
### Step 1: Download Git
1. Go to [https://git-scm.com/download/win](https://git-scm.com/download/win).
2. Download the Windows installer.
3. Run the installer.

### Step 2: Install Git
For most users, the default installer options are fine.

Important option:
- if asked whether to add Git to your path, keep the recommended setting that lets you use Git from the command line

### Step 3: Confirm The Installation
Open `PowerShell` or `Command Prompt` and run:

```powershell
git --version
```

You should see a version number.

## Optional First-Time Git Identity Setup
If this is your first time using `Git`, you may want to set your name and email.

Run these commands with your own details:

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

You only need to do this once on a computer.

## How To Download This Repo With Git
### Step 1: Copy The Repository URL
On GitHub:
1. Open the repository page.
2. Click the green `Code` button.
3. Copy the HTTPS URL.

### Step 2: Open A Terminal
Choose where you want the folder to live on your computer.

Examples:
- `Documents`
- `Desktop`
- a dedicated `projects` folder

### Step 3: Clone The Repo
Run:

```bash
git clone <repository-url>
```

Example:

```bash
git clone https://github.com/davidpcg01/hands-on-ml-cursor.git
```

### Step 4: Open The Downloaded Folder
After cloning, move into the folder:

```bash
cd hands-on-ml-cursor
```

Then open that folder in `Cursor`, `VS Code`, or your file browser.

## Basic Git Commands You May Find Useful
Check the current repo status:

```bash
git status
```

Download the latest changes from GitHub:

```bash
git pull
```

See which branch you are on:

```bash
git branch
```

## If `git clone` Does Not Work
- Make sure `Git` is installed by running `git --version`.
- Check that you copied the full repository URL.
- Make sure you have internet access.
- If you still get stuck, use the `Download ZIP` option instead.

## What To Do Next
Once the files are on your computer:
- use `cursor-setup-and-ai-workflow.md` to run the `Cursor` exercise
- open the files in `data/`
- use the prompts in `cursor-prompts/`
