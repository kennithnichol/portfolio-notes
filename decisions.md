# Project Decisions

A log of key decisions, tech tradeoffs, and design choices made while building my portfolio.

---

## Domain strategy

**Primary domain:** `kennithnichol.com`
** Rationale:** Global appeal, easy to remember, professional branding.
`.ca` held and redirected for regional trust and possibly future use.

---

## Hugo vs Astro

**Chose Hugo** for site generator
**Rationale:**
- Wanted Golang practice
- Static speed and simplicity
- Deep control over layout and content

---

## Repository Structure

- Hugo project lives in `portfolio-site`
- Case studies and emta notes separated for clarity
- Might consider bringing case study Markdown into Hugo later, once templated

---

## 🛠️ Kowledge Management & Workflow

### Notes Strategy
**Decision:** Continue using GitHub + Markdown for primary note-taking and devlog
**Rational:**
- Versioned history and portability
- Keeps everything in on familiar ecosystem
- Leaves room to layer in automation with shell/Go scripts later
- Low-friction and lightweight compared to heavier tools (Notion/Obsidian)

---

## 🌐 Deployment & Hosting

**Decision:** Use Netlify for deplyoing `kennithnichol-site`
**Rationale:**
- Built-in Hugo support and seamless GitHub integration
- Free custom domain support + HTTPS
- Strong dev UX with build logs, rollbacks, and previews
- Aligns with long-term cloud-centric architecture goals

---

## 🧠 Personal Branding

**Decision:** Publicly include Zero To Mastery (ZTM) mentorship across portfolio and GitHub
**Rationale:**
- Reflects mentorship ethos and developer community engagement
- Enhances personal branding and credibility
- Adds context to site visitors and clients seeking well-rounded professionals

