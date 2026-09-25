# StarsUU7 (starsuu7.net)

Official landing page and website portal for **StarsUU7** (UU7 / 777).

## Features

- Modern responsive landing page for mobile, tablet, and desktop
- Fast direct APK download action
- Interactive FAQ accordion sections
- Game showcase and features overview
- Floating social navigation bar (Telegram, WhatsApp, YouTube, Instagram, Facebook, Pinterest)
- SEO and Open Graph metadata configuration with Google Analytics tracking

## Project Structure

```
├── .gitignore          # Git ignore rules
├── index.html          # Main landing page
├── index_raw.html      # Original raw page template / backup
├── site.webmanifest    # Web application manifest
├── favicon.ico         # Website favicon
├── logo.webp           # Website logo
├── _astro/             # Bundled CSS and JavaScript assets
├── admin_uploads/      # Media and game banner images
├── wordpress/          # Content icons and promotional graphics
└── s/                  # Static assets and resources
```

## Running Locally

You can serve this project using any static HTTP server.

### Option 1: Python
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000`.

### Option 2: Node.js (npx serve)
```bash
npx serve .
```

### Option 3: VS Code / IDE Live Server
Right-click on `index.html` and select **"Open with Live Server"**.
