# The organisation's github.io root

This repository exists for one reason: GitHub serves a hostname's root
(`https://<org>.github.io/`) only from a repository named exactly
`<org>.github.io`, and the Vouchwell site does not live here.

The site is at **<https://vouchwell.axonscape.com/>**, built and deployed from
[`site/` in the main repository](https://github.com/vouchwell/vouchwell/tree/main/site).
`index.html` sends anyone arriving at the old `github.io` address there,
keeping any `#anchor` the old link carried. Keeping the source in one place is
why this is a redirect and not a copy.

Nothing else belongs here. To change the site, change it there.
