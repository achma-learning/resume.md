# Workflow — Résumés de topos médicaux (fusion 3 sources)

## Objectif

Produire, pour chaque sujet d'examen, un fichier `.md` prêt à l'emploi dans le vault Obsidian, structuré selon le squelette [`+++topo-plan.md`](./+++topo-plan.md) et exploitable pour la révision active (QCM, cas clinique, mnémotechniques).

## Sources (par ordre de priorité)

1. **Transcription du cours** (`Transcribe-data/S[n]-[matière]/*.txt`)
   → colonne vertébrale pédagogique : logique du prof, pearls cliniques, axes d'examen.
   → **Attention** : erreurs de transcription fréquentes (ex. *transhumination* → transillumination, *hyperostème* → hydrocèle). À corriger systématiquement.

2. **PDF mis à jour** (upload local ou lien Google Drive)
   → données corrigées, figures, chiffres, guidelines actuelles.
   → **écrase** la transcription en cas de divergence factuelle.

3. **Sources crédibles web** (recomedicales.fr, Collèges français, PNDS, HAS, sociétés savantes)
   → couche d'arbitrage : confirme les recommandations actuelles quand (1) et (2) divergent ou datent.

## Règle de fusion

```
transcription  →  structure + emphase examen
     +
PDF mis à jour →  override des données factuelles
     +
web crédible   →  mise à jour des recommandations
     =
fichier .md final
```

## Workflow par session

### Phase 1 — Un seul topo par session
Pas de batch. Chaque sujet mérite une synthèse focalisée. Commencer par les topos à haut rendement ou ceux dont la transcription est la plus complète.

### Phase 2 — Fournir les sources à Claude, dans cet ordre
1. Indiquer le chemin de la transcription (`Transcribe-data/...`) ou l'uploader.
2. Uploader le PDF mis à jour (ou coller le lien Drive).
3. Préciser si un cross-check web est demandé, et sur quels points (ex. "dernière reco SFCE sur tumeurs osseuses").

### Phase 3 — Synthèse par Claude
- Extraction depuis la transcription avec correction des coquilles évidentes.
- Intégration / override via le PDF.
- Cross-reference web sur les points signalés.
- Remplissage **intégral** des sections du `+++topo-plan.md`.
- Ajout systématique : QCM, cas clinique, moyens mnémotechniques.

### Phase 4 — Revue et itération
L'utilisateur relit, signale manques / erreurs, Claude corrige. Itérer jusqu'à validation.

## Lancer une session

Copier le contenu de [`prompt-resume.txt`](./prompt-resume.txt), remplir les placeholders `[TOPIC]`, `[TRANSCRIPTION_PATH]`, `[PDF]`, puis coller.

Exemple rapide :

> « Claude, fais-moi le résumé de **[Pathologie du CPV]**. Voici le PDF mis à jour. Utilise la transcription du projet + sources crédibles pour les données actualisées. »

## Destination du fichier produit

Selon le semestre et la matière :
- Chirurgie pédiatrique S7 → `s7/ped-chir/`
- Pharma S5 → `s5/pharma/`
- Gastro S6 → `s6/gastro/`
- Anapath / MPR / Traumato / Génétique S8 → `s8/<sous-dossier>/`

## Suivi

La liste des topos à traiter est suivie dans les **GitHub issues** du dépôt `achma-learning/resume.md` sous forme de checklist (une issue par module, ex. *pediatric surgery S7*).
