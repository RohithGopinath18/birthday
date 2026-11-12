# Pastel Birthday Surprise Website

A free, mobile-friendly, interactive birthday website. It runs as a static site: no paid service, backend, account, or subscription is required.

## Personalise it
1. Open `index.html` in a text editor.
2. Find `const CONFIG = {` near the bottom.
3. Change:
   - `recipient`: birthday person's name
   - `sender`: your name or signature
   - `reasons`: exactly five short personalised messages
4. Edit the birthday letter in the section with `id="letterText"` if you want a more personal note.
5. Save the file.

## Add photos
The preview includes an **Add your photos** control. For photos to appear for everyone who opens the shared website, put your chosen images in an `images` folder and add them to the HTML gallery before uploading. The browser's local photo picker is only a preview on your device; it does not upload or permanently embed those photos.

For a simple permanent gallery, replace the placeholder gallery in `index.html` with image tags such as:
`<img src="images/photo1.jpg" alt="A favourite memory">`
and keep the surrounding `.photo` card styling.

## Publish free with GitHub Pages
1. Sign in or create a free account at https://github.com/
2. Create a **public** repository, for example `birthday-surprise`.
3. Upload `index.html` (and your `images` folder if you added photos) to the repository's root.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main**, folder **/(root)**, then **Save**.
7. Wait for the published URL shown in the Pages section. It will look like `https://yourusername.github.io/birthday-surprise/`.

## Notes
- The website is static and free to host on GitHub Pages.
- No personal data is sent to a server by this page.
- Do not put private or sensitive photos in a public GitHub repository. A public Pages site can be viewed by anyone with the link, and the repository files themselves are public.
- The page has no copyrighted music. You can add music you own or have permission to use if desired.


## Personalised version
This version is personalised for Shruthoo's 18th birthday, with a handwritten-style letter signed 'Yours roasted Rohithaa'. Review the letter before publishing and make any changes you want.


## Birthday song
The uploaded MP3 is included beside `index.html`. Keep both files in the same folder when uploading to GitHub Pages. Most browsers block autoplay with sound until the visitor interacts with the page. The song therefore starts immediately after the visitor taps **Open your surprise**—there is no separate permission prompt or extra music button required.


Memory Lane includes all 7 photos in the images folder. Keep the images folder beside index.html when uploading the website.
