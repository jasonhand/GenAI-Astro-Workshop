# Part 5: Publishing Your Website

**Duration: 45-60 minutes**

## Step 14: Preparing for Deployment (15-20 minutes)

**What we'll do:** Get our code ready to go live

### Final testing:
- Test all pages and links
- Check mobile responsiveness
- Verify all content is correct

### Understanding the build process:
- Run: `npm run build`
- **What this does:** Creates optimized files for production
- Creates a `dist/` folder with your built website

### Git basics:
- Check status: `git status`
- Add changes: `git add .`
- Commit changes: `git commit -m "Update homepage"`
- Push to GitHub: `git push`

## Step 15: Deploying to Netlify (15-20 minutes)

**What we'll do:** Make your website live on the internet

### Automatic deployment:
- Your site should automatically deploy when you push to GitHub
- Check Netlify dashboard for deployment status

### Understanding the deployment process:
- Netlify watches your GitHub repository
- When you push changes, it automatically builds and deploys
- Usually takes 1-3 minutes

### Troubleshooting deployment:
- Check build logs if something fails
- Common issues and solutions
- Using Claude to debug build errors

## Step 16: Custom Domain Setup (15-20 minutes)

**What we'll do:** Give your site a real web address

### Free Netlify domain:
- Every site gets a random name like `amazing-cupcake-123.netlify.app`
- Change it to something memorable
- Go to Site Settings → Domain Management

### Understanding domains:
- What is a domain name?
- Free vs. paid domains
- How DNS works (simplified)

### Optional: Custom domain:
- If you want to buy a real domain (.com, .org, etc.)
- How to connect it to Netlify
- We won't require this for the workshop

---

[← Previous](04-tailwind-ai.md) | [Home](../README.md) | [Next →](06-advanced.md)