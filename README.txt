MOG Finance V6 - Cloudflare Pages package

Files in this folder are the static production site.
Recommended deployment: connect the existing GitHub repository to Cloudflare Pages so pushes to main deploy automatically.
Static HTML configuration: production branch main; build command exit 0; build output directory the repository root (or the folder containing index.html).
After Cloudflare assigns the *.pages.dev URL, add that exact HTTPS origin to the MOG Finance Google OAuth client's Authorized JavaScript origins.
