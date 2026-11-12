# A10 team website package

Team: Rick Bhattacharya, Antonio Chiocca, Patrick Klauser. Total time: 10 hours.

## Open the report
Open index.html, or serve this folder with a static HTTP server. All figures and local downloads use relative paths. The HTML is buildless and contains the report styles. No account, API, framework, or JavaScript library is required.

## Add it to a portfolio
- For a MkDocs portfolio, copy the contents of `mkdocs/` into `docs/assignments/A10/`, then put the package's `images/` and `files/` folders beside index.md. Add A10 to the existing navigation if needed.
- For another framework, use `report.md` or the `<main>` contents of index.html. Keep the supplied figures, captions, numerical values, attribution, caveats, and relative download links. Adapt the visual shell to the destination website.
- The technical report is shared team content. Keep all three named contribution sections when posting it to individual portfolios.

## Files
`files/A10-team-report.pdf`: complete report with original handwritten-work appendix, original crosshead drawing, and original BOM.
`files/tensile-tester.f3z`: Fusion assembly archive including referenced components.
`files/crosshead.f3d`: Fusion crosshead archive.
`files/Crosshead.pdf`: unchanged original CAD drawing export.
`files/A10-BOM.pdf` and `files/A10-BOM.csv`: original budget and typed table.
`files/A10-engineering-data.json`: machine-readable calculation and result values.
`files/A10-original-work.zip`: original calculation photos, with SHA256 checksums.
`SHA256.json`: checksums for this transfer package.

## Content integrity
The conditional screw calculation gives 23.551 lbf·in per screw for the worksheet radius and friction coefficient with the Acme angle included. The 22.817 value is the square-thread approximation. The full-diameter combined-stress bound is below FOS 4 under those assumptions, so the selected screw is not approved for combined loading. The FEA screenshots are two geometry studies, not a mesh-convergence series. No CAD mass or volume reduction was recorded; no estimated mass-reduction figure is included. The 2-kN load is the design requirement; the supplied response plots do not display the applied load magnitude. The cost-sheet screw stock differs from the precision screws in CAD. Keep these qualifications when moving the report. Do not invent missing refinement results, load confirmations, certifications, or completed tests.

## Distribution controls
Integration instructions are contained only in this README. They are not part of the report or webpage.
