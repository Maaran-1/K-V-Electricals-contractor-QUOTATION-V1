K V ELECTRICALS CONTRACTOR — MOBILE SOURCE UPDATE

This ZIP contains source replacement files, not a complete project:
- App.tsx
- index.css

UPDATE INCLUDED
- Quotation footer tagline is now split into two lines:
  POWERING YOUR PROJECTS
  WITH TRUST AND EXPERIENCE.
- The second line is styled electric blue in print/PDF output for a premium dark-footer contrast.
- Existing mobile-friendly CSS and quotation features are retained.

HOW TO APPLY
1. Back up your existing project.
2. Replace src/App.tsx and src/index.css with these files (adjust paths if your project uses a different source folder).
3. Keep your existing package.json, index.html, public assets, and other project files.
4. Run `npm run build` to check for errors, then `npm run dev` to preview.
5. Check the quotation print/PDF preview on both desktop and a phone-sized viewport before using it for customers.

IMPORTANT
This source update has not been verified with a full npm build or on a physical phone in this session. Quotation data is still stored in the browser's localStorage and does not automatically sync across devices.


UI wording update: removed the AppDeploy/local-only status labels and replaced them with customer-facing workspace wording. This is a wording/UI update only; quotation records still use browser localStorage and do not sync between devices. Online hosting does not add cloud storage.
