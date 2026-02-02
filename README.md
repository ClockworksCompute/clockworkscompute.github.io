# Clockworks Compute Website

This repo is intended to be served via GitHub Pages.

## Pages
- `/` : homepage
- `/manifesto/` : manifesto

## Custom domain
If/when you want to serve this from `clockworks-compute.com`, add a `CNAME` file at repo root with:

```
clockworks-compute.com
```

Then set DNS at Namecheap:
- A records for apex (`@`) to GitHub Pages IPs
- CNAME for `www` to `clockworkscompute.github.io`

(We can automate DNS via a Namecheap CLI once Namecheap API access is configured.)
