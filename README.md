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
- The hero animation is a live visualization of the paper's own two methods on
  Example 1, `f(x) = (x−1)³ − 1` (root `x* = 2`). It cycles between:
  - the **Perpendicular Method** — secant line + a perpendicular dropped through
    the axis point, meeting at the corrected iterate; and
  - the **Extension of the Secant Method (n = 3)** — the nᵗʰ-power parametric line
    that crosses zero at the next iterate.
  Both converge on the amber root marker, then loop.
- Type: Space Grotesk (display), Newsreader (body), IBM Plex Mono (data/labels), via Google Fonts.
- Fully responsive, keyboard-focusable, and respects `prefers-reduced-motion`
  (the animation freezes on the converged Perpendicular-Method state).

## To update
- **Add a publication:** copy one `.pub` block inside the relevant `.pub-group`
  in `index.html` and edit the tag, title, and venue.
- **Swap the CV:** replace `Md_Asadujjaman_Miah_CV.pdf` (keep the same filename).
- **Links:** the Google Scholar buttons point to your profile
  (`scholar.google.com/citations?user=ZhM5fREAAAAJ`); GitHub, LinkedIn, and email are
  wired in the hero and footer.
