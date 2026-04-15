# Workflow de synthèse – Résumés de cours prêts pour l'externat marocain

## Objectif
Produire pour chaque sujet de chirurgie pédiatrique (S7) une fiche `.md` complète, rigoureuse et prête à être intégrée dans un coffre Obsidian.
La fiche doit servir de support d'étude efficace pour l'examen (QCM, cas cliniques, moyens mnémotechniques) et être basée sur une fusion fiable de trois sources :

1. **Transcriptions des cours du professeur** (`Transcribe-data/`) → squelette pédagogique officiel.
2. **PDFs de cours actualisés** (uploads locaux ou Google Drive) → données et figures corrigées.
3. **Sources web fiables** (recomedicales.fr, Collèges, PNDS) → recommandations actuelles.

Ce workflow a été validé sur la fiche *Sténose hypertrophique du pylore* et doit être répliqué pour les autres sujets.

## Sources – Ordre de priorité
Lors de la synthèse, les sources sont utilisées dans l'ordre suivant :

| Priorité | Source | Rôle |
|----------|--------|------|
| 1 | **Transcription du professeur** | Structure du cours, plan, points d'insistance de l'enseignant. |
| 2 | **PDF de cours actualisé** | Données chiffrées, imagerie, schémas ; **corrige** les éventuelles erreurs de transcription. |
| 3 | **Sources web (recomedicales, Collège, PNDS)** | Mise à jour des recommandations, chiffres récents, confirmation de la conduite à tenir. |

## Phase 1 – Un sujet par session
- **Ne pas traiter plusieurs sujets à la fois**.
- Chaque session Claude est dédiée à **un seul sujet** de chirurgie pédiatrique.
- Cela garantit une synthèse profonde et évite les confusions.
- Commencer par les sujets à haut rendement pour l'examen ou ceux dont la transcription est la plus complète.

## Phase 2 – Alimentation des sources dans l'ordre
Au début de la session, fournir à Claude **dans cet ordre précis** :

1. **Le chemin du fichier de transcription** (ex : `Transcribe-data/Invagination_intestinale_aiguë_Kamili.txt`).
2. **Le PDF actualisé** (uploadé directement dans l'interface ou via un lien Google Drive).
3. **Les sources web** (URLs de Recomedicales, Collège concerné, PNDS).

L'instruction donnée à Claude doit lui rappeler de **lire et intégrer les sources selon les règles de priorité**.

## Phase 3 – Règles de synthèse
Claude doit appliquer les règles suivantes lors de la rédaction de la fiche `.md` :

- **Corriger les erreurs de transcription évidentes**
  *Exemples :* « transhumination » → *transillumination* ; « hyperostème » → *hydrocèle* ; « échographie montre une cible » → *image en cocarde*.
- **Le PDF de cours prime sur la transcription** pour les données chiffrées et les figures.
- **Les sources web (Recomedicales, PNDS) servent de vérification finale** pour les recommandations thérapeutiques récentes.
- **Le squelette obligatoire est `+++topo-plan.md`** : chaque section doit être remplie sans exception (Introduction, Épidémiologie, Physiopathologie, Diagnostic, Traitement, etc.).
- **Ajouter systématiquement** :
  - Un **QCM** avec 3 à 5 questions typiques de l'externat.
  - Un **cas clinique** court avec question et réponse détaillée.
  - Des **moyens mnémotechniques** pour retenir les points clés.

## Phase 4 – Relecture et itération
- Après réception de la fiche, **vérifier visuellement** les corrections apportées aux erreurs de transcription.
- Si nécessaire, relancer Claude avec une instruction ciblée (ex : « Précise la CAT selon le PNDS 2023 »).
- Une fois satisfait, la fiche est **stockée dans le dossier `s7/ped-chir/`** et prête pour l'import dans Obsidian.

## Lancement rapide d'une session
Pour démarrer une nouvelle fiche, utiliser le prompt suivant (le template complet se trouve dans `prompt-resume.txt`) :

> *Claude, applique le workflow de synthèse pour le sujet [NOM_DU_SUJET]. Utilise la transcription [CHEMIN], le PDF fourni et les sources web [URLS]. Rédige la fiche `.md` complète selon `+++topo-plan.md`, en corrigeant les erreurs de transcription et en ajoutant QCM, cas clinique et mnémotechniques. Langue : français médical de l'externat marocain. Aucun commentaire hors fiche.*

## Emplacement des fiches produites
- **Dossier cible** : `s7/ped-chir/`
- **Nom du fichier** : `[Nom_du_sujet].md` (ex : `Invagination_intestinale_aiguë.md`)

## Suivi des sujets
Le suivi des fiches restant à produire est assuré via une **GitHub Issue de checklist** dans le dépôt `achma-learning/resume.md`.

---
*Workflow documenté le 15 avril 2026 – validé sur SHP.*
