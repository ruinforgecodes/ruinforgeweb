# Publish RuinForge on a free web address

This folder contains only the public website and its 26.3 modpack downloads. It is ready for GitHub Pages, which provides a free `github.io` address for public repositories.

## Publish it

1. Sign in to your GitHub account (or create a free account).
2. Create a **public** repository. For the shortest address, name it exactly `<your-github-username>.github.io`. The resulting address will be `https://<your-github-username>.github.io/`.
3. Upload the contents of this folder to the top level of that repository, including the hidden `.github` folder.
4. Open the repository's **Settings → Pages**. Under **Build and deployment**, choose **GitHub Actions** as the source.
5. Open **Actions** and wait for “Publish RuinForge website” to finish. GitHub will show the live link in the Pages settings.

You do not need to buy a domain or enter payment details for this address. Anyone can view a GitHub Pages site, so the repository and its website files are public.

## Current release status

The site offers RuinForge profile 0.3.2 for Minecraft Java 26.3, including the custom RuinForge main menu and Ember UI pack. The standalone Windows launcher installer exists, but Microsoft sign-in is not configured yet, so this page does not offer that installer as a ready-to-use public download.
