# Security

No credentials are stored in this repository. All keys and tokens live outside it,
in the backend's own secret store, and are never committed.

Payments are handled entirely by Stripe on Stripe's own domain; no card data reaches
this site.

## Reporting

Found a security issue? Please email the address in the site footer rather than
opening a public issue, and allow a reasonable window for a fix before disclosing.
