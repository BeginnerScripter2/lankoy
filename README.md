# lankoy
Lance + Pamela


Tech Stack

HTML5 / CSS3 / Vanilla JS — no build tools, no frameworks
<model-viewer> by Google — 3D GLB rendering
CSS perspective + rotateX/Y — 3D depth on cards and the decorative ring
Canvas API — ambient particles and the YES burst effect
IntersectionObserver — scroll-triggered reveal animations
Glassmorphism — backdrop-filter: blur() on the letter card
Playfair Display + Cormorant Garamond — via Google Fonts


 Customizing the Text
All letter content is plain HTML inside letter.html. Search for these sections:
What to changeWhere to find itOpening quoteclass="entry-quote"Page headlineclass="opener-h"Floating thoughtsclass="thought-line" (3 of them)The letter bodyid="letterBody"Final questionclass="final-h"YES response messageid="resp-yes""I Need Time" messageid="resp-wait"Secret messageid="secret"Footer<footer>


✦ Browser Support
BrowserSupportChrome 90+✅ FullFirefox 90+✅ FullSafari 15+✅ FullEdge 90+✅ FullMobile (iOS/Android)✅ Responsive — 3D transforms disabled on small screens

✦ File Size
~10 MB — almost entirely the embedded 3D bouquet model. The HTML, CSS, and JS are under 20 KB.
