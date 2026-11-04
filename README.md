# Aniket Vishwakarma

**Backend and real-time systems.** I ship products with real users on them, then write down what broke.
Mumbai, India · B.E. Information Technology, Mumbai University — 2027

[Portfolio](https://aniket-vishwakarma-portfolio.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/aniket-vishwakarma-bb1b922b5) · [Email](mailto:aniketvishworks@gmail.com) · [Résumé](<RESUME-PDF-URL>)

---

## 01 · Selected work

### Student Placement Prediction — live
`197+ users` · `4,400+ views` · `6m 05s avg. session` · `6,700+ tracked events` · measured Oct 2026

A placement-readiness platform used by students, faculty and placement officers at my university. Predicts placement probability from a form or a parsed résumé, scores résumés against ATS criteria, and gives each role its own dashboard.

The part I'd point at is the failure path: Gemini 2.5 is primary, Cloudflare Workers AI takes over automatically when it errors, and inference degrades to the local scikit-learn model instead of to an error page.

`Next.js` `TypeScript` `Python` `scikit-learn` `MongoDB` `Firebase` `Gemini 2.5` `Cloudflare Workers AI`

[Live](<LIVE-URL>) · [Code](<REPO-URL>) · [How it's built](<CASE-STUDY-URL>)

### EcoVision Bharat — 1st place, GNA Hackathon 4.0 (Clean & Green Technology)
`3 role types` · `YOLOv8 inference` · `GPS-tagged reports`

Civic waste reporting: citizens submit a photo and a location, officers verify and dispatch, sanitation workers track the job to closure. YOLOv8 estimates waste severity server-side so triage doesn't depend on the reporter's description.

`React 19` `Vite` `Node` `Express` `FastAPI` `YOLOv8` `Supabase` `PostgreSQL`

[Live](<LIVE-URL>) · [Code](<REPO-URL>) · [Award](<CERTIFICATE-URL>)

### Also built

- **Video calling app** — peer-to-peer calls over WebRTC with signalling and renegotiation. `WebRTC` `Socket.IO` `Node` — [Code](<REPO-URL>)
- **Social platform** — auth, posts, follows, live feed. `MERN` `Socket.IO` `JWT` — [Code](<REPO-URL>)
- **Stock tracker** — live quotes with a simulated trading ledger. `Node` `Express` `REST` — [Code](<REPO-URL>)

---

## 02 · Toolbox

```text
Languages    TypeScript · JavaScript · Python · Java
Frontend     React · Next.js · Tailwind · Recharts
Backend      Node · Express · FastAPI · REST · Socket.IO · WebRTC
Data & ML    MongoDB · PostgreSQL · Supabase · scikit-learn · YOLOv8 · Gemini · Workers AI
Infra        Vercel · Render · Cloudinary · Git
