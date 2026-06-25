# Blocking Invention Map

Interactive visualization of UltronAI's checkout product recognition **patent blockers**.

A radial map of the 22 inventions across three core areas — Product Enrollment, Detection & Recognition, and Customer Experience / Latency. Each invention popup shows its blocker status (Critical Blocker / Important Blocker / Important Patent), patent number, and the reviewed write-up: what it accomplishes, why it works, and why this produces a superior result.

This is the "blocking" companion to the Invention Summary map — same structure and layout, with the reviewed/merged wording and per-patent blocker headers.

## Stack
Next.js (App Router) + React + SVG. Content lives in `src/data/inventions.js`; the graph is `src/components/InventionMap.jsx`; the detail popup is `src/components/Popup.jsx`.

## Development
```bash
npm install
npm run dev
```
Open http://localhost:3000.
