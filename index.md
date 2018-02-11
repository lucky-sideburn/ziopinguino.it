---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---
# ziopinguino.it
### Wildcard DNS per qualsiasi indirizzo IP

#### Puoi usarlo in ambienti di laboratorio senza dover utilizzare /etc/hosts o un DNS server interno.Ho preso esempio da [nip.io](nip.io) per lo stack utilizzato (PowerDNS e backend.py)

Esempi di utilizzo:

* **10.0.0.1.ziopinguino.it** risolve con 10.0.0.1
* **app.10.0.0.1.ziopinguino.it** risolve con 10.0.0.1
* **test.app.10.0.0.1.ziopinguino.it** risolve con 10.0.0.1
* **appmeravigliosa.app.10.0.0.1.ziopinguino.it** risolve con 10.0.0.1
* **foobar.10.0.0.1.ziopinguino.it** risolve con 10.0.0.1

Non so fare siti web per cui se usate ziopinguino.it e fate siti web potete effettuare una pull request sul repo <a href="https://github.com/lucky-sideburn/ziopinguino.it">github</a> al fine di rendere questa pagina pi&ugrave; gradevole (anche se in finale va bene così, la parte interessante è sul DNS).
