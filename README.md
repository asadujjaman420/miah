# Md. Asadujjaman Miah — Academic Portfolio

Personal academic portfolio for **Md. Asadujjaman Miah**, a final-year Applied Mathematics
student at the University of Dhaka. Research focus: numerical root-finding, physics-informed
neural networks (PINNs), integral equations with discontinuous kernels, and precision-guaranteed
computation (CESTAC / CADNA).

## Live site
Once deployed via GitHub Pages: `https://<username>.github.io/<repo>/`

## Repository structure
- `index.html` — the full single-page portfolio (all CSS + JS inline, no build step)
- `Md_Asadujjaman_Miah_CV.pdf` — CV, linked from the "Download CV" buttons
- `README.md` — this file

## Deploying on GitHub Pages
1. Put `index.html` and `Md_Asadujjaman_Miah_CV.pdf` in the repository **root**.
2. In the repo, go to **Settings → Pages**.
3. Under *Build and deployment*, set **Source = Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Save. The site is live at the URL shown on that page in a minute or two.

## Design notes
- The hero animation is a live **secant-method** solving `f(x) = x³ − 2x − 5 = 0`
  (root `x* ≈ 2.0946`) — a nod to the Perpendicular / Extended Secant methods.
- Type: Space Grotesk (display), Newsreader (body), IBM Plex Mono (data/labels), via Google Fonts.
- Fully responsive, keyboard-focusable, and respects `prefers-reduced-motion`
  (the animation freezes on the converged state).

## To update
- **Add a publication:** copy one `.pub` block inside the relevant `.pub-group`
  in `index.html` and edit the tag, title, and venue.
- **Swap the CV:** replace `Md_Asadujjaman_Miah_CV.pdf` (keep the same filename).
- **Google Scholar link:** the "Google Scholar" buttons currently point to a name search.
  Replace both `https://scholar.google.com/scholar?q=Md.+Asadujjaman+Miah` links with your
  profile URL once your Scholar page is set up.
