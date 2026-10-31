# Sign PDF

Sign any PDF for free. No account, no upload, no monthly bill.

**[Try it in your browser](https://Sayemnyc.github.io/sign-pdf/)**

## What it does

A DocuSign-style PDF signer in a single web page.

- Open a PDF by dropping it on the page or picking it.
- Create a signature by drawing it, typing it in a handwriting font, or uploading an image.
- Add your signature, initials, today's date, or a text box anywhere on any page.
- Drag, resize, or delete anything you placed.
- Download the result as `yourfile-signed.pdf`.

## Privacy

Your PDF never leaves your computer. There is no server, no account, and no tracking. Your saved signature and initials stay in your browser's local storage until you click "Forget my signature".

## Use it

Open https://Sayemnyc.github.io/sign-pdf/, or download `index.html` and open it in any modern browser. There is nothing to install and no build step.

## How it works

pdf.js renders each page of your PDF onto a canvas in the browser. Everything you place is stored in PDF points, so it lands in the same spot no matter how large the page is shown. When you download, pdf-lib writes your signature images and text into a copy of the original file.

## Note

This adds a visual signature. It is not a certified e-signature with an audit trail.

## License

MIT. See [LICENSE](LICENSE).
