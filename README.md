# NEXTWAVE — Interior Design & Architecture Website

A multi-page React + Vite website starter for NEXTWAVE. It includes a cinematic homepage, About, Transformation, Living Room, Kitchen, Bedroom, Projects, Services and Contact pages, responsive navigation, GSAP scroll reveals and Lenis smooth scrolling.

## No paid services or backend required

This is a static frontend website. It does **not** use Supabase, Firebase, a paid API, or a paid hosting service. The contact form opens the visitor's email application using a `mailto:` link. It does not store enquiries in a database. Replace `hello@nextwave.studio` in `src/main.jsx` with the real business email before publishing.

Some demo room photographs use remote Unsplash image URLs and therefore require an internet connection. The main homepage hero image is included locally in `public/images/nextwave-hero.png`.

## 1. Open in Visual Studio Code

1. Install Node.js LTS from https://nodejs.org/.
2. Extract this ZIP file.
3. Open Visual Studio Code.
4. Select **File → Open Folder** and choose the extracted `nextwave-website` folder.
5. Open **Terminal → New Terminal**.
6. Run:

```bash
npm install
npm run dev
```

7. Open the local address printed in the terminal (usually `http://localhost:5173`).

To test the production build locally:

```bash
npm run build
npm run preview
```

## 2. Publish free on GitHub Pages

1. Sign in to https://github.com/ and create a **new public repository** named `nextwave-website`.
2. In VS Code, open the extracted project folder.
3. In the Source Control panel, choose **Initialize Repository**.
4. Stage all project files, commit with a message such as `Initial NEXTWAVE website`, then choose **Publish Branch** / **Publish to GitHub** and select the repository you created.
   - Alternatively, upload the extracted project files through GitHub's **Add file → Upload files** page. Keep the `.github/workflows/deploy.yml` file and its folder structure.
5. On GitHub, open **Settings → Pages**.
6. Under **Build and deployment → Source**, select **GitHub Actions**.
7. Open the repository's **Actions** tab and wait for the `Deploy NEXTWAVE to GitHub Pages` workflow to finish successfully.
8. Your live site will be available at:

   `https://YOUR-GITHUB-USERNAME.github.io/nextwave-website/`

The included workflow builds the site and publishes the `dist` folder automatically whenever you push changes to the `main` branch. The website can take a few minutes to appear after the first deployment.

## Before sharing with clients

- Replace the demo email address in `src/main.jsx` with the real business email.
- Add the real WhatsApp number if you want a WhatsApp contact link.
- Replace demo project imagery and copy with approved brand content.
- Add the correct studio address and map embed if required.
- Test the contact form, mobile menu, all page links and images.
- The project gallery and contact form are frontend-only demonstrations; there is no admin dashboard or stored enquiry database in this no-backend version.

## Technology

React, Vite, React Router (hash routing for static hosting), GSAP + ScrollTrigger, Lenis, Lucide React and Google Fonts.


## Latest design updates

- Every room page now includes practical explanations of the room's purpose, planning priorities and design specialties:
  - Living room: seating, zoning, lighting, material and personality.
  - Kitchen: work triangle, storage, durable finishes, task lighting and ventilation.
  - Bedroom: restful atmosphere, layered lighting, storage and comfort.
- Added a five-person sample studio team to the About page, with placeholder names, roles, bios and portrait images. Replace all sample profiles with the real team before launch.
- Added a working dark/light theme switch in the desktop header and mobile menu. The choice is saved in the visitor's browser.
- Added scroll-linked parallax movement to page hero images, feature imagery, project imagery and team portraits, alongside the existing smooth scrolling and reveal animations.
- No Supabase, Firebase or other backend is used.

## Notes before production

The five team portraits and some room/project images load from Unsplash and need an internet connection. The names and positions are fictional placeholders. This remains a static site: no admin CMS or database-backed enquiry storage is included. The contact form uses the visitor's email app.


## Latest visual polish (November 2026)

- Increased NEXTWAVE logo and navigation contrast with a dark translucent logo plate and clearer white / champagne lettering over photography.
- Improved menu, header action and small label visibility.
- Restyled the homepage "Scroll to Explore" link as a high-contrast navigation cue anchored to the left margin.
- Added room-specific descriptions below the Living Room, Kitchen and Bedroom cards.
- Added descriptive captions below the homepage feature and selected project image, page hero photographs, and every portfolio photograph.
- Added scroll-triggered image reveal / pop-up effects and staggered card entrances while retaining the existing smooth scrolling and parallax movement.
- Improved the hero supporting text panel to prevent it blending into bright photography.


## Final contrast and placement update

- Increased the top-right location line size, weight, contrast and legibility.
- Moved the homepage Scroll to Explore navigation cue to the bottom-right margin.
- Set photographic hero and page headings to champagne-gold for reliable contrast.
- Corrected room, project, feature and page-image caption colours for dark and light themes.
- Increased descriptive text weight, size and line-height across the site.


## Brand and contrast refinement
- Updated NEXTWAVE logo colors and subtle logo plate for dark and light themes.
- Made outline CTA borders and fills adapt to the active theme.
- Applied champagne-gold typography to all non-homepage editorial page headings, leaving the homepage hero treatment intact.
- Increased micro-label size and weight with theme-aware colors.
- Reduced the homepage Scroll to Explore cue and anchored it at the lower-right edge, below the hero statistics.


## Brand refinement — amethyst palette
- Updated the logo plate, logo lettering and navigation controls with a theme-aware ivory / plum / lilac palette.
- Applied amethyst and mauve display headings to the inner pages only; the homepage hero heading remains unchanged.
- Improved contrast and weight for inner-page descriptions, labels and section headings.
- Restyled contact form fields, map placeholder, enquiry button and outline CTAs for both Light Mode and Dark Mode.
- Kept the existing React components, routes, page copy, image assets, animations and theme toggle in place.
