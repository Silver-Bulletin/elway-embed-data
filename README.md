# ELWAY and QBERT hosted embeds

This public repository serves the approved chart data and permanent chart pages
used by Silver Bulletin. It contains no credentials, licensed source exports,
simulation code, or private model inputs.

The chart pages fetch versioned, same-origin CSV files from `data/latest/`.
Readers' browsers therefore do not need to contact Google Sheets, and the
Substack iframe URLs never change. Production Sheets can be updated and audited
without changing the public charts; the public release changes only when the
private ELWAY pipeline runs its explicit embed-site publisher.

The live index and copyable Substack snippets are published through GitHub
Pages at <https://silver-bulletin.github.io/elway-embed-data/>.
