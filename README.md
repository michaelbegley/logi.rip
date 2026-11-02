# logi.rip

The one-page site for RIPLOGI: the logo, a light/dark switch and an email sign-up.

- **The page** is `index.html`. Everything is in that one file, except the sounds.
- **The intro** (the logo falls and slams, RIPLOGI slides out, the page rises in) plays after the visitor taps Enter Site, because browsers only allow sound after a tap. Visitors who have reduced motion turned on skip it.
- **Sounds** are in `audio/`: `impact.mp3` (the slam), `door.mp3` (the jail door) and `submerged.mp3` (the music, which loops). The music stops when the visitor mutes it or leaves the page.
- **Sign-ups** go to Kit (kit.com), not to this repo.
- **Hosting** is GitHub Pages from the `main` branch. The `CNAME` file holds the custom domain.
- **To change the page**, edit `index.html` on GitHub (pencil icon) and commit. It goes live in about a minute.
- The hand in the logo and the footer's Instagram icon are from Phosphor Icons (MIT licence, see `LICENSE-phosphor-hand.txt`).
