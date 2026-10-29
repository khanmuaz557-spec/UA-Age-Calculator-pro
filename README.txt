ChronoPulse PWA – steps to publish
1. Upload every file in this folder to HTTPS hosting (Netlify, Cloudflare Pages, GitHub Pages).
2. Open the live URL in Chrome and check that "Install app" appears.
3. Go to pwabuilder.com, enter the URL and choose Android > generate package (AAB).
4. Sign with your own key, upload the AAB in Play Console, and add the Digital Asset Links file PWABuilder gives you at /.well-known/assetlinks.json on your site.
