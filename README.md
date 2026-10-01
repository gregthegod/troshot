# Troshot Media website

Static site: no build step. Deploy the whole folder.

## Deploy with the Vercel CLI
    cd troshot-site
    npx vercel          # preview deployment
    npx vercel --prod   # production

## Deploy from GitHub
Push this folder to a repository, then in Vercel: Add New > Project > Import the repo.
Framework preset: Other. Build command: none. Output directory: leave empty.

## Replacing placeholders
- Photos: assets/img/  (keep the same file names, or edit assets/data.js)
- Videos: assets/vid/  (H.264 MP4, muted loops)
- Copy, projects, crew, quotes: the data block at the top of the script in index.html
