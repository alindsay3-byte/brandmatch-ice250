# Brandmatch | ICE-250: The Future of Music

Brandmatch is a prototype for an AI-assisted visual discovery and artist-branding tool. Independent artists swipe through visual references, save styles to a moodboard, and generate a starter creative direction for their logos, release artwork, posters, and social media.

## Current prototype features

- Swipe-style discovery with like/pass buttons
- Keyboard controls: left arrow to pass, right arrow to save
- Touch swipe support on mobile
- Saved moodboard / shortlist
- Undo last swipe
- Starter brand direction based on saved references
- Downloadable text brand brief
- Responsive layout for desktop and mobile

## Project thesis (working draft)

By 2028, AI-assisted creative discovery tools will make professional-level brand planning more accessible to independent musicians, helping artists communicate a clearer visual identity without needing to hire a creative director at the beginning of their careers.

This is a hypothesis to investigate and test, not a proven outcome. Add sourced signals and user-testing evidence before submitting the class project.

## Run locally

This prototype is a static website. Open `index.html` in a browser, or serve the folder with a local static web server.

## Use with GitHub

1. Create a new repository on GitHub, for example `brandmatch-ice250`.
2. Upload `index.html`, `README.md`, and `.gitignore` to the repository.
3. Commit the files to the main branch.
4. Optional: enable GitHub Pages in the repository settings if you want a public static demo URL.

## Use with Replit

1. Import the GitHub repository into Replit, or upload this project folder.
2. Open `index.html` and use Replit's preview/webview for the prototype.
3. Make changes in small increments and test each change.
4. Commit/push meaningful updates back to GitHub so the repository tracks your build progress.

Replit's UI and import labels may change over time. If you cannot find the GitHub import option, create a static HTML/CSS/JS Replit project and upload `index.html`.

## ICE-250 next steps

1. Define the target artist persona and job to be done.
2. Gather evidence for the future thesis and map at least three course innovation lenses.
3. Test the current prototype with independent artists; record what they do and what confuses them.
4. Improve the recommendation logic. The current version summarizes tags from saved styles; it does not use a trained AI model.
5. Add artist profile inputs, accessible font/color guidance, and rights-conscious image sourcing.
6. Document changes, user feedback, risks, and the next experiment in weekly build logs.

## Important limitations

- Saved preferences are kept only in the current browser session; there is no account or cloud database.
- The recommendation summary is rule-based, not a personalized machine-learning model.
- Inspiration images load from external Unsplash URLs and need an internet connection.
- The current prototype does not create finished logos or posters. It produces a starter creative brief.
- Use only images and fonts with appropriate permissions in any public or commercial release.
