# n00bin.github.io

The root of the n00bin GitHub Pages address. It holds one thing: `.well-known/assetlinks.json`, which tells
Android that the Wordami app (`com.n00bin.wordami`) belongs to this address, so the app opens
https://n00bin.github.io/gintaras/ full-screen with no browser bar.

The fingerprints in that file are public by design. When Google Play signs the app with its own key, that key's
SHA-256 fingerprint (Play Console > Test and release > App integrity) must be added to the list.

`.nojekyll` is needed, or GitHub Pages skips the `.well-known` folder.

The app itself lives at https://n00bin.github.io/gintaras/.
