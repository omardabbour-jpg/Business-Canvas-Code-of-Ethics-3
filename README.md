# AP Business — Task 5: Stress Test and Code of Ethics

Interactive student worksheet for AP Business. The website is **index.html**; this README is documentation, not the website itself.

## Deploy on GitHub Pages

1. Create a repository on GitHub.
2. Upload `index.html` and `README.md` to the **root** of the repository (not inside a subfolder).
3. Commit both files to the `main` branch.
4. In **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, and save.
5. Wait for deployment, then open the **GitHub Pages URL** displayed in Settings → Pages (usually `https://USERNAME.github.io/REPOSITORY/`). Do not use the repository's source-file URL as the website.

## Troubleshooting

- **404:** Check the exact spelling `index.html`, that it is in the repository root, the selected branch and folder, and that deployment has finished.
- **Source code appears instead of webpage:** Open the GitHub Pages URL, not the `github.com` file viewer.
- **PDF button unavailable:** The PDF library requires internet access. Use **Print / Save as PDF** instead.
- **Answers missing:** Responses are stored locally in the same browser/device only. Clearing browser data or changing devices can remove access to them.

## Student submission

Students fill in the activity, export or print to PDF, and upload that PDF through the school LMS. The website does not send responses to the teacher automatically.

## Fix included

The previous file placed JavaScript inside a `<script src="...">` element; browsers ignore that inline code. This version separates the external script tag correctly and retains the working button handlers in the main script.
