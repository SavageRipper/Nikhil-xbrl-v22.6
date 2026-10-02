# MCA C&I XBRL Web Tool V22.6

Version: **22.6.0**

V22.6 is the V22.5-based MCA C&I XBRL preparation workbench release candidate. It retains the existing taxonomy/table model, dimensional handling, importer, current/prior-year handling, scaling, cash-flow, calculation and validation workflows, with the V22.6 rule-index performance work and release metadata applied.

## Deployment

For GitHub Pages, publish the contents of this directory as the site root and open `index.html`. The production page loads `app-bundled.js`, which contains the MCA taxonomy/business-rule authority data required by the bundled runtime; the development-only `MCA_CNI_AUTHORITY/` and fixture directories are not runtime dependencies of the bundled page.

## External validation

This workbench performs internal preparation and validation checks. It does **not** provide MCA certification, MCA approval, or a guarantee of acceptance. The official MCA XBRL Validation Tool V5.1 remains the final external validation authority before filing.

## Release status

See `V22.6_FINAL_RELEASE_REPORT.md` for the exact regression accounting. The package is named as requested for delivery, but the report explicitly records any release-critical test that could not be certified in the available execution environment.
