How to use this patch

1) Upload files to your portfolio repo (srikanthmadabhushi.github.io):
   - projects.html
   - index.html.sample  (optional; merge the nav into your existing index.html)
   - assets/itsm.svg
   - assets/itom.svg
   - assets/generic.svg

2) Link from your homepage (index.html):
   <a href="/projects.html">Projects</a>

3) Optional custom thumbnails:
   In projects.html, add `img:'/assets/your-image.svg'` (or .png) to any project entry.
   If no `img` is provided, the page auto-fetches an image from the repo README or uses a GitHub preview, with a clean SVG fallback.

4) Deep links:
   /projects.html?cat=ITSM (or ITOM, GRC, CSM, HRSD)

5) Remove 'AI + ServiceNow Gallery':
   Open index.html and delete that section. If you need help, paste your index.html and I will remove it for you.
