# Sidharth Nair — Product Manager Portfolio

**Live site:** howdysid.com


A live, interactive portfolio built to show product management thinking through working artifacts, not slides. Instead of case-study writeups, each project on this site is a functioning tool a visitor can actually use in the browser.

## About

I'm a product-minded engineer with 3+ years of experience in automotive technology, now pivoting into product management. I combine technical depth, analytical thinking, and user empathy to turn problems into product opportunities — this site is where I show that work.

## Featured artifact — The Drop-Off Backlog

An interactive RICE and MoSCoW prioritization board built around six real onboarding friction points pulled from Indian lending app reviews (Play Store, Reddit, Quora) — the actual reasons users abandon KYC/onboarding mid-flow.

- **RICE view** — move the Reach, Impact, Confidence, or Effort slider on any friction point and watch the backlog re-rank itself live, using `RICE = (Reach × Impact × Confidence) ÷ Effort`
- **MoSCoW view** — the same six points re-sorted into Must / Should / Could / Won't have, each with a "Why" and a live cross-reference back to its RICE score
- Every score comes from live input, not hardcoded numbers — the point of the artifact is the mechanism itself, not the specific ranking

→ [`projects/drop-off-backlog/index.html`](projects/drop-off-backlog/index.html)

## Built with

Vanilla HTML, CSS, and JavaScript — no framework, no build step, no dependencies. Every project is a single self-contained `index.html`, so it's easy to open, read, and extend.

## Structure

```
index.html                        → main site (hero, projects, contact)
styles/main.css                   → shared design tokens and styles
script.js                         → nav toggle, scroll reveal, interactions
assets/                           → résumé, profile photo
projects/
  drop-off-backlog/index.html     → The Drop-Off Backlog (RICE + MoSCoW artifact)
```

## Get in touch

- LinkedIn: [linkedin.com/in/sidharth-nair07](https://www.linkedin.com/in/sidharth-nair07)
- Email: [sidharthnair07@gmail.com](mailto:sidharthnair07@gmail.com)