# Active Directory Red Team Report 

**Auteur**: Libasse | INSA LYON - PENTEST/BLUE TEAM PROFIL
**Type**: Projet pédagogique / laboratoire Red Team  
**Objectif**: Documenter et reproduire un scénario complet d’attaque Active Directory: reconnaissance, exploitation Kerberos, élévation de privilèges, extraction NTDS et persistance. Le dépôt inclut le rapport converti en Markdown, commandes reproductibles et playbooks de remédiation.

> **Avertissement**: Les techniques documentées sont dangereuses et illégales hors d'un environnement autorisé. Ce dépôt est destiné à un usage pédagogique et doit rester dans un environnement contrôlé.

---

## Contenu du dépôt

- `docs/report.md` — Rapport complet converti en Markdown (anonymiser avant publication publique).  
- `remediation/` — Plan de remédiation priorisé et playbooks opérationnels.  
- `scripts/` — Scripts d'aide pour générer PDF et préparer une release.  
- `.github/workflows/render-report.yml` — Workflow GitHub Actions pour générer un PDF à partir du Markdown.  
- `CONTRIBUTING.md` — Règles de contribution, anonymisation et validation.  
- `LICENSE` — Licence MIT.

---

## Résumé exécutif (1 ligne)
Rapport pédagogique et reproductible d’un audit Active Directory (GOAD) : reconnaissance, Kerberoasting, AS‑REP Roasting, délégations Kerberos, DCSync, Pass‑the‑Hash, Golden Ticket, et plan de remédiation.

---

## Usage rapide

1. Cloner le dépôt  
   `git clone https://github.com/Libasse/active-directory-red-team-report.git`  
2. Lire le rapport  
   `less docs/report.md`  
3. Générer le PDF (local)  
   `./scripts/build_pdf.sh`  
4. Respecter les consignes de sécurité : anonymiser IPs, supprimer dumps NTDS, ne pas publier hashes ou credentials.

---

## Badges & topics recommandés
**Topics**: `active-directory`, `red-team`, `pentest`, `kerberos`, `bloodhound`, `goad`, `vagrant`, `virtualbox`  
**Licence**: MIT

---

## Comment contribuer
Voir `CONTRIBUTING.md`. Toute contribution doit respecter l’anonymisation et ne pas inclure d’artefacts sensibles (hashes, dumps, mots de passe).

