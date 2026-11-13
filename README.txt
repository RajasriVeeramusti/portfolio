RAJASRI PORTFOLIO — DEPLOYMENT GUIDE
====================================

Files:
- index.html: portfolio website
- RajasriVeeramustiResume.pdf: resume used by the download button

DEPLOY WITH GITHUB PAGES
1. Create a public repository on GitHub (for example: portfolio).
2. Upload index.html and RajasriVeeramustiResume.pdf directly into the repository root.
3. Open repository Settings > Pages.
4. Under Build and deployment, choose "Deploy from a branch".
5. Select branch "main" and folder "/ (root)", then Save.
6. Wait for the Pages deployment workflow to finish successfully.
7. Your site URL will look like: https://YOUR-USERNAME.github.io/REPOSITORY-NAME/

UPDATING PROJECT DEMO LINKS LATER
1. Open index.html in VS Code or GitHub's edit view.
2. Find the project card's text: "Live demo link to be added".
3. Replace that span with an anchor, for example:
   <a class="demo" href="https://YOUR-DEPLOYED-APP-URL" target="_blank" rel="noopener">Live demo ↗</a>
4. Commit the changes. GitHub Pages automatically republishes the site.

UPDATE PROFILE LINKS
Find the GitHub and LinkedIn buttons near the Contact section and replace their general website URLs with your own profile URLs.

NOTE
Project demo buttons and personal profile destinations are not linked to real project deployments yet because those URLs were not provided. Do not leave placeholder URLs in the published portfolio; replace them when available.
