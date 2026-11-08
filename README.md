# rain-drop-site

Marketing page for **또르르 · RAIN DROP** by LIVEASFILM, served by GitHub Pages from `main`:
<https://liveasfilm.github.io/rain-drop-site/> (`?lang=ko|en|ja`).

It is the App Store Marketing URL and the Google Play contact website, so AdMob finds
`https://liveasfilm.github.io/app-ads.txt` at the host root. The privacy policy is served here too, at
<https://liveasfilm.github.io/rain-drop-site/privacy/> (`?lang=ko|en|ja` starts at that language), the
App Store, Google Play and AdMob consent message privacy policy URL. It is plain HTML with all three
languages, readable without JavaScript, written by `python3 tools/build_site_privacy.py <this checkout>`
in the game repository from the same words as the game server's `privacy.html`
(`tools/build_support_pages.py`). Support and data deletion stay on the game server, because deletion
sends the player's link code to the server's API.

Generated: edit `marketing/site/index.html` in the game repository and run
`python3 tools/build_marketing_site.py <this checkout>` there. Galmuri11 is by Minseo Lee under
the SIL Open Font License 1.1 (`Galmuri-OFL.txt`); `assets/galmuri11.woff2` is a subset.
