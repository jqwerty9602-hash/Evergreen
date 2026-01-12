# Evergreen Marine Corp Website

## Project Overview
This is a static website for Evergreen Marine Corp. The project has been refactored from a single HTML file into a clean, professional folder structure with separated CSS, JavaScript, and assets.

## Folder Structure
```
/project-root
 ├── index.html          # Main HTML file with semantic markup
 ├── css/
 │   └── style.css       # All CSS styles
 ├── assets/
 │   ├── images/         # Image assets
 │   └── icons/          # Icon assets
 ├── js/
 │   └── main.js         # JavaScript functionality
 ├── vercel.json         # Vercel deployment configuration
 └── README.md           # This file
```

## How to Run Locally

### Option 1: Using a Simple HTTP Server
If you have Python installed:
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

If you have Node.js installed:
```bash
npx http-server -p 8000
```

Then open your browser to `http://localhost:8000`

### Option 2: Using Live Server (VS Code)
1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

### Option 3: Direct File Access
Simply open `index.html` directly in your web browser. Note that some features may not work due to CORS restrictions.

## How to Deploy to Vercel

### Method 1: Vercel CLI
1. Install Vercel CLI:
   ```bash
   npm install -g vercel
   ```

2. Deploy from the project directory:
   ```bash
   vercel
   ```

3. Follow the prompts to complete deployment

### Method 2: Vercel Dashboard
1. Go to [vercel.com](https://vercel.com)
2. Sign in or create an account
3. Click "New Project"
4. Import your Git repository or drag and drop the project folder
5. Vercel will automatically detect the static site and deploy it

### Method 3: Git Integration
1. Push your code to GitHub, GitLab, or Bitbucket
2. Connect your repository to Vercel
3. Vercel will automatically deploy on every push to the main branch

## Technical Details
- **Type**: Static website
- **No build step required**: All assets are pre-compiled
- **Framework**: Vanilla HTML/CSS/JavaScript
- **Deployment**: Optimized for Vercel static hosting

## Files Description
- **index.html**: Contains the semantic HTML structure with proper meta tags and references to external CSS/JS
- **css/style.css**: Contains all styling rules extracted from the original file (2.3MB)
- **js/main.js**: Contains JavaScript functionality (847 bytes)
- **vercel.json**: Configuration file for Vercel deployment
- **assets/**: Directory for storing images and icons (to be populated)

## Notes
- All inline styles have been extracted to `css/style.css`
- All inline scripts have been extracted to `js/main.js`
- The original file structure and behavior have been preserved
- No functionality changes were made during refactoring
