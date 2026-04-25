# Sturgeon Shield Certificate Form

Single-file GitHub Pages version of the Sturgeon Shield Vehicle Protection Certificate.

## Deploy Files

- `index.html` - certificate form and printable five-page certificate
- `sturgeon-logo.png` - add this logo file at repo root before publishing

## GitHub Pages Setup

1. Create a new GitHub repository.
2. Upload `index.html`, `README.md`, and `sturgeon-logo.png` to the repository root.
3. In GitHub, open `Settings` -> `Pages`.
4. Set source to `Deploy from a branch`.
5. Select branch `main` and folder `/ (root)`.
6. Save and use the Pages URL after GitHub finishes publishing.

## Final QA

- Confirm the Sturgeon logo loads from `sturgeon-logo.png`.
- Confirm the form defaults to Stand Alone with Stand Alone product rows.
- Select package/tier and confirm the product table updates automatically.
- Use Clear Form and confirm the form resets to a blank Stand Alone certificate.
- Sign both signature boxes.
- Confirm Print / Save PDF creates the full five-page certificate and shows the next-form toast after the print dialog closes.
