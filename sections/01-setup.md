# Part 1: Setting Up Your Development Environment

**Duration: 45-60 minutes**  
**Prerequisites: None - We'll set up everything together**

## Step 1: Create Essential Accounts (20 minutes)

**What we'll do:** Set up free accounts for all the services we'll use

### GitHub Account (5 min)
- Go to [github.com](https://github.com)
- Click "Sign up" 
- Choose a username (this will be part of your website URL)
- Verify email address

### Netlify Account (5 min)
- Go to [netlify.com](https://netlify.com)
- Click "Sign up"
- Sign up using your GitHub account (easiest option)

### Anthropic Account (5 min)
- Go to [claude.ai](https://claude.ai)
- Sign up for free Claude account
- We'll use this to help write code

### Cursor Account (5 min)
- Go to [cursor.sh](https://cursor.sh)
- Sign up for free account (we'll download the app next)

## Step 2: Install Required Software (25-35 minutes)

**What we'll do:** Download and install the tools we need to build websites

### Install Cursor IDE (10 min)
- Download from [cursor.sh](https://cursor.sh)
- Install on your computer (Mac/Windows/Linux)
- Launch the application
- Sign in to your Cursor account
- Brief tour of the interface

### Install Node.js and NPM (10-15 min)

**Option 1: Command Line Installation (Recommended)**
- **Windows:** 
  - Install via Chocolatey: `choco install nodejs-lts` (if you have Chocolatey)
  - Or install via winget: `winget install OpenJS.NodeJS.LTS`
- **Mac:** 
  - Install via Homebrew: `brew install node@lts` (if you have Homebrew)
  - Or use the website method below
- **Linux:** 
  - Ubuntu/Debian: `curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash - && sudo apt-get install -y nodejs`
  - Or use your distribution's package manager

**Option 2: Website Download**
- Go to [nodejs.org](https://nodejs.org)
- Download the LTS version (recommended)
- Install on your computer

**What is Node.js?** A tool that lets us run JavaScript on our computer  
**What is NPM?** A package manager that helps us install code libraries  
**Test installation:** Open terminal and type `node --version` and `npm --version`

### Install Git (5-10 min)

**Option 1: Command Line Installation (Recommended)**
- **Windows:** 
  - Install via Chocolatey: `choco install git`
  - Or install via winget: `winget install Git.Git`
- **Mac:** 
  - Install via Homebrew: `brew install git`
  - Or use Xcode Command Line Tools: `xcode-select --install`
- **Linux:** 
  - Ubuntu/Debian: `sudo apt update && sudo apt install git`
  - CentOS/RHEL: `sudo yum install git` or `sudo dnf install git`
  - Arch: `sudo pacman -S git`

**Option 2: Website Download**
- Download from [git-scm.com](https://git-scm.com)
- Install with default settings

**What is Git?** A tool that tracks changes to our code  
**Test installation:** Open terminal and type `git --version`

## Step 3: Terminal Basics (10-15 minutes)

**What we'll do:** Learn the basics of using the command line

### What is a terminal?
A text-based way to give commands to your computer

### Opening terminal:
- **Mac:** Press Cmd+Space, type "Terminal"
- **Windows:** Press Win+R, type "cmd" or use "Command Prompt"
- **Or use Cursor's built-in terminal**

### Basic commands we'll use:
- `cd` - change directory (folder)
- `ls` (Mac) or `dir` (Windows) - list files
- `mkdir` - make a new folder
- Don't worry - we'll guide you through each command!

---

[Home](../README.md) | [Next →](02-tools-overview.md)