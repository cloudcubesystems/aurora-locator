# Aurora Locator website (GitHub Pages)

Static files for the public site: the home page and the privacy policy (Play and the App Store
require one). Later this site will also host the remote `config.json`.

The app repo is private, and GitHub Pages on a private repo needs a paid plan. So publish this
folder from a **public** repo, `cloudcubesystems/aurora-locator`: Settings → Pages → Deploy from
branch `main`, folder `/ (root)`. The site's address is then
https://cloudcubesystems.github.io/aurora-locator/ and the privacy policy is
https://cloudcubesystems.github.io/aurora-locator/privacy.html. That address is the
`PRIVACY_POLICY_URL` in `src/config/app.ts`.
