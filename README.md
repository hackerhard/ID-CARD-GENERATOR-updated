Student ID Card Generator (GitHub Pages)
======================================

Files:
- index.html  — Single-file app (HTML + Tailwind + JS). Drop this into a GitHub repo and enable GitHub Pages.
- student_template.csv — CSV template for bulk uploads.
- README.md — this file.

How to use:
1. Create a new GitHub repo (public or private).
2. Upload `index.html` and `student_template.csv`.
3. In repo Settings → Pages, set source to main branch (root) and save.
4. Visit the provided GitHub Pages URL to use the app.

Notes:
- Bulk CSV parsing supports headers. Photos per-row are not supported in CSV (use the single-student photo upload for those).
- You can add generated cards to the batch and click 'Print All' to print multiple cards on one go.
