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
| `assets/logo.png` | The logo. |
| `assets/favicon.png` | The little icon in the browser tab. |

## Hosting

- GitHub Pages, deployed from the `main` branch on every push.
- Currently served at <https://k9nails.github.io>.

### Not yet switched over to k9nails.com

`www.k9nails.com` still points at the old Squarespace site. To cut over:

1. Add a file named `CNAME` at the top level of this repo containing exactly:
   `www.k9nails.com`
2. At the domain registrar, point `www` (CNAME) at `k9nails.github.io`, and
   point the bare domain (A records) at `185.199.108.153`, `185.199.109.153`,
   `185.199.110.153`, `185.199.111.153`.
3. Once that resolves, turn on **Enforce HTTPS** in Settings -> Pages.
