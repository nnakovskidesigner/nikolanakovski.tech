# nikolanakovski.tech

My personal AI-built portfolio and blog for nikolanakovski.tech — static site generated and deployed via Git to Namecheap.

## How to update, commit, push, and deploy

1. **Edit your files**
   - Make changes to any HTML, CSS, or JS files as needed.

2. **Commit your changes**
   ```sh
   git add .
   git commit -m "Describe your changes"
   ```

3. **Push to GitHub**
   ```sh
   git push origin main
   ```

4. **Deploy via cPanel**
   - Log in to your cPanel account.
   - Open the Terminal or File Manager.
   - Run the deployment script:
     ```sh
     bash .cpanel.yml
     ```
   - This will copy all site files to `/home/nikobusc/public_html`.

## File Structure
- `index.html` — Home page
- `about.html` — About page
- `blog/index.html` — Blog index
- `blog/first-illumination.html` — First blog article
- `404.html` — Not found page
- `assets/css/` — Custom CSS
- `assets/js/` — Custom JS
- `assets/img/` — Images
- `.cpanel.yml` — Deployment script

## Notes
- No frameworks or build tools required.
- Uses Tailwind CSS via CDN.
- Telekom Magenta (#E20074) for accent color.
- All pages are responsive and lightweight.
