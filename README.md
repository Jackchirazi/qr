# QR redirect

The QR code printed on my merch points at **https://jackchirazi.github.io/qr/** — permanently.
This repo decides where that QR actually sends people.

## To change where the QR points

1. Open [`index.html`](index.html) on github.com (works from a phone).
2. Tap the pencil (edit) icon.
3. Find the marked line near the top and change only the URL after `url=`:

   ```html
   <meta http-equiv="refresh" content="0; url=https://www.instagram.com/jack_chiraz1/">
   ```

4. Commit. The change is live within a minute or two.

That's it. Never change the QR code itself — only this file.

## Adding a second QR later

To give the hat its own destination, add a folder (e.g. `hat/`) with its own
`index.html` copy, and print a QR for `https://jackchirazi.github.io/qr/hat/`.
