# Mathematics Tuition site

Static site. No build step, no dependencies.

## Files
- `index.html` - the whole page
- `assets/` - photograph, Imperial crest, favicon

## Publishing with GitHub Pages
1. Create a repository and push these files to the **root** of the default branch.
2. Repository **Settings** > **Pages**.
3. Under **Build and deployment**, set Source to **Deploy from a branch**, branch to your default branch, folder to **/ (root)**.
4. Save. The site appears at `https://<username>.github.io/<repository>/` within a minute or two.

## Preview locally
    python3 -m http.server 8000

Then open http://localhost:8000

## Before it goes live
- The enquiry form opens the visitor's email application via a `mailto:` link. That fails for
  anyone using webmail in a browser. For real enquiries, switch it to a form service such as
  Formspree or Netlify Forms.
- The Imperial College crest is a registered trademark. Confirm with Imperial that your use is
  acceptable, or remove it and keep the course named in text only.
- Three review slots in the Reviews section are placeholders. Replace them with real reviews
  you have permission to quote, or delete that section.
