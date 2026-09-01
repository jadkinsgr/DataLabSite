# Data Lab - Website (draft)

Static site for Data Lab (formerly Midwest Dataworks), built as a single `index.html` (no build step). Loads GSAP + ScrollTrigger + Lenis from CDN for scroll animation and smooth scrolling; the page degrades gracefully to a plain fade-in if those CDNs are unreachable.

**Live preview:** https://jadkinsgr.github.io/MidwestDataworksSite/
**Production domain:** https://midatalab.net/ (Namecheap DNS pointed at GitHub Pages via the `CNAME` file; `www.midatalab.net` redirects to the apex)

## Status: draft

This is being iterated on via GitHub Pages, now pointed at the `midatalab.net` production domain (previously served by Wix under the old `midwestdataworks.com` name). Once the design/content is approved, the remaining step is to:

1. Downgrade/cancel the Wix Premium plan once the cutover is confirmed working.

## Local preview

Just open `index.html` in a browser - no build tooling required.
