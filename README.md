# Valentine's Day Proposal

A romantic Valentine's Day proposal site built with Astro, ready for GitHub Pages hosting.

## Local Development

```bash
# Install dependencies
pnpm install

# Start dev server
pnpm dev

# Build for production
pnpm build
```

## Deploy to GitHub Pages

1. **Create a GitHub repository** named `valentines` (or whatever you prefer)

2. **Update the config** in `astro.config.mjs`:
   - Change `site` to `https://YOUR_USERNAME.github.io`
   - Change `base` to `/YOUR_REPO_NAME` (e.g., `/valentines`)

3. **Push your code:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/valentines.git
   git push -u origin main
   ```

4. **Enable GitHub Pages:**
   - Go to your repo Settings > Pages
   - Under "Build and deployment", set Source to **GitHub Actions**

5. The site will automatically deploy when you push to `main`. Your Valentine will find it at:
   `https://YOUR_USERNAME.github.io/valentines`

## Customization

Edit `src/pages/index.astro` to:
- Change the love message
- Customize colors in the `:root` CSS variables
- Add your names or special details
