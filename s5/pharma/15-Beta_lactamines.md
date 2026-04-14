---
type: topo-plan
titre: "Les Bêta-Lactamines"
date: "{{date}}"
module: "[[Pharmacologie]]"
matiere: "Pharmacologie"
enseignant: "Pr. TASSI"
semestre: 1
annee: 2025-2026
statut: brouillon
revision: 0
tags:
  - pharmacologie
  - infectiologie
  - bêta-lactamines
  - antibiotiques
  - Tassi
cssclasses:
  - medical-note
---

# Les Bêta-Lactamines

> [!info] Métadonnées
> **Module** : [[Pharmacologie]] · **Enseignant** : Pr. TASSI
> **Statut** : 🔴 Brouillon → 🟡 Révisé → 🟢 Maîtrisé

---

## I. Introduction

- Classe la plus utilisée des antibiotiques (50% des prescriptions mondiales)
- **Mécanisme commun** : inhibition de la synthèse de la paroi bactérienne
- **Bactéricides** — activité **temps-dépendante** (T > CMI = 40-70% du temps)

---

## II. Structure et mécanisme d'action

### A. Structure

- Cycle bêta-lactame (4 chaînons) commun à tous → cible des bêta-lactamases
- Différences structurales → différences de spectre, de stabilité et de pharmacocinétique

### B. Mécanisme

```mermaid
graph LR
    A[Bêta-lactamine] --> B[Liaison aux PLP\nPenicillin Binding Proteins]
    B --> C[Inhibition transpeptidases]
    C --> D[Blocage réticulaison peptidoglycane]
    D --> E[Affaiblissement paroi]
    E --> F[Lyse osmotique bactérienne = bactéricide]
```

- **PLP** (Protéines Liant la Pénicilline) sont des enzymes de synthèse du peptidoglycane
- Résistance SARM = modification PLP2a → affinité réduite pour toutes les pénicillines

---

## III. Classification des bêta-lactamines

### A. Les pénicillines

| Sous-groupe | Médicaments | Spectre |
|---|---|---|
| Pénicilline G (IV) / V (oral) | Benzylpénicilline, Phénoxyméthylpénicilline | Streptocoques, anaérobies Gram+ |
| Pénicillines M (anti-staph) | Oxacilline, Cloxacilline | SAMS uniquement |
| Aminopénicillines | Amoxicilline, Ampicilline | Streptococcus, E.coli sensible, H. influenzae |
| + Inhibiteurs bêta-lactamases | Amoxicilline-clavulanate (Augmentin®), Ampicilline-sulbactam | Spectre élargi (BLSE non couverts) |
| Carboxypénicillines/Uréidopénicillines | Ticarcilline, Pipéracilline | Pseudomonas (pipéracilline-tazobactam) |

### B. Les céphalosporines

| Génération | Médicaments | Spectre |
|---|---|---|
| C1G | Céfalexine (oral), Céfazoline (IV) | Gram+ (chirurgie prophylaxie) |
| C2G | Céfuroxime | Gram+ et certains Gram- |
| C3G orales | Céfixime, Céfpodoxime | Gram+ et Gram- (sauf Pseudomonas) |
| C3G IV | Ceftriaxone (Rocéphine®), Céfotaxime | Gram+ et Gram-, bonne diffusion LCR |
| C3G anti-Pseudomonas | Ceftazidime | + Pseudomonas |
| C4G | Céfépime | Gram+, Gram-, Pseudomonas |
| C5G | Ceftaroline | + SARM (premiers à couvrir) |

### C. Les carbapénèmes

| Médicament | Spectre | Particularité |
|---|---|---|
| Imipénème-cilastatine | Très large : Gram+, Gram-, anaérobies | Cilastatine protège contre dégradation rénale |
| Méropénème | Idem, meilleure tolérance neurologique | 1er choix méningite si résistance |
| Ertapénème | Large mais **pas Pseudomonas** | 1 fois/j, usage communautaire |

> [!important] Carbapénèmes = antibiotiques de dernier recours → réserver aux infections à BMR (BLSE, Pseudomonas multirésistant)

### D. Les monobactames

- Aztréonam : spectre Gram- uniquement, **pas d'allergie croisée avec pénicillines** → utile en allergie vraie aux pénicillines pour couvrir Gram-

