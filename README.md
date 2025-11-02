# Honey and Freida

A simple static website hosted on GitHub Pages.

## Local Development

To run this website locally:

1. Open `index.html` in your web browser
2. Or use a simple HTTP server:
   ```bash
   python3 -m http.server 8000
   ```
   Then visit `http://localhost:8000`

## GitHub Pages Setup

1. Push this repository to GitHub
2. Go to repository Settings > Pages
3. Set Source to "Deploy from a branch"
4. Select the `main` branch (or `master`) and `/ (root)` folder
5. Click Save

Your site will be available at `https://<username>.github.io/<repository-name>/`

## Custom Domain

To use a custom domain:

1. Update the `CNAME` file with your domain name
2. Configure your domain's DNS settings to point to GitHub Pages
3. See [GitHub Pages documentation](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site) for details

## Project Structure

```
.
├── .gitignore      # Git ignore patterns
├── CNAME           # Custom domain configuration
├── README.md       # This file
├── index.html      # Main HTML page
├── styles.css      # Stylesheet
└── script.js       # JavaScript file
```
