# DarkSlayer995 — Personal portfolio

A responsive portfolio for an Anticheat Developer, Detection Analyst, and Minecraft Security Specialist. Built with semantic HTML, CSS, and vanilla JavaScript. No build step, backend, database, API keys, analytics, remote fonts, or runtime dependencies.

## Project structure

```text
index.html          Content, navigation, and SEO metadata
styles.css          Responsive layouts, visual effects, reduced-motion support
script.js           Mobile navigation, active section, current footer year
assets/favicon.svg  Original shield favicon
README.md           Preview, deployment, and maintenance instructions
```

## Preview locally

Open `index.html` directly in a modern browser. Content and links also work with JavaScript disabled.

For an HTTP preview, use an existing static server such as VS Code Live Server, or run this from the repository root if Python is installed:

```sh
python -m http.server 8000
```

Open `http://localhost:8000`. Stop the server with Ctrl+C.

## Publish to GitHub Pages

The repository is already configured to deploy from **main / root**. Commit the files and push them to `main`; GitHub Pages will publish at [darkslayer995.github.io](https://darkslayer995.github.io/). No configuration changes or build commands are needed. Check the repository's Pages deployment or Actions status after pushing.

```sh
git add index.html styles.css script.js assets/favicon.svg README.md
git commit -m "Build personal security portfolio"
git push origin main
```

If working on another branch, merge the reviewed changes into `main` first. This implementation does not itself commit or push changes.

## Customize content

- Edit text and cards directly in `index.html`.
- GitHub links use the supplied public identity, `DarkSlayer995`. Each experience card also links to its supplied organization website or Discord invite. Landkreis Rheintal is identified as a FiveM role.
- The contact section lists the approved public business email, Discord username, and Discord user ID. The email uses a `mailto:` link. Keep these details up to date and publish only contact information you intend to share.
- Projects are general work overviews. Add real repository or download links only when they are ready to share.
- Experience descriptions are broad role summaries based on the supplied titles. Review them for personal accuracy before publishing. No dates, metrics, endorsements, or private detection methods are included.
- Change colors and type stacks using the variables at the start of `styles.css`.
- Keep canonical and Open Graph URLs aligned if the domain changes.
- Decorative artwork and the favicon are original SVG/CSS. Organization badges are text treatments, not official logos.

## Accessibility and privacy

Includes semantic headings, a skip link, visible keyboard focus, accessible navigation state, Escape-to-close mobile navigation, and reduced-motion support. Animations are decorative. External website and Discord invite links announce that they open a new tab. No tracking scripts, embedded third-party resources, contact forms, cookies, or client-side storage.

## QA after edits

1. Check navigation and call-to-action links.
2. Review at narrow mobile, tablet, and desktop widths; check horizontal overflow.
3. Test mobile navigation with keyboard and pointer, including Escape.
4. Enable reduced motion and disable JavaScript to check fallbacks.
5. Check the browser console and Network panel for errors and missing assets.
6. Confirm all public text and contact details are accurate and intentional.
