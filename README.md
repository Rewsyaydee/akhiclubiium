# AKHI CLUB IIUM - Outreach & Character

Static site for AKHI CLUB IIUM. Entry point is index.html and assets live under testinghtml/.

## Local preview

Open index.html in a browser, or use a simple local server if you prefer.

## Publish to GitHub (manual)

1. Create a new GitHub repository.
2. In this folder:
   - git init
   - git add .
   - git commit -m "Initial commit"
   - git branch -M main
   - git remote add origin <your-repo-url>
   - git push -u origin main

## Manual deployment

Upload the following to your hosting root:
- index.html
- testinghtml/

Make sure testinghtml/ stays next to index.html so all media paths resolve.

## Notes

This site uses the Tailwind CDN, so it needs an internet connection at runtime.
