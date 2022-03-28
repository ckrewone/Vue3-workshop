---
theme: default
class: text-center
highlighter: shiki
lineNumbers: true
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
drawings:
  persist: false
title: Warsztat#5 - DevOps
layout: cover
altCover: cover-alt
clicks: 1
---

# Deploy na produkcje naszej aplikacji

---

# Co będziemy potrzebować?
- VPS
- aplikacji (git z dostepem ssh)
- nginx (reverse proxy i serwer plików statycznych)
- pm2 (do uruchomienia backendu)
- nodejs

---

# Najpierw zacznijmy od VPSa
## Logujemy się do azure:

---

...

---
---
# Pobrany klucz ssh kopiujemy do ~/.ssh/

cp ./ssh.pem ~/.ssh/
chmod 600 ~/.ssh/ssh.pem

---
# Logujemy się na server

ssh ubuntu@52.172.3.43
The authenticity of host '52.172.3.43 (52.172.3.43)' can't be established.
ECDSA key fingerprint is SHA256:ZSPIL734dgYeXSU8hts1TKgyPBamwB6Q0nS+HofdW50.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added '52.172.3.43' (ECDSA) to the list of known hosts.


---
# Tworzymy klucz ssh i dodajemy do Bitbucket

---

