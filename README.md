# ELWAY and QBERT hosted embeds

This public repository serves the approved chart data and permanent chart code
used by Silver Bulletin. It contains no credentials, licensed source exports,
simulation code, or private model inputs.

The direct-paste Substack files under `direct/` fetch approved CSV files from
`data/latest/`. Readers' browsers therefore do not need to contact Google
Sheets. Production Sheets can be updated and audited without changing the
public charts; the public release changes only when the private ELWAY pipeline
runs its explicit publisher.

GitHub Pages also provides browser previews at
<https://silver-bulletin.github.io/elway-embed-data/>. Substack does not permit
that domain as an iframe source, so use the complete HTML files in `direct/`,
not iframe tags.
