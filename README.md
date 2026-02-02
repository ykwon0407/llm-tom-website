# LLM Top-of-Mind Project Page

Project website for "What LLMs Think When You Don't Tell Them What to Think About"

## Structure

```
llm-tom-website/
├── index.html                          # Main landing page
├── interactive_LLM_top_of_mind.html    # Interactive UMAP visualization
├── figures/                            # Static figures for the page
│   └── (add your figures here)
└── README.md
```

## Deployment

### Option 1: GitHub Pages (Free)

1. Create a new GitHub repository (e.g., `llm-tom-website`)
2. Push this folder to the repository
3. Go to **Settings → Pages**
4. Under "Source", select branch `main` and folder `/ (root)`
5. Click Save - your site will be available at `https://yourusername.github.io/llm-tom-website/`

### Option 2: Netlify (Free, drag & drop)

1. Go to [netlify.com](https://netlify.com) and sign up
2. Drag and drop the `llm-tom-website` folder onto the dashboard
3. Your site is live instantly with a random URL (can customize later)

### Option 3: Host on your own server

Simply copy the files to any web server (Apache, Nginx, etc.)

### Local Preview

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .
```

Then open `http://localhost:8000` in your browser.

## TODO

- [ ] Replace placeholder figures with actual images
- [ ] Update author names and affiliations
- [ ] Add correct paper/dataset links
- [ ] Update GitHub repository link
- [ ] Add `interactive_model_comparison.html` if available
