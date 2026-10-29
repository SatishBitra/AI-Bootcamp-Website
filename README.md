# SARKTEK learning website

React and TypeScript implementation of the SARKTEK AI and SAP learning website. The site uses reusable course and bootcamp data with path-based page rendering and Vite's SPA fallback.

## Run locally

```sh
npm install
npm run dev
```

## Routes

- `/` — homepage and learning paths
- `/courses` — AI/SAP catalogue and category filters
- `/courses/:slug` — six reusable course detail pages
- `/bootcamps` — four in-person bootcamps
- `/bootcamps/:slug` — audience-specific bootcamp detail pages
- `/find-your-course` — client-side, rule-based course finder
- `/why-sarktek`, `/blogs`, `/blogs/:slug`, `/contact`, `/privacy`, `/thank-you`

Course, bootcamp, and sample blog content is defined in `src/site.tsx`; local SVG artwork is stored in `src/assets`. The enquiry form is intentionally a frontend demonstration: no CRM, email recipient, persistence, analytics, or server validation has been configured. It does not claim that an enquiry was sent.
