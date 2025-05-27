# Part 4: Styling with Tailwind and AI

**Duration: 60-75 minutes**

## Step 11: Tailwind CSS Fundamentals (20-25 minutes)

**What we'll learn:** How to style without writing CSS

### Core concepts:
- **Utility classes:** `bg-red-500`, `text-center`, `p-4`
- **Responsive design:** `md:text-lg`, `lg:grid-cols-3`
- **Hover states:** `hover:bg-blue-600`

### Common patterns:
- **Layouts:** `flex`, `grid`, `container`, `mx-auto`
- **Spacing:** `p-4` (padding), `m-2` (margin), `space-y-4`
- **Colors:** `bg-blue-500`, `text-gray-800`

### Using the Tailwind documentation:
- Browse [tailwindcss.com](https://tailwindcss.com)
- Search for specific utilities
- Copy and paste classes

## Step 12: Finding Inspiration and Using AI (20-25 minutes)

**What we'll do:** Find inspiration from real Tailwind sites and recreate designs with Claude

### Finding design inspiration from showcase sites:

**Option 1: Astro Showcase**
- Go to [astro.build/showcase](https://astro.build/showcase)
- Browse through featured Astro websites (IKEA, Porsche, Netlify, Cloudflare, etc.)
- **What you'll see:** Real websites built with Astro by major companies
- **Perfect for this workshop:** These sites show what's possible with Astro specifically

**Option 2: Tailwind Showcase**
- Go to [tailwindcss.com/showcase](https://tailwindcss.com/showcase)
- Browse through the featured websites (NASA, OpenAI, Shopify, The Verge, etc.)
- **What you'll see:** Real websites built with Tailwind CSS by major companies

**What to look for on both showcases:**
- Click on a site that appeals to you and explore it
- Take note of design elements you like:
  - Color schemes and typography
  - Layout patterns (hero sections, cards, navigation)
  - Button styles and spacing
  - Overall visual style
- **Pro tip:** Some sites appear on both showcases (like Netlify and Cloudflare) - these use both Astro AND Tailwind!

### Choose your inspiration:
- Pick ONE website from either showcase that you find appealing
- Take a screenshot of the homepage or a specific section you like
- **Good choices for beginners from Astro Showcase:**
  - **The Guardian Engineering** - Clean blog/documentation style
  - **Marie Curie** - Nonprofit/charity design
  - **Firebase Studio** - Modern tech company look
  - **Eva Decker** - Personal portfolio style
- **Good choices for beginners from Tailwind Showcase:**
  - **Lemon Squeezy** - Clean SaaS design
  - **Wealthfront** - Professional fintech look
  - **Laracon Online** - Conference/event style
  - **Spotlight Template** - Personal website style

### Using Claude in Cursor to recreate the design:
- Open Cursor and make sure Claude is connected
- Upload your screenshot to Claude
- Use these prompts:

**Initial prompt:**
"I want to style my Astro website to resemble this design from the Tailwind showcase. Can you help me update my homepage (src/pages/index.astro) to have a similar look and feel? Focus on the color scheme, typography, and overall layout."

**Follow-up prompts:**
- "Can you make this responsive for mobile devices?"
- "How can I recreate this specific section using Tailwind classes?"
- "What Tailwind classes would give me a similar color palette?"
- "Can you explain why you chose these specific classes?"

### Iterating with AI:
- Ask for variations: "Make this more modern" or "Make it more minimalist"
- Ask for improvements: "How can I make this more accessible?"
- Ask for explanations: "Why did you use `bg-gradient-to-r` instead of a solid color?"
- Request specific changes: "Can you make the buttons more prominent?"

## Step 13: Building Components (20-25 minutes)

**What we'll do:** Create reusable pieces of your website

### Understanding components:
- Reusable pieces of code
- Keep your project organized
- Make changes in one place, update everywhere

### Create a simple component:
- Make `src/components/Card.astro`
- Accept props (data passed to component)
- Use the component in multiple places

### Using Claude for components:
- "Create a card component that displays a title, description, and button"
- "Make this component accept different color schemes"
- "Add hover effects to this card"

---

[← Previous](03-create-site.md) | [Home](../README.md) | [Next →](05-deploy.md)