# Third-party assets

Bootstrap 5.3.3 is self-hosted to keep the CSP restricted to this origin.

- CSS source: https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css
- JavaScript source: https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js
- License: BOOTSTRAP-LICENSE (MIT, upstream v5.3.3)

Both files are pinned by SHA-384 integrity attributes in src/helpers.php.
When updating Bootstrap, review the release, replace both assets, update the
integrity hashes and repeat CSP, mobile-navigation and caption-preview checks.
