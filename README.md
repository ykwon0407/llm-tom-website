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

### GitHub Pages

1. Create a new repository (e.g., `llm-tom-website` or `yourusername.github.io`)
2. Push this folder to the repository
3. Go to Settings → Pages → Select branch `main` and folder `/ (root)`
4. Your site will be available at `https://yourusername.github.io/llm-tom-website/`

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
