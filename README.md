# k9nails.com

The K9 Nails website. Plain HTML — no build step, no framework.
Hosted free on GitHub Pages at <https://www.k9nails.com>.

## How to update the upcoming dates

1. Click **`index.html`** in the file list above.
2. Click the **pencil icon** (✏️) in the top right to edit.
3. Find the `UPCOMING DATES` section. Each date is one line that looks like:

   ```html
   <li><strong>Sat Nov 8th, 11am&ndash;3pm</strong> &mdash; Highway 20 Feed, Fort Bragg, CA</li>
   ```

   - To **add** a date: copy an existing line, paste it, and change the text.
   - To **remove** a date: delete the whole line.
   - `&ndash;` makes the dash in a time range (12–2pm). `&mdash;` makes the longer dash before the location.
4. Click **Commit changes...**, then **Commit changes** again.
5. Wait ~1 minute, then reload <https://www.k9nails.com>. Done.

If something looks broken, the **Actions** tab shows whether the last publish succeeded.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The entire website. |
| `CNAME` | Tells GitHub the site lives at `www.k9nails.com`. **Do not delete** — the custom domain stops working without it. |
| `assets/logo.png` | The logo. |
| `assets/favicon.png` | The little icon in the browser tab. |

## Hosting

- GitHub Pages, deployed from the `main` branch on every push.
- Custom domain `www.k9nails.com`, HTTPS via GitHub's free certificate.
- DNS is managed at the domain registrar; `www` is a CNAME to the GitHub Pages host.
