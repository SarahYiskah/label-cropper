# Label Cropper (PWA)

Crop return-label PDFs to your thermal label size, then print or share them.

## Deploy (any static host over HTTPS)

There is no build step. Host the files in this folder as they are.

- **Vercel:** `cd label-cropper && npx vercel --prod`
- **Netlify (no account setup):** drag the folder onto https://app.netlify.com/drop
- **GitHub Pages:** push the folder to a repo and turn on Pages

## Install

- **iPhone:** open the URL in Safari → Share → Add to Home Screen
- **Android:** open the URL in Chrome → menu → Install app
- **Desktop Chrome/Edge:** use the install icon in the address bar

## Use

1. Open a PDF, or a screenshot or photo of the label (handy when the PDF is a long page and hard to crop). On Android you can also share a PDF or image from Gmail or Files straight to "Label Cropper".
2. Adjust the box. It starts around the content and keeps your label's shape. A long page shows at full width so you can scroll to the label; tap the label and the box snaps onto it.
3. Tap **Print label**. If you print from a phone and the job doesn't reach the printer, tap **Share / save as PDF** and send the file to the printer's own app. The PDF is already the exact label size.
4. Save the box position as a preset per company (Amazon, UPS…) so the next label takes one tap.

The app works offline after the first visit. Presets are stored on each device.
