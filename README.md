# Sethryvia Futures website

Ready-to-upload static website. No installation or build is required.

## Upload to GitHub
1. Extract this ZIP on your computer.
2. Open your GitHub repository, choose Add file > Upload files.
3. Upload the CONTENTS of this extracted folder, including the assets folder. index.html must appear at the repository root, not inside another folder. Do not upload the ZIP itself.
4. Commit the files to main.
5. In Settings > Pages choose Deploy from a branch, main, /(root), then Save.
6. Add your actual domain under Settings > Pages > Custom domain, then configure Namecheap DNS.
7. Enable Enforce HTTPS once GitHub finishes its DNS and certificate checks.

No CNAME file is included because your domain name has not yet been provided. Saving the custom domain in GitHub creates it for branch deployments.

## Files
- index.html: Home
- about.html: About us
- programmes.html: Our programmes
- partner.html: Partnership and contact information
- styles.css: Shared responsive styling
- assets/image1.png: SFL logo
- .nojekyll: Serves the static files without Jekyll processing

Open index.html locally to preview. The contact button opens the visitor's email application; there is no contact-form backend.

This export includes the approved headline, enlarged logo with its underline hidden, revised organisation wording and Our commitment section. Source snapshot: d9fe5c3dae0f4218e28aed8f76adab12253a3cd7.
