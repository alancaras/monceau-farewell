# monceau.com.au DNS as published on 6 Oct 2026 (before leaving Cloudflare)

Nameservers at the time: brenda.ns.cloudflare.com, lakas.ns.cloudflare.com

## Keep (email – Google Workspace)
| Type | Name | Value | Priority |
|---|---|---|---|
| MX | @ | aspmx.l.google.com | 1 |
| MX | @ | alt1.aspmx.l.google.com | 5 |
| MX | @ | alt2.aspmx.l.google.com | 5 |
| MX | @ | aspmx2.googlemail.com | 10 |
| MX | @ | aspmx3.googlemail.com | 10 |
| TXT | @ | v=spf1 include:_spf.google.com ~all | |
| TXT | @ | google-site-verification=SzvPGT4Te09oRcPz9FP-mtkWwDyDcg8530IpkTjUyCA | |
| TXT | @ | google-site-verification=wORX429DfN5NA31LZ4NsGjcGtUiJFMhA0aieJl1KA_M | |

## Replace (website – was Shopify, now GitHub Pages)
| Type | Name | Old value | New value |
|---|---|---|---|
| A | @ | 23.227.38.32 | 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153 |
| CNAME | www | monceau-co.myshopify.com | alancaras.github.io |

## Not recreated (old marketing tools)
| Type | Name | Value |
|---|---|---|
| TXT | @ | facebook-domain-verification=5txbgi82rgg7tc8rbk691ztt0jj79w |
| TXT | @ | klaviyo-site-verification=XvAwGs |
| CNAME | s1._domainkey | s1.domainkey.u20296287.wl038.sendgrid.net |
| CNAME | s2._domainkey | s2.domainkey.u20296287.wl038.sendgrid.net |
| CNAME | kl._domainkey | kl.domainkey.u161779.wl030.sendgrid.net |
| CNAME | kl2._domainkey | kl2.domainkey.u161779.wl030.sendgrid.net |
