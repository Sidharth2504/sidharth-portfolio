# Portfolio Website

This is a simple static portfolio built with HTML, CSS, and JavaScript. It can be deployed easily to any static hosting service.

## Deployment Options

### GitHub Pages
1. Initialize a git repository and push to GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo>.git
   git push -u origin main
   ```
2. In the repository settings on GitHub, go to **Pages** and select the `main` branch (root) as the source.
3. After a few minutes, your site will be available at `https://<your-username>.github.io/<repo>/`.

### Netlify
1. Sign up at [Netlify](https://www.netlify.com/) and connect your GitHub repository.
2. Choose the repository and set the build command to `npm run build` (if you have one) or leave blank for simple static sites.
3. Set the publish directory to the project root (`/`).
4. Deploy and the site will be live at a Netlify-generated URL, which you can customize.

### Vercel
1. Go to [Vercel](https://vercel.com/) and import the repository.
2. Select "Other" for the framework if prompted, and use `/` as the output directory.
3. Deploy and obtain a live URL from Vercel.

### Other hosts
- **Firebase Hosting**: `firebase init` then `firebase deploy`
- **Surge**: `npm install -g surge` then `surge ./ "your-custom-domain.surge.sh"`

## Local Testing
Run a simple HTTP server:
```bash
python -m http.server 8000
```
Then open `http://localhost:8000` in your browser.

## Notes
- Make sure image `sidharth.jpg` and other assets are included in the repository.
- Update links (e.g. GitHub source code or live demos) before publishing.

Enjoy deploying your portfolio! Feel free to customize further.