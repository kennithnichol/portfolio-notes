# Dev Log

A running chronicle of what I'm working on, learning, and deciding as I build my portfolio and site.

## 2025-06-22 - Kickoff

- Created this dev notes repo to document my Hugo build and workflow decisions.
- Settling on `kennithnichol` as primary branding.
- Started Hugo scaffold separately fromcontent repo to keep site tidy.
- Considering sharing parts of this as blog entries later.

---

## 2025-06-23 - Theme Tinkering & Cotnent Structure

- Reviewed Hugo themes: PaperMod is feeling like the top contender.
- Thinking about layout structure for case studies (taxonomy? custom sections?).
- Planning to add an "About Me" and potential "Hire Me" page soon.

## 2025-06-23 - Site Setup & Repo Push

- Initialized the Hugo portfolio site under `kennithnichol-site`
- Using PaperMod theme; added config and early folder structure
- Pinned main repos to GitHub profile to align public brand
- Asked Copilot to keep me accountable for logging progress

## 2025-06-23 - Live with Netlify

- Set up Netlify deployment via GitHub integration for `kennithnichol-site1
- Build succeeded using Hugo (PaperMod Theme)
- Needed to specify HUGO_VERSION env var to get build to pass
- Site is live at https://kennithnichol.netlify.app/
- Prepared for using `kennithnichol.com` as custom domain w/ HTTPS

## 2025-06-24 - Portfolio Site Progress

- Refined homepage content using `_index.md`
- Created "About" and "Hire Me" pages, wired into nav
- Verified site structure and nav behaviour on Netlify
- Added `.gitignore` to ignore `public/` and other build artifacts
- Switched domain over to `kennithnichol.com`, DNS has propagated.

