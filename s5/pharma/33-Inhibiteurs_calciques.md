---
type: topo-plan
titre: "Les Inhibiteurs Calciques"
date: "2026-04-14"
module: "[[Pharmacologie]]"
matiere: "Pharmacologie cardiovasculaire"
enseignant: "Pr. BENDRISS"
specialite: "[[Cardiologie]]"
semestre: S2
annee: 2025-2026
statut: brouillon
revision: 0
urgence: false
tags:
  - pharmacologie
  - cardiovasculaire
  - inhibiteurs-calciques
  - antihypertenseur
  - antiangoreux
aliases:
  - antagonistes calciques
  - bloqueurs canaux Ca2+
cssclasses:
  - medical-note
created: "2026-04-14T00:00"
modified: "2026-04-14T00:00"
---

# Les Inhibiteurs Calciques

> [!info] Métadonnées
> **Module** : [[Pharmacologie]] · **Spécialité** : [[Cardiologie]]
> **Enseignant** : Pr. BENDRISS · **Statut** : 🔴 Brouillon → 🟡 Révisé → 🟢 Maîtrisé

---

## I. Introduction

> [!abstract] Objectifs pédagogiques
> 1. Distinguer les deux grandes sous-classes d'inhibiteurs calciques (DHP vs non-DHP)
> 2. Connaître leurs indications spécifiques et leurs contre-indications
> 3. Comprendre les différences d'effets cardiaques entre les deux sous-classes

- Les **inhibiteurs calciques** (IC) bloquent les canaux calciques voltage-dépendants de type **L** (Long-lasting)
- **Deux sous-classes aux profils très différents** : dihydropyridines (DHP) et non-dihydropyridines (non-DHP)

---

## II. Rappels physiologiques

- Le **Ca²⁺** est un messager secondaire essentiel :
  - **Muscle lisse vasculaire** : Ca²⁺ + calmoduline → activation myosine kinase → **contraction** (vasoconstriction)
  - **Cardiomyocyte** : Ca²⁺ = couplage excitation-contraction → force systolique
  - **Nœud sinusal / NAV** : Ca²⁺ = dépolarisation lente (phase 0) → **automatisme** et **conduction**

- **Canaux calciques L** : présents dans vaisseaux, myocarde et tissu nodal
- Inhiber ces canaux → vasodilatation + effets cardiaques variables selon la sélectivité

---

## III. Classification

```mermaid
graph TD
    A[Inhibiteurs calciques\n(bloqueurs canaux Ca2+ type L)] --> B[Dihydropyridines\nDHP]
    A --> C[Non-Dihydropyridines\nNon-DHP]
    B --> D["Amlodipine, Nifédipine\nLercarnidipine, Félodipine\nNicardipine, Nimodipine"]
    C --> E["Vérapamil (phénylalkylamine)\nDiltiazem (benzothiazépine)"]
    D --> F["Sélectivité vasculaire ++\n(peu d'effet cardiaque)"]
    E --> G["Action vasculaire +\nAction cardiaque ++"]
    style D fill:#4ecdc4,color:#000
    style E fill:#ff6b6b,color:#fff
```

---

## IV. Dihydropyridines (DHP)

### A. Caractéristiques

