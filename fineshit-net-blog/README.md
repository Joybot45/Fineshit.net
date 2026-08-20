# fineshit.net

Static blog, black background / red theme, hosted on GitHub Pages.
Home page lists posts as a grid of cards (thumbnail + title + short summary), like a video site.

## Adding a new post
1. Add a thumbnail image to `images/` (16:9 works best, e.g. 640x360). Replace `placeholder-thumb.jpg` with a real image, or add a new one per post.
2. Copy `posts/first-post.html` to a new file in `posts/` (e.g. `posts/my-review.html`).
3. Edit the title, date, hero image path, and body text in that file.
4. In `index.html`, copy one `<li>...</li>` card block, and update:
   - the `href` (link to your new post file)
   - the `src` (your new thumbnail)
   - the title
   - the short summary text (this is your "what I thought of it")
   - the date
5. Commit and push (or upload via GitHub's web UI) — GitHub Pages redeploys automatically in a minute or two.

## Domain
The `CNAME` file tells GitHub Pages to serve this site at `fineshit.net`.
DNS for the domain is configured at Namecheap.
