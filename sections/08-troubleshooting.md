# Troubleshooting Guide

## Common Issues and Solutions

### Terminal/Command Line Problems

#### "Command not found" errors
- **Problem:** Terminal says `node`, `npm`, or `git` command not found
- **Solution:** 
  - Restart your terminal after installation
  - Check if software was installed correctly
  - On Windows, try running as administrator
  - Verify installation path is in your system PATH

#### Permission issues
- **Problem:** "Permission denied" or "Access denied" errors
- **Solution:**
  - On Mac/Linux: Use `sudo` before commands (e.g., `sudo npm install`)
  - On Windows: Run terminal as administrator
  - Check file/folder permissions

#### Navigation problems
- **Problem:** Can't find your project folder
- **Solution:**
  - Use `pwd` (Mac/Linux) or `cd` (Windows) to see current location
  - Use `ls` (Mac/Linux) or `dir` (Windows) to list contents
  - Use `cd ..` to go up one folder
  - Use `cd ~` to go to home directory

### Installation Issues

#### Node.js installation problems
- **Problem:** Node.js won't install or doesn't work
- **Solution:**
  - Download from official nodejs.org website
  - Choose LTS (Long Term Support) version
  - Restart computer after installation
  - Try alternative: Install via package manager (Homebrew on Mac, Chocolatey on Windows)

#### NPM permission errors
- **Problem:** NPM commands fail with permission errors
- **Solution:**
  - Configure npm to use a different directory for global packages
  - Use a Node version manager (nvm)
  - Run terminal as administrator (Windows)

#### Git configuration issues
- **Problem:** Git asks for username/email or authentication fails
- **Solution:**
  - Set up Git identity: 
    ```bash
    git config --global user.name "Your Name"
    git config --global user.email "your.email@example.com"
    ```
  - Set up GitHub authentication (personal access token)
  - Use GitHub Desktop as alternative

### Development Server Issues

#### Port conflicts
- **Problem:** "Port already in use" error
- **Solution:**
  - Kill existing process using the port
  - Use a different port: `npm run dev -- --port 3001`
  - Restart your computer to clear all processes

#### Module not found errors
- **Problem:** "Cannot find module" errors
- **Solution:**
  - Delete `node_modules` folder and `package-lock.json`
  - Run `npm install` again
  - Check if you're in the correct project directory
  - Verify package.json exists

#### Hot reload not working
- **Problem:** Changes don't appear automatically in browser
- **Solution:**
  - Hard refresh browser (Ctrl+F5 or Cmd+Shift+R)
  - Check browser console for errors
  - Restart development server
  - Check if files are being saved correctly

### Deployment Issues

#### Build failures
- **Problem:** Site fails to build on Netlify
- **Solution:**
  - Check build logs in Netlify dashboard
  - Ensure all dependencies are in package.json
  - Test build locally: `npm run build`
  - Check for syntax errors in your code

#### Environment variables
- **Problem:** Site works locally but not in production
- **Solution:**
  - Check if you're using environment variables
  - Add environment variables in Netlify dashboard
  - Ensure API keys and secrets are properly configured

#### Domain configuration problems
- **Problem:** Custom domain not working
- **Solution:**
  - Check DNS settings with domain provider
  - Wait for DNS propagation (can take 24-48 hours)
  - Verify domain is correctly added in Netlify
  - Check for HTTPS/SSL certificate issues

## Getting Help During Workshop

### Instructor assistance
- Raise your hand for immediate help
- Share your screen if needed
- Don't hesitate to ask questions

### Peer support
- Work with a partner when possible
- Share solutions with others facing similar issues
- Learn from others' approaches

### Using Claude for debugging
- Copy and paste error messages to Claude
- Ask: "What does this error mean and how do I fix it?"
- Share your code context for better help
- Ask for step-by-step debugging instructions

### Documentation and resources
- Check official documentation first
- Search Stack Overflow for specific errors
- Use GitHub issues for package-specific problems
- Bookmark useful resources for later

## Emergency Backup Plans

### If local development fails:
- Use GitHub Codespaces for cloud development
- Use online editors like CodeSandbox or StackBlitz
- Pair with someone whose setup is working

### If deployment fails:
- Use alternative hosting (Vercel, GitHub Pages)
- Deploy a simpler version first
- Focus on getting something live, then iterate

### If accounts don't work:
- Use instructor backup accounts temporarily
- Create accounts with different email addresses
- Use alternative services when possible

---

[← Previous](07-wrapup.md) | [Home](../README.md) | [Next →](09-materials.md)