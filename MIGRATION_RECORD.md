# Draft migration record

Source: `https://github.com/msp-operations/MSP-Remodel-Preview.git`

Source commit: `53505b2a16d68dee1445af0dbbb9c5daf1162920`

Source directory: `(repository root: five site files plus msp-ui/)`

This repository is a copied **draft**. It does not deploy automatically, and the original site is unchanged. Binary files, code and local UI assets were retained.

Changes limited to repository separation:

- Updated only the 9 `next` URLs in `projects.js` to the existing publicly hosted preview, because the apps no longer reside in child directories of this repo.

Do not enable production deployment or move domains until links and workflows have been tested. Existing links to the original preview and external services were intentionally preserved. If renamed, review any absolute site path references.