---

## IV. Pharmacocinétique

| Voie | Médicament | Biodisponibilité |
|---|---|---|
| Orale | Amoxicilline, Céfixime, Céfalexine | 70-95% |
| IV/IM | Céfazoline, Ceftriaxone, Imipénème | 100% |

- Élimination principalement **rénale** → adapter à la fonction rénale (sauf ceftriaxone = biliaire)
- **Ceftriaxone** : 1 injection/j possible (demi-vie longue 8h), bonne diffusion LCR, os, prostate

---

## V. Résistances aux bêta-lactamines

| Mécanisme | Exemple | Conséquence |
|---|---|---|
| Bêta-lactamases | E.coli résistant à amoxicilline | → Utiliser amox-clav |
| **BLSE** | E.coli, Klebsiella BLSE | → Carbapénème |
| **Carbapénémases (EPC)** | K. pneumoniae EPC | → Options limitées (colistine) |
| PLP modifiée (SARM) | S. aureus MRSA | → Vancomycine, Linézolide |
| Imperméabilité + efflux | Pseudomonas aeruginosa | → Pipéracilline-tazobactam, céftazidime |

---

## VI. Effets indésirables

> [!warning] Allergie aux bêta-lactamines
> - Allergie vraie à la pénicilline : 0,1-5% des patients (souvent surestimée)
> - Réactions possibles : urticaire, anaphylaxie (IgE-médiée), maladie sérique, cytopénie
> - Allergie croisée pénicilline ↔ céphalosporines : ~2% (faible si allergie vraie documentée)
> - **Contre-indication absolue** : choc anaphylactique à une bêta-lactamine

| EI | Classe concernée |
|---|---|
| Allergie (urticaire → anaphylaxie) | Toutes, surtout pénicillines |
| Diarrhée, colite à *Clostridioides difficile* | Toutes, surtout amox-clav, C3G |
| Convulsions (doses élevées) | Imipénème ++ |
| Hypoprothrombinémie | Certaines C3G (Céfotaxime) |
| Thrombophlébite (IV) | Toutes en IV |

---

## VII. Indications cliniques clés

| Infection | Antibiotique de référence |
|---|---|
| Méningite bactérienne communautaire | Amoxicilline (pneumocoque sensible) ou Ceftriaxone |
| Pneumonie communautaire sévère | Amoxicilline-clavulanate ou C3G + macrolide |
| Pyélonéphrite | C3G IV → relais oral (céfixime) |
| Endocardite (strepto) | Amoxicilline IV ± gentamicine |
| Infections ostéo-articulaires | Oxacilline (SAMS) ou C1G |
| Prophylaxie chirurgicale | Céfazoline (C1G) |
| BLSE documentée | Imipénème ou Méropénème |

---

## Zone de révision active

> [!question] Questions de synthèse
> **Q1** : Quel est le mécanisme d'action commun à toutes les bêta-lactamines ?
> **R1** : Inhibition des PLP (Penicillin Binding Proteins) → blocage transpeptidation → lyse de la paroi bactérienne.
>
> **Q2** : Pourquoi les aminopénicillines sont-elles souvent associées à l'acide clavulanique ?
> **R2** : Pour inhiber les bêta-lactamases et élargir le spectre aux souches productrices.
>
> **Q3** : Quel traitement en cas d'E. coli BLSE ?
> **R3** : Carbapénème (imipénème ou méropénème).

> [!success] Points tombables à l'examen ⭐
> - Classif pénicillines / céphalosporines / carbapénèmes
> - Ceftriaxone : 1/j, bonne diffusion LCR, élimination biliaire
> - BLSE → carbapénèmes
> - SARM → vancomycine (pas bêta-lactamines sauf C5G)
> - Imipénème : risque épileptogène +++
> - Allergie : contre-indication absolue si choc anaphylactique

---

## Liens

- **Cours précédent** : [[14-Antibiotherapie_generalites]]
- **Cours suivant** : [[16-Aminosides]]

---

> [!success] Suivi de révision
> | Date | Score (/5) | Notes |
> |------|------------|-------|
> | {{date}} | | |

*Dernière révision : {{date}}*
