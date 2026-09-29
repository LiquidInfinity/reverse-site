# Reverse public site

Static GitHub Pages site for `usereverse.io`. This is separate from
the non-Git ReverseNext app project. It contains only public HTML and CSS;
there are no keys, user records, or build artifacts.

`index.html`, `privacy.html`, and `terms.html` describe the current development
build, not planned data collection. Update the privacy page
it when capture, AI chat storage, or Supabase account syncing becomes active.

The site is published from a dedicated GitHub repository. Its Pages custom
domain is `usereverse.io`; the apex A records and `www` CNAME point to GitHub
Pages. Clerk uses a separate subdomain. Google OAuth Branding links to these
public pages.
