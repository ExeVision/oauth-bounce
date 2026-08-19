# oauth-bounce

Static HTTPS redirect page for a local OAuth authorization flow that requires
an HTTPS redirect URI.

The page has no server-side logic and stores nothing: it forwards the
browser's query string straight to a local one-shot callback server on
`http://localhost:8080/callback`.
