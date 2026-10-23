# privacy.onova.tech

Privacy policies for Onova Tech apps, served by GitHub Pages from `main` at
https://privacy.onova.tech.

| Path | Purpose |
|---|---|
| `pocket-tools/` | Pocket Tools privacy policy (English); `pt-br/` and `es/` hold the translations. Keep all three in sync. |
| `favicon.svg`, `favicon.ico`, `apple-touch-icon.png` | The Onova Tech logo as the site icon. The SVG is the source; the ICO (16, 32 and 48 px) and the 180 px PNG are drawn from it. |
| `app-ads.txt` | Authorized ad sellers for Onova Tech apps (AdMob, publisher `pub-3506335232902582`). |
| `CNAME` | Custom domain for GitHub Pages. |
| `.nojekyll` | Serves the files as they are, without Jekyll. |

The pages load nothing from third parties (no fonts, scripts or analytics).

AdMob looks for `app-ads.txt` at the root of the developer website named in each app's Play
listing, checking that host and then the domain above it. Each listing's developer website must
therefore be `https://privacy.onova.tech`. If the website later moves to `https://onova.tech`, the
file has to move to the root of that site.
