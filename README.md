# KIXORA — Connect. Share. Belong.

A responsive, Instagram-inspired social-network front-end prototype for GitHub Pages. It includes a light/dark theme and separate app views for Home, Explore, Clips, Messages, Communities, Notifications, Profile, Saved, and Settings.

## Run locally
Open `index.html` in a browser, or serve this folder with any static web server. The project uses plain HTML, CSS, and JavaScript; no build step or package install is needed.

## Publish with GitHub Pages
1. Create a GitHub repository named `KIXORA` (or another name you prefer).
2. Upload the **contents** of this folder to the repository root. `index.html` must be in the root.
3. Open **Settings → Pages**.
4. Under Build and deployment, select **Deploy from a branch**, choose `main` and `/(root)`, then save.
5. Wait for GitHub Pages to publish the site.

## Included interactions
- Sign-up and log-in demo flow; the name, username, and email flow into the profile and settings.
- Light (white) and dark (black/navy) themes.
- Edit profile, including a small profile-image upload.
- Create posts, attach small images, like, comment, save, share, and view saved posts.
- Explore search for sample people and posts, follow/unfollow sample profiles.
- Local demo conversations, new-message dialog, and message sending.
- Community join/create demo, notifications, profile tabs, settings controls, and JSON data export.
- Responsive mobile navigation and desktop sidebar.

## Important production limitations
This is a **front-end prototype**, not a secure production social network. Demo data is saved in the current browser's local storage and does not sync between users or devices. Do not use real passwords or sensitive personal information with this demo. Before a public launch, replace the demo sign-up/login with a secure authentication provider and connect a database, authorization rules, media storage, and backend services for persistent posts, real messaging, video streaming, community membership, notifications, account recovery, and email verification. A browser-only app cannot safely provide these features by itself.

Designed by Kitamba Joshua.