- **Sélectivité vasculaire** : agissent préférentiellement sur le muscle lisse vasculaire
- **Effets cardiaques directs** : faibles (peu d'effet chronotrope/dromotrope)
- **Effet réflexe** : la vasodilatation → ↓ PA → réflexe sympathique → **tachycardie réflexe** (surtout avec les DHP d'action courte)

### B. Principaux DHP

| DCI | Demi-vie | Particularités |
|-----|----------|----------------|
| **Amlodipine** | 30-50h | Longue durée d'action, 1 prise/j, référence HTA |
| **Nifédipine LP** | 6-12h | Forme LP obligatoire (forme courte = CI) |
| **Lercarnidipine** | 8-10h | Très sélectivité vasculaire, moins d'œdèmes |
| **Félodipine LP** | 11-16h | Similaire à amlodipine |
| **Nicardipine IV** | 6-8h | Voie IV en urgences hypertensives |
| **Nimodipine** | 1-2h | Spécifique : vasospasme cérébral post-HSA |

### C. Effets indésirables DHP

> [!warning] EI DHP
> - **Œdèmes des membres inférieurs** ★ : vasodilatation capillaire (pas de rétention hydrosodée) → résistant aux diurétiques, ↓ en surélevant les jambes
> - **Flush, céphalées, érythème** : vasodilatation cutanée
> - **Tachycardie réflexe** : surtout formes d'action courte → CI nifédipine courte dans l'angor
> - **Gingival hyperplasia** (surtout nifédipine)

---

## V. Non-Dihydropyridines

### A. Vérapamil

- **Classe** : phénylalkylamine
- **Sélectivité** : cardiaque ++ (nœud SA, nœud AV, myocarde) ET vasculaire
- **Effets pharmacologiques** :
  - **Chronotrope négatif** : ↓ FC (dépression nœud sinusal)
  - **Dromotrope négatif** : ↓ conduction NAV → allongement PR
  - **Inotrope négatif** modéré
  - **Vasodilatateur** artériel
- **Indications** :
  - HTA (si CI bêtabloquants)
  - Tachyarythmies supraventriculaires (flutter, FA à cadence rapide, TSV)
  - Angor (surtout vasospastique)
  - Migraine (prophylaxie)
- **EI** : bradycardie, BAV, constipation (++ spécifique du vérapamil), IC décompensée

> [!danger] CI absolues vérapamil
> - **Association avec bêtabloquants** : risque de BAV complet et arrêt sinusal (bradycardie + bloc AV additifs)
> - **IC à FE réduite** : inotrope négatif → décompensation
> - **Syndrome de WPW** : risque de TV ventriculaire par accélération de la conduction accessoire

### B. Diltiazem

- **Classe** : benzothiazépine
- **Profil** : intermédiaire entre DHP et vérapamil
  - Effets cardiaques présents mais moins marqués que vérapamil
  - Effets vasculaires présents mais moins que DHP
- **Indications** :
  - HTA
  - Angor stable et vasospastique
  - Tachyarythmies supraventriculaires (contrôle de fréquence FA)
- **EI** : bradycardie, BAV (moins que vérapamil), flush
- **CI** : association avec bêtabloquants (même que vérapamil)

---

## VI. Tableau comparatif

| Propriété | DHP (amlodipine) | Vérapamil | Diltiazem |
|-----------|-----------------|-----------|-----------|
| Vasodilatation | +++ | ++ | ++ |
| Chronotrope négatif | 0 (tachycardie réflexe) | +++ | ++ |
| Dromotrope négatif | 0 | +++ | ++ |
| Inotrope négatif | 0-+ | ++ | + |
| Indication arythmies | **Non** | **Oui** | **Oui** |
| CI avec bêtabloquants | Non | **Oui absolue** | **Oui absolue** |

---

## VII. Indications résumées

| Indication | Choix |
|-----------|-------|
| HTA simple | Amlodipine (DHP) |
| HTA + angor | DHP LP ou diltiazem |
| HTA + bradycardie / BBG | DHP (pas de non-DHP) |
| Angor vasospastique | DHP ou vérapamil/diltiazem |
| Contrôle fréquence FA | Vérapamil ou diltiazem |
| Vasospasme cérébral (HSA) | Nimodipine (DHP) |
| Urgence hypertensive | Nicardipine IV |

---

## VIII. Contre-indications communes

| CI | DHP | Non-DHP |
|----|-----|---------|
| IC à FE réduite | Non (amlodipine tolérée) | Oui (sauf amlodipine/félodipine) |
| BAV 2-3 | Oui | Oui |
| Association bêtabloquant | Non (acceptable) | **Oui** (CI absolue) |
| Choc cardiogénique | Oui | Oui |

---

## Zone de révision active

> [!question] Questions de synthèse
> **Q1** : Pourquoi les DHP provoquent-elles une tachycardie réflexe mais pas les non-DHP ?
> **R1** : Les DHP sont sélectives vasculaires → vasodilatation → ↓ PA → activation réflexe barorécepteurs → tachycardie sympathique réflexe. Les non-DHP ont un effet chronotrope négatif direct qui contrebalance cette réponse réflexe.
>
> **Q2** : Pourquoi l'association vérapamil + bêtabloquant est-elle contre-indiquée ?
> **R2** : Addition des effets chronotropes et dromotropes négatifs → bradycardie sévère, BAV complet voire arrêt sinusal.
>
> **Q3** : Quel inhibiteur calcique utilise-t-on pour le vasospasme cérébral post-HSA ?
> **R3** : Nimodipine (DHP à sélectivité cérébrale).
>
> **Q4** : Quel est l'effet indésirable typique du vérapamil absent avec les autres IC ?
> **R4** : Constipation (ralentissement de la motricité intestinale par blocage des canaux Ca²⁺ des cellules musculaires lisses intestinales).

> [!note] Mnémotechnique
> **DHP** = **D**ilatent principalement les **H**yperéactifs vaisseaux **P**ériphériques (pas de bradycardie)
> **Véra**pamil = **Véra**iment bradycardisant + constipant + **V**alve NAV bloquée

---

> [!success] Points tombables à l'examen ⭐
> - DHP = sélectivité vasculaire → tachycardie réflexe → OK si bradycardie chronique
> - Non-DHP (vérapamil, diltiazem) = effet cardiaque (bradycardie, BAV) → utilité en arythmie
> - CI absolue : association **non-DHP + bêtabloquant** (BAV fatal)
> - Vérapamil EI spécifique = **constipation**
> - Nimodipine = vasospasme cérébral post-hémorragie sous-arachnoïdienne
> - IC à FE réduite : seules amlodipine et félodipine (DHP) sont tolérées
> - WPW + FA : CI vérapamil et diltiazem (masquent la FA mais accélèrent la conduction accessoire)

---

## Liens

- **Voir aussi** : [[34-Beta_bloquants]] · [[31-Bloqueurs_SRAA]] · [[35-Anti_angoreux]]
- **Pathologies** : [[HTA]] · [[Angor]] · [[Fibrillation auriculaire]]
- **Référentiel** : [[ESC Guidelines 2023]] · [[VIDAL]]

---

*Dernière révision : 2026-04-14*
