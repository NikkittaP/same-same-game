# Same Same! — website

Public pages for the Android game **Same Same!** (`com.nikitapetrovapps.samesame`),
served by GitHub Pages from the `main` branch, root folder.

- `index.html` — landing page; the game is live on Google Play
- `privacy/index.html` — privacy policy; this is the URL given to Google Play Console:
  `https://nikkittap.github.io/same-same-game/privacy/`

The source of truth for the policy is `privacy/index.html` here. The game
repository keeps an exact copy in `docs/privacy_policy.html` and a Russian
rendering in `docs/privacy_policy.md`; when the policy changes, edit it here
first, bump "Last updated", then sync both files there. Before any change
that touches the network, data or purchases, check it against the manifest
of the built AAB.
