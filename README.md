# RedHelp

Un mémo regroupant des commandes et explications utiles pour la formation Guardia en cybersécurité.  
Ce guide vise à t'aider à gagner du temps pendant les TP, CTF ou audits d'entraînement.

---

## 🗂️ Fichiers disponibles

- [`Guide.txt`](./Guide.txt)
  ➤ Le fichier principal. Toutes les étapes d’un audit ou d’un test d’intrusion, de la reconnaissance jusqu’à la post-exploitation.

- [`automatisation_scripts.txt`](./automatisation_scripts.txt)
  ➤ Explique comment créer tes propres scripts Bash pour automatiser les tâches répétitives.

- [`bypass_filtrage.txt`](./bypass_filtrage.txt)
  ➤ Techniques pour contourner les protections (WAF, filtres d’extensions, encodage, etc.).

- [`crypto_hashes.txt`](./crypto_hashes.txt)
  ➤ Comment identifier, comprendre et casser des hashs (MD5, SHA1, bcrypt, NTLM…) avec les bons outils.

- [`memo_exploitation_services.txt`](./memo_exploitation_services.txt)
  ➤ Un résumé clair des services (FTP, SSH, HTTP, SMB…) avec les types d’exploitation possibles pour chaque port.

- [`nettoyage_post_exploit.txt`](./nettoyage_post_exploit.txt)
  ➤ Étapes pour effacer proprement les traces d'une exploitation (bash history, logs, fichiers temporaires…).

- [`outils_reconnaissance_sup.txt`](./outils_reconnaissance_sup.txt)
  ➤ Liste enrichie d'outils de reconnaissance supplémentaires (OSINT, DNS, scans réseau, fingerprinting…).

- [`payloads.txt`](./payloads.txt)
  ➤ Liste commentée de payloads pour XSS, LFI, SSTI, reverse shell, command injection, etc.

---

## Site WEB

🧰 Outils et générateurs
-------------------------
Site                                    | Utilité
----------------------------------------|---------------------------------------------------------------
[RevShells](https://www.revshells.com/)               | Générateur de reverse shells (bash, php, python, etc.)
[CrackStation](https://crackstation.net)                | Déchiffrement de hash par force brute ou rainbow tables
[Hashes](https://hashes.com/en/tools/hash_identifier) | Identification automatique de hash
[CyberChef](https://gchq.github.io/CyberChef/)       | Couteau suisse pour encodage, décodage, crypto, etc.
[Decoder](https://decoder.link)                    | Tester et analyser des requêtes HTTP, injections, payloads
[Decode Brain Fuck](https://brainfuck.rmjtromp.dev/)               | Décodeur BrainFuck pour analyser des payloads obscurs
[GTFOBins](https://gtfobins.github.io/)          |GTFOBins is a curated list of Unix binaries that can be used to bypass local security restrictions in misconfigured systems.

📚 Bases de données de vulnérabilités
--------------------------------------
Site                                    | Utilité
----------------------------------------|---------------------------------------------------------------
[Nist](https://nvd.nist.gov/)                   | CVE officiel (failles connues référencées)
[Exploit-DB](https://www.exploit-db.com)              | Exploits publics, scripts, failles par logiciel
[Vulners](https://vulners.com)                     | Moteur de recherche d’exploits/CVE, API dispo
[CVEDetails](https://cvedetails.com)                  | Recherche de failles par version de logiciel

💀 Pratique / Entraînement
---------------------------
Site                                    | Utilité
----------------------------------------|---------------------------------------------------------------
[TryHackMe](https://tryhackme.com)                   | Labs interactifs guidés pour tous niveaux
[HackTheBox](https://hackthebox.com)                  | Machines virtuelles à compromettre, du facile au hard
[VulnHub](https://vulnhub.com)                     | VMs vulnérables à télécharger et exploiter en local
[PicoCTF](https://picoctf.org)                     | Challenges CTF pour débutants / lycéens / étudiants
[Root-Me](https://root-me.org)                     | Enorme collection de challenges variés (Web, Crypto, etc.)

🧠 Références & Cheat Sheets
-----------------------------
Site                                    | Utilité
----------------------------------------|---------------------------------------------------------------
[GTFOBins](https://gtfobins.github.io/)             | Privesc via binaires Linux sudo ou suid
[HackTricks](https://book.hacktricks.xyz)             | Guide complet sur pentest, exploitation et privesc
[Payloads ALl The Things](https://payloadsallthethings.com)        | Payloads pour toutes les failles et cas (XSS, LFI, etc.)
[PentestMonkey](https://pentestmonkey.net/)              | Cheatsheets pratiques (reverse shell, SQLi, etc.)

🕸️ Analyse Web & Sécurité
---------------------------
Site                                    | Utilité
----------------------------------------|---------------------------------------------------------------
[SecurityHeaders](https://securityheaders.com)             | Analyse des headers HTTP de sécurité
[Shodan](https://shodan.io)                       | Moteur de recherche d’équipements exposés
[Censys](https://censys.io)                       | Alternative à Shodan pour l’OSINT et l’analyse réseau
