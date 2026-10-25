# Candidate Assessment Dashboard

A static site for GitHub Pages. It uses `index.html` and the supplied `pup-ou-seal.svg` asset; no build tool, package install, or server is required.

The scatter plot uses fixed Project Manager and QA Tester axes with multi-select role-area filters. When multiple role filters are selected, a candidate appears only if every selected role is included in that candidate's top assessed role areas. The candidate directory sorts alphabetically by surname.

## Publish with GitHub Pages

1. Create a GitHub repository for the site and add `index.html` at the repository root.
2. Open **Settings → Pages**.
3. Under the build and deployment source, choose **Deploy from a branch**, select the default branch and the `/ (root)` folder, then save.
4. GitHub Pages will provide the published address after its deployment finishes.

## Before publishing

GitHub Pages sites are public. The dashboard currently displays candidate names, assessment scores, role ratings, and assessment notes to every visitor. Share or publish it only after confirming that public display is appropriate and that candidates' identities are correct.

The certificate creates a QR code that points to the site's homepage after deployment. On a local `file://` preview, the QR box explains that hosting is required first. The QR code library is loaded from cdnjs, so certificate QR generation requires an internet connection.

The certificate is designed to print on one landscape Letter page. Cinzel and Source Sans 3 are loaded from Google Fonts, with serif and sans-serif fallbacks when the font service is unavailable. Browser print headers and footers should be disabled to avoid printing the page URL or file name.

The overall score is calibrated to the requested 78–98 range. Role ratings are shown separately on the original 20-point rubric scale.

