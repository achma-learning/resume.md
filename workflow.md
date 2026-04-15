# Workflow — Résumés de topos médicaux (fusion 3 sources)

## Objectif

Produire, pour chaque sujet d'examen, un fichier `.md` prêt à l'emploi dans le vault Obsidian, structuré selon le squelette [`+++topo-plan.md`](./+++topo-plan.md) et exploitable pour la révision active (QCM, cas clinique, moyens mnémotechniques).

Ce workflow s'applique à **toutes les matières de l'externat FMPM Marrakech** — chirurgie pédiatrique, pharmacologie, gastro-entérologie, anapath, MPR, traumatologie, génétique, etc. — et non au seul module S7.

## Sources (par ordre de priorité)

1. **Transcription du cours** (`Transcribe-data/S[n]-[matière]/*.txt`)
   → colonne vertébrale pédagogique : logique du prof, pearls cliniques, axes d'examen.
   → **Attention** : erreurs de transcription fréquentes (ex. *transhumination* → transillumination, *hyperostème* → hydrocèle, *scrotom* → scrotum). À corriger systématiquement.

2. **PDF mis à jour** (upload local ou lien Google Drive / URL)
   → données corrigées, figures, chiffres, guidelines actuelles.
   → **écrase** la transcription en cas de divergence factuelle.
   → l'URL du PDF fournie par l'utilisateur **doit être reportée en bas de la fiche** dans la section *Sources*.

3. **Sources crédibles web** (recomedicales.fr, Collèges français — CFCOT, SFCE, GFHGNP, SNFGE, CEP, etc. —, PNDS, HAS, sociétés savantes, UpToDate si accessible)
   → couche d'arbitrage : confirme les recommandations actuelles quand (1) et (2) divergent ou datent.
   → **chaque URL consultée est citée en bas de la fiche** dans la section *Sources*.

## Règle de fusion

```
transcription  →  structure + emphase examen
     +
PDF mis à jour →  override des données factuelles
     +
web crédible   →  mise à jour des recommandations
     =
fichier .md final + bloc "Sources" (liens PDF + URLs web)
```

## Workflow par session

### Phase 1 — Un seul topo par session
Pas de batch. Chaque sujet mérite une synthèse focalisée. Commencer par les topos à haut rendement d'examen ou ceux dont la transcription est la plus complète.

### Phase 2 — Fournir les sources à Claude, dans cet ordre
1. Indiquer le chemin de la transcription (`Transcribe-data/...`) ou l'uploader.
2. Uploader le PDF mis à jour **ou coller son URL** (Google Drive, Drive partagé, lien institutionnel). Toute URL fournie sera conservée et inscrite en bas de la fiche.
3. Préciser si un cross-check web est demandé, et sur quels points (ex. *« dernière reco SFCE sur tumeurs osseuses »*).

### Phase 3 — Synthèse par Claude
- Extraction depuis la transcription avec correction des coquilles évidentes.
- Intégration / override via le PDF.
- Cross-reference web sur les points signalés.
- Remplissage **intégral** des sections du `+++topo-plan.md`.
- Ajout systématique : QCM, cas clinique, moyens mnémotechniques.
- **Bloc *Sources* en bas de la fiche** listant, avec URL cliquable :
  - le PDF de cours (si URL fournie),
  - chaque source web consultée (recomedicales, Collège, PNDS, HAS, etc.),
  - le chemin de la transcription utilisée.

### Phase 4 — Revue et itération
L'utilisateur relit, signale manques / erreurs, Claude corrige. Itérer jusqu'à validation, puis déposer la fiche dans le vault.

## Lancer une session

Copier le contenu de [`prompt-resume.txt`](./prompt-resume.txt), remplir les placeholders `[TOPIC]`, `[TRANSCRIPTION_PATH]`, `[PDF_URL_OR_UPLOAD]`, `[WEB_SOURCES]`, puis coller dans une nouvelle session.

Exemple rapide :

> « Claude, fais-moi le résumé de **[Pathologie du CPV]**. Voici le PDF mis à jour (lien : `https://drive.google.com/...`). Utilise la transcription `Transcribe-data/S7-ped-chir/kamili-cpv.txt` + sources crédibles (recomedicales.fr, CFCOT) pour les données actualisées. »

## Destination du fichier produit

Selon le semestre et la matière :
- Chirurgie pédiatrique S7 → `s7/ped-chir/`
- Pharmacologie S5 → `s5/pharma/`
- Gastro-entérologie S6 → `s6/gastro/`
- Anapath / MPR / Traumatologie / Génétique S8 → `s8/<sous-dossier>/`
- Autres matières → suivre la convention `s[n]/<matière>/`.

## Nommage

- Un fichier `.md` par topo, nommé `[Nom du sujet].md` (diacritiques autorisés).
- La première ligne utile du fichier peut contenir un commentaire HTML :
  `<!-- suggested filename: [topic-slug].md -->`

## Suivi

La liste des topos à traiter est suivie dans les **GitHub issues** du dépôt `achma-learning/resume.md` sous forme de checklist (une issue par module, ex. *pediatric surgery S7*). Chaque fiche validée est cochée.

---
*Workflow — version élargie, 15 avril 2026.*
