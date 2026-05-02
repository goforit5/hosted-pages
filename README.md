# hosted-pages

Public umbrella for client-facing HTML decks served via GitHub Pages.

Each deck lives at `/<random-slug>/index.html`. URL: `https://goforit5.github.io/hosted-pages/<slug>/`

Slugs are unguessable hex (12 chars). This is **public-by-obscurity**, NOT private. Don't push PII, credentials, therapy content, financial details, or anything sensitive.

To revoke a deck: `git rm -rf <slug>/ && git commit && git push`.

Created 2026-05-01 because Supabase categorically blocks HTML hosting (forces text/plain + sandbox CSP on all HTML responses).
