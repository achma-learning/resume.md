---
type: topo-plan
titre: "Traitement de la maladie ulcéreuse gastroduodénale"
date: "2026-04-14"
module: "[[Pharmacologie]]"
matiere: "Pharmacologie digestive"
enseignant: "Pr. SAMLANI"
specialite: "[[Gastro-entérologie]]"
semestre: S2
annee: 2025-2026
statut: brouillon
revision: 0
urgence: true
urgence_type: "Hémorragie digestive sur ulcère"
tags:
  - pharmacologie
  - digestif
  - ulcere
  - IPP
  - helicobacter
  - antiulcereux
aliases:
  - IPP
  - ulcère gastrique
  - ulcère duodénal
  - Helicobacter pylori
cssclasses:
  - medical-note
created: "2026-04-14T00:00"
modified: "2026-04-14T00:00"
---

# Traitement de la maladie ulcéreuse gastroduodénale

> [!info] Métadonnées
> **Module** : [[Pharmacologie]] · **Spécialité** : [[Gastro-entérologie]]
> **Enseignant** : Pr. SAMLANI · **Statut** : 🔴 Brouillon → 🟡 Révisé → 🟢 Maîtrisé

---

## I. Introduction

> [!abstract] Objectifs pédagogiques
> 1. Comprendre la physiopathologie de l'ulcère et le rôle de H. pylori
> 2. Maîtriser le mécanisme des IPP et leurs indications majeures
> 3. Connaître les protocoles d'éradication de H. pylori

> [!example] Vignette clinique
> *Homme de 45 ans, stress professionnel intense, AINS pour lombalgie, brûlures épigastriques à jeun calmées par l'alimentation. FOGD : ulcère duodénal actif. Biopsies : H. pylori +.*
> **Traitement ?**

- **Ulcère gastro-duodénal (UGD)** : perte de substance de la muqueuse gastrique ou duodénale dépassant la muscularis mucosae
- **Causes principales** : H. pylori (70-90% des UD, 60-80% des UG) + AINS/aspirine

---

## II. Physiopathologie — Balance agression/protection

```mermaid
graph LR
    A[AGRESSIONS] --> C{Déséquilibre}
    B[PROTECTIONS] --> C
    A --- A1[H. pylori\nAINS\nAspirin\nAlcool\nTabac\nStress]
    B --- B1[Mucus\nBicarbonates\nPGE2 (prostaglandines)\nVascularisation\nRenouvellement épithélial]
    C -->|Agressions > Protections| D[ULCÈRE]
    style D fill:#ff6b6b,color:#fff
```

---

## III. Médicaments Anti-Sécrétoires

### A. Inhibiteurs de la Pompe à Protons (IPP) ★★★

