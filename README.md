# inkd-site
Inkd Public Site
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>inkd Support</title>
<style>
  :root { --bg:#ffffff; --text:#24120E; --muted:#6F5F5E; --accent:#1B3A34; --line:#E6E8EB; }
  @media (prefers-color-scheme: dark) {
    :root { --bg:#24120E; --text:#FBEFF3; --muted:#B0A2A3; --accent:#C3975C; --line:#543A25; }
  }
  * { box-sizing: border-box; }
  body { margin:0; background:var(--bg); color:var(--text);
         font:17px/1.6 -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif; }
  main { max-width: 680px; margin: 0 auto; padding: 48px 24px 72px; }
  h1 { font-size: 2rem; line-height: 1.2; margin: 0 0 4px; }
  h2 { font-size: 1.15rem; margin: 36px 0 6px; color: var(--accent); }
  p, li { margin: 0 0 12px; }
  ul { padding-left: 22px; }
  .meta { color: var(--muted); font-size: .95rem; margin-bottom: 28px; }
  a { color: var(--accent); }
  hr { border: 0; border-top: 1px solid var(--line); margin: 36px 0 20px; }
  footer { color: var(--muted); font-size: .9rem; }
</style>
</head>
<body>
<main>
  <h1>inkd</h1>
  <p class="meta">Pen &amp; Ink Log, by Carbonell &amp; Co</p>

  <p>inkd keeps track of your fountain pens and inks: what is inked right now, when each pen last got a clean, and what is in your collection.</p>

  <h2>Support</h2>
  <p>Need help, found a bug, or have an idea? Email <a href="mailto:cj@crbnl.com">cj@crbnl.com</a> and include your iPhone model and iOS version if you can.</p>

  <h2>Common questions</h2>
  <p><strong>Where is my data?</strong> On your device, with an optional backup in your own iCloud. See the <a href="privacy.html">privacy policy</a>.</p>
  <p><strong>How do I move my collection?</strong> Use Export and Import in Settings. inkd works with CSV files.</p>
  <p><strong>Why does a pen show as needing a clean?</strong> Each pen has a cleaning interval. You can change the defaults in Settings.</p>

  <hr>
  <footer><a href="privacy.html">Privacy Policy</a> &middot; Designed and built by Carbonell &amp; Co</footer>
</main>
</body>
</html>
