# Rabbit Speaks site

The GitHub Pages user site that hosts every Rabbit Speaks game's privacy policy and the shared `app-ads.txt`.

Push these files to the root of a public repo named `<username>.github.io`, then turn on Settings › Pages (deploy from `main`).

## Before publishing, replace the placeholders

| Placeholder | Where | Replace with |
|---|---|---|
| `pub-XXXXXXXXXXXXXXXX` | `app-ads.txt` | Your AdMob publisher ID (AdMob › Settings › Account information) |
| `[YOUR-EMAIL]` | `index.html`, `dunderball/privacy-policy.html` | The public contact email for your games |
| `[EFFECTIVE-DATE]` | `dunderball/privacy-policy.html` | The date you publish the policy |

## URLs

- **Website** (each game's Play listing): `https://<username>.github.io`
- **Dunderball privacy policy:** `https://<username>.github.io/dunderball/privacy-policy.html`
- **app-ads.txt:** `https://<username>.github.io/app-ads.txt`

## Adding a game

Copy `dunderball/` to `<game>/`, edit the policy for that game's data use, and add a card to `index.html`. `app-ads.txt` stays as it is while the game uses the same AdMob account.
