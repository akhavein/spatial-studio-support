# Spatial Studio public support site

Public home, accuracy, privacy and support pages are hosted at https://akhavein.github.io/spatial-studio-support/ from the repository root on `main`.

## Search discovery

Each of the four public pages has an absolute self-canonical. `sitemap.xml` lists only those pages; the existing `404.html` remains noindex and is omitted. No private scans, diagnostics or project files belong in this site.

GitHub Pages serves this project beneath `/spatial-studio-support/`. A robots file placed here would not control the origin. Origin-wide robots policy belongs to the separate account-root Pages site and is intentionally not changed by this project. The project sitemap can be submitted directly in the corresponding Search Console property.

Validation: parse the sitemap as XML; verify every listed route maps to an existing index.html with exactly one matching canonical; retain the 404 noindex; compare rendered public pages before publication. Deploying the repository follows the existing main-branch Pages configuration. No new agent service, DNS or bot-access policy is required.
