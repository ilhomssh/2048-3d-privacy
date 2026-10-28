# Privacy policy page for GitHub Pages

This folder contains a standalone policy page in all 19 game languages. Its
language selector is at the upper right. The shared policy text is maintained
in `maintenance/privacy-policy-locales.cjs` and is used both here and in the
game's About page. After editing it or the developer/contact details, regenerate
the page with `node maintenance/build-public-privacy.cjs` and reinstall the
in-game page with `node maintenance/install-home-about.cjs`.

The policy describes local game saves, AdMob/UMP data practices, child-directed
non-personalized ads, rewarded ads and Game Over continues, disabled coin-pack
purchases, image sharing, external links, retention/deletion, and privacy
requests. Keep the Google Play Data safety form consistent with the actual SDKs
and release configuration.

The policy reflects the current app configuration as of October 13, 2026.
After regeneration, commit and push `index.html` to the GitHub Pages repository
to publish updates at the existing policy URL. This local file alone does not
publish changes. Review it whenever SDKs, permissions, ads, purchases or data
flows change.
