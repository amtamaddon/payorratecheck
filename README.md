# Payor Rate Check

Static site for ratecheckmd.com. A practice looks up its published negotiated rates from UnitedHealthcare, Blue Cross Blue Shield, Anthem, Aetna and Cigna, next to the typical rate for its specialty in its state. It is built from the payers' Transparency in Coverage files. Data arrives monthly through `.github/workflows/publish.yml`, which copies a gated build from a private refresh. Typing a management company's name lists its practices (`mso.json`).

Run by RSK Health; not affiliated with any payer.
