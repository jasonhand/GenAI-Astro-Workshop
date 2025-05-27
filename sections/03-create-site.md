# Part 3: Creating Your First Website

**Duration: 90-120 minutes**

## Step 6: Starting with an Astro Template (20-25 minutes)

**What we'll do:** Create a new repository and get a basic website running locally

### Connect GitHub to Netlify:
- Log into Netlify with your GitHub account
- Click "New site from Git"
- Choose GitHub and authorize Netlify to access your repositories
- **What this does:** Allows Netlify to automatically deploy when you update your code

### Deploy an Astro template:
- In Netlify, look for "Browse templates" or "Deploy from template"
- Search for "Astro" templates
- Choose a beginner-friendly template (we recommend "Astro Blog" or "Astro Portfolio")
- Click "Deploy to Netlify"
- **Important:** This creates a new repository in YOUR GitHub account
- Give your repository a name (like "my-first-website" or "portfolio-site")
- Click "Save & Deploy"
- Wait 2-3 minutes for deployment to complete
- **Result:** You now have a live website AND a GitHub repository!

### Understanding what just happened:
- ✅ Netlify created a new repository in your GitHub account
- ✅ Netlify deployed your site and gave you a live URL
- ✅ Your site will automatically update when you change the code
- ✅ You can now work on this code locally on your computer

### Clone the repository locally:

**Step 1: Find your repository URL**
- Go to [github.com](https://github.com) and sign in
- Click on your profile picture (top right) → "Your repositories"
- Find the repository Netlify just created (it will have the name you chose)
- Click on the repository name to open it
- Click the green "Code" button
- Make sure "HTTPS" is selected (not SSH)
- Click the copy button to copy the URL (it will look like: `https://github.com/yourusername/your-repo-name.git`)

**Step 2: Choose where to put your project**
- Open terminal/command prompt
- Navigate to where you want to store your project:
  - **Windows:** `cd C:\Users\YourName\Documents` or `cd Desktop`
  - **Mac:** `cd ~/Documents` or `cd ~/Desktop`
  - **Create a new folder (optional):** `mkdir my-websites && cd my-websites`

**Step 3: Clone the repository**
- Run: `git clone [paste-your-copied-url-here]`
- **Example:** `git clone https://github.com/yourusername/my-first-website.git`
- **What this does:** Downloads all the code to your computer
- Navigate into the project: `cd [your-repo-name]`
- **Example:** `cd my-first-website`

**Step 4: Verify everything worked**
- Run: `ls` (Mac/Linux) or `dir` (Windows) to see the files
- You should see files like `package.json`, `astro.config.mjs`, and folders like `src/`

## Step 7: Understanding the Project Structure (15-20 minutes)

**What we'll learn:** How Astro projects are organized

### Open project in Cursor:
- File → Open Folder → Select your project

### Key folders and files:
- `src/` - Where our website code lives
- `src/pages/` - Each file becomes a webpage
- `src/components/` - Reusable pieces of our site
- `src/content/` - Markdown files for blog posts/content
- `package.json` - Lists our project dependencies
- `astro.config.mjs` - Astro settings

### Understanding the file structure:
- `.astro` files - Astro components (HTML-like)
- `.md` files - Markdown content
- `.css` files - Styles (though we'll use Tailwind)

## Step 8: Running Your Site Locally (10-15 minutes)

**What we'll do:** See your website on your computer

### Install dependencies:
- In terminal (in your project folder): `npm install`
- **What this does:** Downloads all the code libraries your project needs

### Start development server:
- Run: `npm run dev`
- **What this does:** Starts a local web server
- Open browser to `http://localhost:4321` (or whatever URL it shows)

### Understanding development mode:
- Changes you make will automatically update in browser
- This is where you'll preview your changes

## Step 9: Making Your First Changes (25-30 minutes)

**What we'll do:** Customize the template to make it yours

### Edit the homepage:
- Open `src/pages/index.astro`
- Change the title and main heading
- Update the description text
- Save and see changes in browser

### Understanding Astro syntax:
- HTML-like structure
- Frontmatter (code between ---) runs on server
- Body contains your HTML

### Using Claude to help:
- Ask Claude: "How do I change the background color of this hero section?"
- Ask Claude: "Can you help me add a new section with three columns?"

### Adding Tailwind classes:
- Find existing classes in the template
- Experiment with changing colors: `bg-blue-500`, `text-white`
- Try different sizes: `text-xl`, `text-2xl`, `text-3xl`

## Step 10: Adding New Content (20-30 minutes)

**What we'll do:** Create new pages and content

### Add a new page:
- Create `src/pages/about.astro`
- Copy structure from index.astro
- Customize the content

### Add blog posts using Markdown:
- Create files in `src/content/blog/` (if template has blog)
- Use markdown syntax for formatting
- Add frontmatter for metadata (title, date, description)

### Understanding markdown basics:
- `# Heading 1`, `## Heading 2`
- `**bold text**`, `*italic text*`
- `[link text](url)`
- `![alt text](image-url)`

---

[← Previous](02-tools-overview.md) | [Home](../README.md) | [Next →](04-tailwind-ai.md)