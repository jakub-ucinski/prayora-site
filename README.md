# prayora-site

The public website for Prayora: the landing page, privacy policy, terms and support pages.

Plain HTML, no build step. GitHub Pages serves it from the `main` branch.

- `index.html`: landing page. The waitlist form posts to the `join_waitlist` function in the Prayora Supabase project, using its public key.
- `privacy.html`, `terms.html`, `support.html`: pages linked from the footer and the App Store listing.
