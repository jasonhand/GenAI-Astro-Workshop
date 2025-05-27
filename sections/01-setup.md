# Part 1: Setting Up Your Development Environment

**Duration: 20-30 minutes**  
**Prerequisites: Complete [Part 0: Prerequisites Check](00-prerequisites-check.md) first**

> **🚀 Using GitHub Codespaces!** No local installation needed - everything runs in your browser!

## Step 1: Create Your GitHub Account (5-10 minutes)

**What we'll do:** Set up your GitHub account and verify Codespaces access

### Create GitHub Account
1. Go to [github.com](https://github.com)
2. Click "Sign up"
3. **Choose your username carefully** - this will be part of your website URL!
   - Example: If your username is `johndoe`, your site might be `johndoe.github.io`
   - Use lowercase letters, numbers, and hyphens only
   - Make it professional - you might use this for future projects
4. Complete the signup process
5. **Verify your email address** (important for Codespaces access)

### Verify Codespaces Access
1. Once logged into GitHub, visit: https://github.com/codespaces
2. You should see the Codespaces dashboard
3. If you see "Get started with Codespaces," you're all set!

## Step 2: Create Other Essential Accounts (10-15 minutes)

**What we'll do:** Set up accounts for deployment and AI assistance

### Netlify Account (5 min)
1. Go to [netlify.com](https://netlify.com)
2. Click "Sign up"
3. **Choose "Sign up with GitHub"** (this makes integration much easier)
4. Authorize Netlify to access your GitHub account
5. Complete your profile setup

### Claude AI Account (5 min)
1. Go to [claude.ai](https://claude.ai)
2. Sign up for a free account
3. Verify your email
4. We'll use Claude to help write and improve our code

### Why These Accounts?
- **GitHub**: Hosts our code and provides Codespaces
- **Netlify**: Automatically deploys our website from GitHub
- **Claude AI**: Helps us write better code faster

## Step 3: Launch Your First Codespace (5-10 minutes)

**What we'll do:** Create a development environment in the cloud

### Option A: Use Our Workshop Template (Recommended)

1. **Visit our workshop template**: [Create template link - we'll add this]
2. Click **"Use this template"** → **"Create a new repository"**
3. Name your repository: `my-astro-website` (or choose your own name)
4. Make sure it's set to **"Public"** (required for free GitHub Pages hosting)
5. Click **"Create repository"**
6. Once created, click the **"Code"** button → **"Codespaces"** tab
7. Click **"Create codespace on main"**

### Option B: Start from Scratch

1. Go to [github.com/codespaces](https://github.com/codespaces)
2. Click **"New codespace"**
3. Choose **"Blank"** template
4. Click **"Create codespace"**

### What Happens Next

Your Codespace will launch with:
- ✅ **VS Code in your browser** (full-featured editor)
- ✅ **Terminal access** (for running commands)
- ✅ **Node.js & NPM** (pre-installed)
- ✅ **Git** (pre-configured with your GitHub account)
- ✅ **File explorer** (to manage your project files)

**This usually takes 30-60 seconds to fully load.**

## Step 4: Tour Your Development Environment (5 minutes)

**What we'll do:** Get familiar with VS Code in the browser

### Key Areas of VS Code

1. **File Explorer** (left sidebar)
   - Shows all your project files
   - Click files to open them

2. **Editor** (center)
   - Where you'll write your code
   - Supports syntax highlighting and autocomplete

3. **Terminal** (bottom panel)
   - Access with `Ctrl+`` (backtick) or `View → Terminal`
   - Run commands here (like `npm install`)

4. **Extensions** (left sidebar, puzzle piece icon)
   - Pre-installed with useful web development extensions

### Test Your Environment

Let's verify everything works:

1. **Open the terminal** (`Ctrl+`` or `View → Terminal`)
2. **Run these commands** one by one:
   ```bash
   node --version
   npm --version
   git --version
   ```
3. You should see version numbers for all three tools

### Create Your First File

1. **Right-click in the File Explorer** → **"New File"**
2. **Name it**: `hello.txt`
3. **Type**: `Hello from my Codespace!`
4. **Save**: `Ctrl+S`

Congratulations! You just created your first file in the cloud! 🎉

## Step 5: Understanding Codespaces (5 minutes)

**What we'll do:** Learn how Codespaces works and best practices

### How Codespaces Works
- **Cloud computer**: Your Codespace runs on GitHub's servers
- **Persistent storage**: Your files are saved automatically
- **Auto-sleep**: Codespaces sleep after 30 minutes of inactivity
- **Resume anytime**: Click to wake up exactly where you left off

### Best Practices
- **Save your work**: Files auto-save, but commit to Git regularly
- **Stop when done**: Stop your Codespace to save on free hours
- **One project per Codespace**: Keep projects organized

### Managing Your Codespace

**To stop your Codespace:**
1. Click your profile picture (top right)
2. Select "Your codespaces"
3. Click the "..." menu next to your Codespace
4. Select "Stop codespace"

**To restart later:**
1. Go to [github.com/codespaces](https://github.com/codespaces)
2. Click on your Codespace name to resume

## Troubleshooting

### Codespace Won't Load
- **Check internet connection**
- **Try a different browser** (Chrome/Edge work best)
- **Disable browser extensions** temporarily
- **Clear browser cache** and try again

### "Codespaces not available"
- **Verify email address** on your GitHub account
- **Check GitHub status**: https://www.githubstatus.com
- **Try again in a few minutes**

### Slow Performance
- **Close unnecessary browser tabs**
- **Use Chrome or Edge** for best performance
- **Check your internet speed**

## What's Next?

You now have:
- ✅ **GitHub account** with Codespaces access
- ✅ **Netlify account** for deployment
- ✅ **Claude AI account** for coding help
- ✅ **Working development environment** in the cloud

Ready to learn about the tools we'll use? Let's continue to [Part 2: Understanding Our Tools and Framework](02-tools-overview.md)!

---

[← Previous](00-prerequisites-check.md) | [Home](../README.md) | [Next →](02-tools-overview.md)