# Requirements (Version 1.0)

These requirements describe the **minimum** portfolio site experience I want to deliver for:

- **Recruiters / hiring teams** (fast evaluation)
- **Potential clients** (assess fit)
- **Fellow developers** (review work + collaborate)

This is written from the perspective of a solo developer today, but structured the way teams often communicate requirements in an enterprise setting: **scope → user outcomes → functional requirements → quality attributes → open questions**.

---

## MVP scope (June 4 meetup)

### In scope

- Home (landing page)
- About
- Experience / Resume access
- Contact

### Out of scope (for now)

- Polished visual design system
- Full project case studies (can be placeholders)
- Analytics/monitoring/alerts (planned for later)
- Deployment automation (planned for later)

---

## User outcomes (what success looks like)

- A recruiter can understand my focus and strengths in **10–30 seconds**.
- A visitor can reach **resume and contact info in 1 click** from the landing page.
- The site works on mobile and desktop without usability issues.

---

## Functional requirements (what the site must do)

- **FR1 — Navigation:** Users can navigate between primary sections/pages from any page.
- **FR2 — Landing page:** The first page a visitor sees clearly introduces who I am and links to the most important sections (About, Experience/Resume, Contact).
- **FR3 — Resume access:** Users can view and/or download my resume.
- **FR4 — Contact info:** Users can find at least one reliable way to contact me (email required; other links optional).
- **FR5 — Contact message:** Users have a way to send me a message (a form or a clear alternative method).
- **FR6 — Mobile access:** Users can access and use the site on mobile devices.

---

## Non-functional requirements (quality attributes)

- **NFR1 — Responsive:** Layout adapts cleanly to desktop and mobile.
- **NFR2 — Professional:** Tone, writing, and layout feel credible for job search and client conversations.
- **NFR3 — Performance:** Pages load quickly and don’t feel sluggish.
- **NFR4 — Accessibility:** Basic accessibility expectations are met (readable contrast, usable navigation).
- **NFR5 — Maintainability:** Content and structure are easy to update as I add projects and experience.
- **NFR6 — Compatibility:** Works across common modern browsers/devices.

---

## Constraints & considerations

- Messages to me may include feedback, networking outreach, or job/project opportunities.
- I will test locally and keep work in a GitHub repo.
- A pilot release will be used to gather feedback before expanding scope.

---

## Open questions (for meetup + feedback)

- What should the landing page emphasize most: **skills**, **impact**, or **projects**?
- What is the most useful resume experience: **embedded view**, **download**, or both?
- What’s the best “contact message” approach for an early MVP: form vs direct email link?
- Which 1–3 projects would be strongest to feature first (even as placeholders)?
