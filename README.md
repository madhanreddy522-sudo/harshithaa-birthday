# Harshithaa Birthday Website (Free)

A mobile-friendly interactive birthday microsite made with plain HTML, CSS, and JavaScript. No frameworks, paid services, API keys, or custom domain required.

## Preview locally
1. Extract the ZIP.
2. Open `index.html` in a browser. (Some browsers restrict local audio; that's okay.)
3. To add personal pictures, put three image files in the same folder and name them exactly:
   - `photo1.jpg`
   - `photo2.jpg`
   - `photo3.jpg`
   The website automatically replaces the photo placeholders when those files are present.
4. Optional: add a legally usable MP3 named `romantic-music.mp3` to the same folder. Tap **Music off** to start it. Browsers require a tap before music can play.

## Personalize the page
Open `index.html` in any text editor:
- Change the birthday name in the welcome and final headings if needed.
- Edit the letter inside the element with `id="letterText"`.
- Edit the captions in the `<figcaption>` elements.
- Edit the five reason messages in the JavaScript `lines` array.
- Keep personal photos private if you don't want them publicly accessible. GitHub Pages sites in public repositories are public.

## Free romantic music
Do not download copyrighted songs from unofficial sources. Choose a track whose license permits reuse and public hosting (for example, a track with a suitable license from Pixabay Music: https://pixabay.com/music/). Check the specific track's license/terms, download the MP3, rename it `romantic-music.mp3`, and place it next to `index.html`. The site works without music too.

## Publish with GitHub Pages (free)
1. Create/sign in to a GitHub account at https://github.com/.
2. Click **New repository**. Name it `harshithaa-birthday`. Choose **Public** (GitHub Pages on the free plan generally requires a public repository). Create the repository.
3. On the repository page, choose **Add file → Upload files**.
4. Upload `index.html`, your chosen `photo1.jpg`, `photo2.jpg`, `photo3.jpg`, and optionally `romantic-music.mp3`. Do not upload photos/music you don't have permission to share.
5. Click **Commit changes**.
6. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**. Select branch `main` and folder `/ (root)`, then click **Save**.
7. Wait a few minutes and refresh the Pages section. GitHub will show the published URL, usually `https://YOUR-USERNAME.github.io/harshithaa-birthday/`.
8. Open the URL on your phone to test. Send the link to Harshithaa when you're ready.

## Notes
- This is a static website; it does not collect or upload form data.
- Any uploaded photo/music in a public repository can be viewed/downloaded by visitors. Use photos you are comfortable sharing.
- Music playback is user-initiated because mobile browsers commonly block autoplay.
- If the site doesn't update immediately, wait a few minutes and refresh the page.
