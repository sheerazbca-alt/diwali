Happy Diwali page - folder guide
================================
index.html            the page (everything draws on a canvas)
bg.webp / bg.mp4      the design: still image shows instantly, video plays over it
favicon.*, icon-512   diya favicon (browser tab) and app icons
og-card.png           the big LinkedIn / Facebook / X card image (1200x627)

To show the BIG CARD when you post on LinkedIn
1. Upload this whole folder to any web host (Netlify Drop, GitHub Pages, Vercel, your company site).
2. Open index.html in a text editor and replace every  YOUR-DOMAIN  with your real address,
   for example  diwali.example.com  (about 7 places; Find & Replace does it in one go).
   On Mac/Linux:  sed -i '' 's/YOUR-DOMAIN/diwali.example.com/g' index.html
3. Paste your page link into LinkedIn Post Inspector (linkedin.com/post-inspector) once
   so LinkedIn refreshes its preview, then post.

Notes
- Music is generated in the browser (no audio file). Browsers allow sound only after the first
  click / tap / key press, so it starts the instant the visitor does any of those.
- The page opens as a calm night (stars, moon, dimmed lamp) with a small "Tap or click to celebrate Diwali" line.
  The first tap/click starts the music and brings up the light and fireworks. If the browser already allows sound, this happens by itself.
- Speaker button, bottom-left, turns all sound off/on.
