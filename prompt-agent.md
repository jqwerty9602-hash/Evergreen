# Task: Refactor Existing Code into Clean Folder Structure

## Objective
Use the **existing code exactly as provided** and reorganize it into a
clean, professional folder and file structure.

⚠️ IMPORTANT RULES
- DO NOT change functionality
- DO NOT redesign UI
- DO NOT rewrite logic
- DO NOT optimize or refactor code behavior
- ONLY move code into proper files and folders
- Preserve 100% behavior and output

## What You Are Given
- Existing HTML, CSS, and assets
- The code already works locally and on Vercel

## What You Must Do
- Separate files properly
- Improve folder clarity
- Keep all relative paths correct
- Ensure site still runs without errors

## Target Folder Structure
/project-root
 ├── index.html
 ├── css/
 │   └── style.css
 ├── assets/
 │   ├── images/
 │   └── icons/
 ├── js/
 │   └── main.js
 ├── vercel.json
 └── README.md

## Rules for Each File
### index.html
- Contains semantic HTML only
- Links CSS and JS correctly
- No inline styles
- No inline scripts

### css/style.css
- Move ALL existing CSS here
- Keep selectors unchanged

### js/main.js
- Move ALL existing JS here (if any)
- No logic changes

### assets/
- Keep original filenames unless instructed
- Update paths correctly

### README.md
Include:
1. Project overview
2. Folder structure
3. How to run locally
4. How to deploy to Vercel

## Vercel Compatibility
- Static site only
- No build step
- No framework assumptions

## Output Rules
Return ONLY the following files:
- index.html
- css/style.css
- js/main.js (if JS exists)
- vercel.json
- README.md

No explanations.
No markdown formatting.
Code only.
