AI Affiliate Creator
====================

This is a self-contained mobile-first PWA/web app.

Run:
1. Unzip.
2. Open index.html in a modern browser.
3. On Android Chrome, use "Add to Home screen" to install it as a PWA.

Core workflow:
Product URL + Affiliate/Profit URL -> Generate -> product metadata + verified fields + creative preview + reel storyboard + platform copy + export.

Important limitation:
Browser-only apps cannot reliably bypass CORS, login walls, anti-bot systems, or retailer restrictions. When automatic extraction is blocked, use the Manual fallback with verified product details. The app deliberately does not invent prices, ratings, warranties, reviews, or specifications.

For production:
Connect a backend/API layer for permitted product extraction, image processing, LLM copy generation, image/video generation, storage, and official social publishing APIs. Keep all API secrets server-side.
