# DNS / deSEC note

Your website DNS and ImprovMX email can coexist.

For the website:
- Create the A/AAAA/CNAME record required by your web host for `more4uproductions.dedyn.io`.
- Do NOT remove MX records used by ImprovMX.
- Do NOT replace SPF/DKIM/DMARC records that your mail setup requires.

The exact website record depends on the host, so use the host's published target rather than guessing an IP.
