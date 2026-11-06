# Hamid Bostani — customized al-folio website

This package is a complete copy of the official al-folio starter, customized with Hamid Bostani's initial website content.

## What is included
- The complete al-folio template source.
- A concise homepage inspired by Fabio Pierazzi's academic-site structure.
- A separate publications page and 19 bibliography entries transcribed from the supplied CV.
- Four selected peer-reviewed papers highlighted on the homepage.
- A small news section with the dated PhD defense announcement.
- Existing profile photograph and supplied CV PDF.
- The existing GitHub Pages URL configured as `https://hamidbostani2021.github.io`.

## Important: this package is not yet published
Your existing GitHub repository has not been changed. Do not delete or replace its files until the new site is checked.

## How the site is configured
- Repository name expected: `HamidBostani2021.github.io`
- Site URL: `https://hamidbostani2021.github.io`
- `baseurl` is intentionally blank for a user/organization GitHub Pages site.
- The included `.github/workflows/deploy.yml` builds the Jekyll site and deploys it from the `main` or `master` branch.

## Before publication
1. Confirm the selected profile photo is the one you want to use.
2. Confirm the CV PDF is the public version you want linked.
3. Review author spellings and bibliographic metadata, especially entries where the CV uses initials.
4. Confirm whether the three 2026 manuscripts are still under peer review and whether the 2026 Springer survey is now published.
5. Add any other public profile links you want (e.g., ORCID, LinkedIn).
6. Test the Jekyll build and the GitHub Actions deployment before changing the live site.

## Notes
- The website intentionally does not reproduce every CV section.
- Teaching, skills, detailed employment history, full talks list, and other CV-only material are not separate website sections.
- The phone number and office address have not been published.
- The bibliography reflects the CV supplied for this project and should be checked before public release.
- This is based on the al-folio `main` branch ZIP uploaded in this conversation. A local build was not run here because the Ruby/Node dependencies are not installed in this environment.


## Temporary project-site test configuration
This archive is configured for the temporary repository `hamidbostani-al-folio-test` with `baseurl: /hamidbostani-al-folio-test`. Do not use this configuration when moving to the final user-site repository `HamidBostani2021.github.io`; for that final repository, set `baseurl:` to blank.