> [!important] Mécanisme des IPP
> **Prodrogue** activée en milieu acide → **sulfénamide** → liaison **covalente irréversible** à la H+/K+ ATPase (pompe à protons) des cellules pariétales gastriques → **↓↓↓ sécrétion acide** (jusqu'à 90-95%)

**Principaux IPP :**

| DCI | Demi-vie | Particularités |
|-----|----------|----------------|
| **Oméprazole** | 1h | 1er IPP, référence, interactions CYP2C19 |
| **Pantoprazole** | 1h | Moins d'interactions, IV disponible |
| **Esoméprazole** | 1-1,5h | Énantiomère S de l'oméprazole, efficacité ++ |
| **Lanzoprazole** | 1-2h | |
| **Rabéprazole** | 1h | Moins dépendant du CYP2C19 |

> [!tip] Règles de prise
> - Prendre **30 min avant le repas** (la pompe doit être active pour que l'IPP soit efficace)
> - **Matin de préférence**
> - Les IPP sont des prodrogues → activées in situ dans le canalicule sécrétoire

**Effets indésirables des IPP :**

| EI | Mécanisme | Commentaire |
|----|-----------|-------------|
| **↓ Magnésium** (si >1 an) | ↓ absorption Mg2+ | Surveiller Mg²⁺ si traitement long |
| **↓ B12** (si >3 ans) | ↓ acidité → ↓ libération B12 | |
| **↓ Absorption fer, calcium** | Acidité nécessaire | Ostéoporose à long terme |
| **Infections digestives** | ↓ acidité = ↓ barrière anti-infectieuse | Risque C. difficile ↑, pneumonies |
| **↑ Gastrine** réactionnelle | Réponse à l'hypochlorhydrie | Hyperplasie des cellules ECL |
| **Néphrite interstitielle** | Réaction idiosyncrasique | Rare |
| **Interaction clopidogrel** | Oméprazole inhibe CYP2C19 → ↓ activation clopidogrel | Utiliser pantoprazole ou rabéprazole |

### B. Anti-H2 (Antihistaminiques H2)

- **Mécanisme** : blocage compétitif des récepteurs H2 de l'histamine sur les cellules pariétales → ↓ sécrétion acide (moins puissant que les IPP ~70%)
- **DCI** : ranitidine (retirée du marché en 2020 — NDMA), **famotidine** (Pepcidine®), cimétidine
- **Place** : 2ème ligne (si CI aux IPP), prévention des ulcères de stress, traitement d'appoint RGO
- **EI cimétidine** : inhibiteur enzymatique puissant (CYP1A2, CYP2C9, CYP3A4) → nombreuses interactions ; anti-androgène (gynécomastie)
- **Tolérance** : tachyphylaxie (réduction d'effet en cas d'utilisation prolongée)

---

## IV. Médicaments Protecteurs de la Muqueuse

### A. Misoprostol (analogue des prostaglandines PGE1)

- **Mécanisme** : ↑ mucus, ↑ bicarbonates, ↑ vascularisation muqueuse + ↓ sécrétion acide
- **Indication** : **prévention des ulcères aux AINS** (surtout chez personnes âgées à risque)
- **EI** : diarrhées, crampes abdominales, **abortif** (CI grossesse — mais utilisé en gynécologie obstétrique pour cette propriété)

### B. Sucralfate

- **Mécanisme** : polymère d'aluminium → se lie aux protéines ulcéreuses dénaturées → **barrière protectrice** + stimulation mucus/PGE2
- **Utilisation** : en milieu acide (prendre à distance des IPP), 1h avant les repas
- **EI** : constipation, diminue absorption d'autres médicaments (↓ biodisponibilité si prise simultanée)
- **CI** : IRC (aluminium absorbé en faible quantité → accumulation)

### C. Sels de bismuth

- **Mécanisme** : protecteur muqueux + activité anti-H. pylori
- **Utilisation** : quadrithérapie anti-H. pylori

---

## V. Helicobacter pylori — Éradication ★★★

### A. Pourquoi éradiquer ?

- **Éradication = guérison définitive de l'ulcère** dans la grande majorité des cas
- ↓ Risque de récidive de 80-90% → 5%
- ↓ Risque d'adénocarcinome gastrique et de lymphome MALT

### B. Protocoles d'éradication

> [!important] Schémas d'éradication (HAS 2017)

**1ère ligne : Quadrithérapie bismuthée (10-14 jours)**

| Médicament | Posologie |
|-----------|----------|
| IPP (oméprazole ou ésoméprazole) | 20-40 mg × 2/j |
| Bismuth (sous-citrate) | 140 mg × 4/j |
| Métronidazole | 500 mg × 3/j |
| Tétracycline (doxycycline) | 500 mg × 3/j |

**Alternative 1ère ligne : Trithérapie concomitante (10 jours)**

| Médicament | Posologie |
|-----------|----------|
| IPP | 20-40 mg × 2/j |
| Amoxicilline | 1 g × 2/j |
| Clarithromycine OU Métronidazole | 500 mg × 2/j |

**2ème ligne si échec :**

```mermaid
flowchart TD
    A[Échec 1ère ligne] --> B[Bilan de résistances\n(culture + antibiogramme si possible)]
    B --> C[Quadrithérapie bismuthée\nsi non utilisée en 1ère ligne]
    B --> D[Lévofloxacine + Amoxicilline + IPP\n(si résistance clarithromycine)]
    C & D --> E[Contrôle éradication\nà 4 semaines (test respiratoire)]
```

### C. Contrôle d'éradication

- **Test respiratoire à l'urée marquée (13C)** : gold standard en pratique (non invasif)
- À réaliser **≥ 4 semaines** après fin du traitement, **en dehors des IPP** (arrêt 2 semaines avant)
- Alternative : antigène H. pylori dans les selles

---

## VI. Stratégie globale — Ulcère gastroduodénal

```mermaid
flowchart TD
    A[Ulcère gastro-duodénal confirmé\npar FOGD] --> B{H. pylori ?}
    B -->|Positif| C[Triple/Quadruple thérapie\néradication H. pylori\n+ IPP 4-8 semaines]
    C --> D[Contrôle éradication\nTest respiratoire à 4 semaines]
    D --> E{Éradicaton réussie ?}
    E -->|Oui| F[IPP non systématique\nsauf facteurs de risque]
    E -->|Non| G[2ème ligne d'éradication]
    B -->|Négatif| H[AINS / Aspirine ?]
    H -->|Oui| I[Arrêt AINS + IPP 4-8 sem\nSi AINS indispensable : misoprostol ou IPP]
    H -->|Non| J[IPP + bilan étiologique\n(Zollinger-Ellison, Crohn...)]
```

---

## VII. Syndrome de Zollinger-Ellison

- **Cause** : gastrinome (tumeur neuroendocrine) → ↑↑ gastrine → ↑↑ sécrétion acide → ulcères multiples, atypiques, résistants
- **Traitement** : IPP fortes doses en continu

---

## Zone de révision active

> [!question] Questions de synthèse
> **Q1** : Pourquoi prendre les IPP 30 min avant le repas ?
> **R1** : Les IPP sont des prodrogues activées en milieu acide dans les canalicules sécrétoires des cellules pariétales. Ces pompes ne sont actives que lors de la stimulation par le repas. Prise 30 min avant → activation maximale des pompes lors du pic sécrétoire.
>
> **Q2** : Quel anti-H2 a des propriétés anti-androgènes ?
> **R2** : Cimétidine → gynécomastie, impuissance (effet anti-androgène non spécifique).
>
> **Q3** : Quelle est la complication spécifique à long terme de l'oméprazole sur le bilan ionique ?
> **R3** : Hypomagnésémie (surtout si > 1 an de traitement), pouvant provoquer hypocalcémie secondaire et arythmies.
>
> **Q4** : Pourquoi ne pas associer oméprazole et clopidogrel ?
> **R4** : Oméprazole inhibe le CYP2C19 → ↓ activation du clopidogrel (prodrogue) → ↓ effet antiagrégeant → risque de thrombose. Utiliser pantoprazole ou rabéprazole.

> [!note] Mnémotechnique
> **IPP** = "**I**nhibent la **P**ompe **P**arfaitement" mais : **B**12, **Mg**, **Fe** absorbés moins bien avec le temps

---

> [!success] Points tombables à l'examen ⭐
> - IPP = prodrogue activée en milieu acide → liaison covalente irréversible à H+/K+ ATPase
> - Prise 30 min avant le repas (obligatoire pour l'efficacité)
> - H. pylori : éradication = guérison de l'ulcère + ↓ risque cancer gastrique
> - Contrôle éradication : test respiratoire à l'urée 13C (4 semaines après fin traitement)
> - Ranitidine retirée du marché en 2020 (NDMA cancérogène)
> - Interaction oméprazole + clopidogrel → utiliser pantoprazole
> - EI long terme IPP : ↓ Mg, ↓ B12, ↓ Ca, ↑ risque infections digestives (C. difficile)
> - Misoprostol = prévention ulcères aux AINS mais CI grossesse (abortif)
> - Quadrithérapie bismuthée = 1ère ligne éradication H. pylori en France (depuis 2017)

---

## Liens

- **Voir aussi** : [[36-Laxatifs]] · [[27-Antitussifs]] · [[28-Antiagregants_plaquettaires]]
- **Pathologies** : [[Ulcère gastro-duodénal]] · [[RGO]] · [[H. pylori]]
- **Référentiel** : [[HAS 2017]] · [[SNFGE]] · [[VIDAL]]

---

*Dernière révision : 2026-04-14*
