# Zineb El Hadri — Cybersecurity Portfolio

Responsive React, Vite, and TypeScript portfolio with client-side routing, dark/light theme persistence, interactive project filters, project detail pages, a SOC walkthrough, and a skill-to-work explorer.

## Local development

1. Install Node.js 20 or later.
2. Run `npm install`.
3. Run `npm run dev` and open the local URL Vite prints.
4. Run `npm run build` for the production build; `npm run preview` serves it locally.

## CV

The supplied CV is stored at `public/Zineb-El-Hadri-CV.pdf`; the download button saves it with that filename. The supplied portrait is stored at `public/zineb-el-hadri.jpg` and used in the responsive hero frame.

## Deploy to Vercel

Import this folder as a Vite project. Use `npm run build` and `dist` as the output directory. `vercel.json` routes client-side paths to the app entry point.

## Content

Portfolio content is maintained in `src/content.ts`. Update projects, experiences, skills, study history, contact details, and training there. Training items are deliberately described as courses, not verified certifications.
