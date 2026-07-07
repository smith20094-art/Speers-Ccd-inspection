# Noah's Ark Campground — Marketing Site

Single-page static site. No frameworks, no build step — just `index.html`, `styles.css`, and `script.js`.

## Deploying

**Netlify:** drag-and-drop this folder onto app.netlify.com/drop, or connect the repo and set the publish directory to `noahs-ark-campground`.

**GitHub Pages:** Settings → Pages → deploy from branch, set the folder to `/noahs-ark-campground` (or move these files to the repo root / a dedicated repo if you want a cleaner URL).

## Before you launch — replace these placeholders

- **Photos:** every `.placeholder-img` block (hero, about, nearby cards) — swap the `<div>` for an `<img src="images/your-photo.jpg" alt="...">`.
- **Contact info:** phone number and email appear in the sticky call bar, header, and Contact section — search for `[(250) 555-1234]` and `[info@noahsarkcampground.ca]`.
- **Address & map:** update the address text and the map `<iframe src="...">` query in the Contact section.
- **Facts:** number of sites, river/creek name, years in business (`about` section).
- **Amenities:** the amenities grid lists everything commonly offered — delete what you don't have, add what's missing.
- **Rates table:** all dollar figures are placeholders.
- **Rules:** check-in/out times, quiet hours, office hours.
- **Section 5 (Things To Do Nearby)** is a stub by design — full content comes in a later pass.

## Notes

- Mobile-first; a sticky "Call Now" bar stays on screen on phones (hidden on desktop, where the phone number lives in the header instead).
- No external fonts, images, or JS libraries are loaded — the page works offline once cached, which matters for visitors with weak highway signal.
