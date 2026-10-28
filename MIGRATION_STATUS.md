# KPS website migration — staging only

This branch is reserved for migration of the existing `kpslaweu.com` website without Antigravity.

The complete source package (100 files) is currently prepared in the ChatGPT conversation as `KPS_GitHub_Migration_Staging_2026-10-28.zip`; it has **not yet been committed to this repository**.

## Critical predeployment checks

1. Review all proposed files for client confidentiality and secrets before pushing into this **public** repository.
2. Verify the actual production hosting service and DNS; a CNAME in a local backup does not prove GitHub Pages is the live host.
3. Verify any Netlify serverless dependencies; `translate-columns.js` is retained as an optional file in the package.
4. Stage full site content and test all pages, navigation, multilingual Careers page, homepage notice, accessibility, mobile, and forms.
5. Approve and verify rollback before any production deployment.

No changes to production hosting, DNS, or main branch are authorized by this staging note.
