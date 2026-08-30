# Data Lab - Website (draft)

Static site for Data Lab (formerly Midwest Dataworks), built as a single `index.html` (no build step). Loads GSAP + ScrollTrigger + Lenis from CDN for scroll animation and smooth scrolling; the page degrades gracefully to a plain fade-in if those CDNs are unreachable.

**Live preview:** https://jadkinsgr.github.io/MidwestDataworksSite/

## Status: draft

This is being iterated on via GitHub Pages at the default `github.io` URL above, **not** yet pointed at a live production domain (which is currently still served by Wix under the old `midwestdataworks.com` name). The `og:url` meta tag currently points at a placeholder `www.thedatalab.com` - update it once the real domain for Data Lab is finalized. Once the design/content is approved, the plan is to:

1. Enable GitHub Pages on this repo (`main` branch, root).
2. Review/iterate at the `github.io` URL.
3. Register/point the new Data Lab domain, add a `CNAME` file, and update DNS records to point at GitHub Pages.
4. Downgrade/cancel the Wix Premium plan once the cutover is confirmed working.

## Local preview

Just open `index.html` in a browser - no build tooling required.
