# Student Database System

Starter structure for a private student-management project.

## Important security rules
- Never commit real student records, IC/passport numbers, passwords, tokens, private keys, service-account JSON files, or real document images.
- GitHub Pages publishes a public website. Treat every deployed page and asset as public.
- Keep Google Sheets and Drive private. Access them only through a trusted backend after authorization.
- Do not use Drive "Anyone with the link" sharing for student files.
- Use Firebase Authentication for sign-in and verify Firebase ID tokens in the backend.
- Enforce roles and classroom assignments on the backend for every read/write request.

## Suggested structure
- `schemas/`: empty CSV header templates only; no student data.
- `docs/`: setup notes.
- `index.html`: safe placeholder page for initial Pages deployment.
- `functions/`: backend implementation will be added after Firebase project setup.

## Student ID policy
Generate IDs on the backend only, using `STU-YYYY-NNNN` (example: `STU-2026-0001`).
Use a lock/transaction strategy to prevent duplicate sequence numbers.

## Initial setup
1. Create a GitHub repository named `student-database-system`.
2. Keep the repository free of real student data and credentials.
3. Upload this starter package contents.
4. Configure GitHub Pages only after reviewing the repository contents.
5. Create Google Sheets and Drive folders, keep both private.
6. Configure Firebase Authentication and backend before connecting real student data.

## Data model
See the CSV header templates in `schemas/`. These are schema templates, not live databases.
