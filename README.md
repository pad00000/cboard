# cboard

Static, encrypted dashboard for personal use. The transaction data inside
`index.html` is AES-256-GCM encrypted with a PBKDF2-derived key — without
the passphrase the file is unreadable.

Generated automatically by `make_dashboard.py` from a per-row CSV export.
