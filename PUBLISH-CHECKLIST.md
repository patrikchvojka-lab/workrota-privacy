# WorkRota privacy-policy publication checklist

The local `index.html` now contains the Wear OS/Data Layer disclosure in Czech,
English, German, Polish and Slovak, with an effective date of 16 August 2026.

Before publishing:

1. Review the local diff and validate the HTML.
2. Confirm each language section describes the seven-shift allow-list, transport
   metadata, encrypted Wear OS Data Layer, possible end-to-end encrypted Google
   relay, private storage and the disable/reset payload.
3. Commit and push only with explicit owner authorization.
4. Wait for GitHub Pages deployment, then verify the public URL and every language
   anchor in a private/incognito window.
5. Reopen the Play Data safety and store-listing preview and confirm the public
   privacy link resolves to the updated text.

Do not mark the release privacy gate complete based only on this local file.
