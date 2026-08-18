# k9nails.com

The K9 Nails website. Plain HTML — no build step, no framework.
Hosted free on GitHub Pages at <https://www.k9nails.com>.

## How to edit the site

1. Click **`index.html`** in the file list above.
2. Click the **pencil icon** (✏️) in the top right.
3. Change the text between the tags — e.g. the email address, or
   "Thanks for visiting!". Leave the `<tags>` themselves alone.
4. Click **Commit changes...**, then **Commit changes** again.
5. Wait ~1 minute, then reload <https://www.k9nails.com>.

If something looks broken, the **Actions** tab shows whether the last publish
succeeded.

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
