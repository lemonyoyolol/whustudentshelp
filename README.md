# WHUSH static website

A deployable static website matching the provided Framer screenshots.

## Pages
- `index.html` — home page
- `team.html` — team page
- `projects.html` — all 6 project cards
- `project.html?project=learning-spaces` etc. — reusable project detail page

## Edit links
Open `script.js` and update the `WHUSH` object if the donation/link destinations change.

## Deploy
Upload the whole folder to any static host, or drag it into Netlify/Vercel. Keep the file structure intact so the assets load correctly.


Update: The black LET'S CONNECT footer is generated once in script.js and injected into every page through renderCommon(), so it appears at the bottom of index.html, team.html, projects.html, and project.html. Uploaded WHUSH logo/project image assets have also been added to assets/.


## Changing pictures
All website images are stored in the `assets/` folder. To replace a picture, keep the same filename and overwrite the old file, for example:

- `assets/hero-event.jpg` = large homepage hero image
- `assets/project-learning.jpg` = Learning Spaces card/detail image
- `assets/project-teacher.jpg` = Teacher Support card/detail image
- `assets/project-digital.jpg` = Digital Learning card/detail image
- `assets/project-community.jpg` = Community Classrooms card/detail image
- `assets/team-hero.jpg` = large team group photo
- `assets/johannes.jpg`, `assets/finja.jpg`, etc. = team portraits
- `assets/logo.png` and `assets/logo-white.png` = regular and footer logos

Use JPG or PNG files with the same exact names. For best quality, use images at least 1600px wide for hero/project photos and at least 800px wide for portraits.

Donation links: all Donate buttons and PayPal links point to `https://www.paypal.com/paypalme/whushev`.

## Image replacement notes
The homepage hero image is `assets/hero-event.jpg`. Team portraits are stored as lowercase JPG files such as `assets/ruohan.jpg`, `assets/felix.jpg`, `assets/finja.jpg`, `assets/christine.jpg`, `assets/isabelle.jpg`, `assets/lotta.jpg`, `assets/paula.jpg`, `assets/johannes.jpg`, and `assets/kira.jpg`. Replace a file with a new photo using the same filename to update the website without changing code.


Photo updates in v6:
- `assets/team-hero.jpg` is the uploaded Teamfoto image for the Team page.
- `assets/sarina.jpg` is the uploaded Sarina photo.
- `assets/lena.jpg` is the uploaded Lena Peters photo, added to the Team page as Project Development.


Latest update: removed decorative icons, applied WHUSH brand colors (#0A9CFD, #03369A, #939598), and widened the responsive layout for larger screens.

v19 changes:
- Header links Home, Projects, Team, and Donate now appear as white rounded buttons.
- The gradient slides in quickly on hover, matching the homepage involvement tile interaction.
- Donate in the header is no longer permanently gradient; it stays white until hover.

v24 update:
- Footer background restored to black.
- Learning Spaces renamed to Charity Concert with Every Winter timeline and updated description.
- Charity Concert project uses a swipeable/scrollable image carousel in the order Konzert_v2, Konzert_v1, Konzert_v3.
- Carousel includes left/right arrow controls and advances automatically every 10 seconds in a loop.


## v29 updates
- Replaced the second project formerly shown as Teacher Support with Rhine Clean-Up.
- Added Rhine Clean-Up title, subtitle, annual timing, full description, and three uploaded Rhine photos.
- Footer background remains black.
