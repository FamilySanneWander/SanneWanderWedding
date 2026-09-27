Sicilian Wedding Website
A zero-cost, static wedding website designed for GitHub Pages.
Edit your information
Open `index.html` and search for `\[insert` to find every placeholder that needs completing.
Add the RSVP
Near the bottom of `index.html`, find:
`<a class="button" href="#" ...>`
Replace `#` with the URL of your Google Form or other RSVP form.
Add photographs later
The first version uses coloured image placeholders. You can later create an `images` folder, add compressed JPG/WebP files, and replace the placeholder sections with those images.
Publish for free with GitHub Pages
Create a new public GitHub repository, for example `wedding`.
Upload `index.html` (README is optional).
Open the repository's Settings → Pages.
Under Build and deployment, select Deploy from a branch.
Select the `main` branch and `/ (root)`, then save.
GitHub will show the public site address once deployment finishes.
No build system or dependencies are required.
