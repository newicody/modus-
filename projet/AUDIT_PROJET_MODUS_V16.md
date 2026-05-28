# AUDIT COMPLET V16 — PROJET MODUS JP0F — VF1JP0F0H43308282
## 28 mai 2026 — Structure 3 phases + K9K 896

---

## 0 — VÉHICULE ET OBJECTIFS MIS À JOUR

**Véhicule :** Renault Modus 1.5 dCi 85ch Quickshift (JP0F) — K9K766 — JA5 → TL4B043
**VIN :** VF1JP0F0H43308282 — 130 000 km
**Boîte :** TL4B043 neuve (Eurofrance24 — 531,79 € PAYÉ)
**Couple bridé boîte :** 240-260 Nm (260 si tr/min élevé, reprog gérée)

### Nouvelle structure 3 phases

| Phase | Contenu | Moteur | Turbo | Couple |
|---|---|---|---|---|
| **Phase 0** | Turbo stock KP35 + reprog fine adaptée — stable | K9K766 | KP35 stock | 240-260 Nm |
| **Phase 1** | Turbo hybride géométrie variable + meilleurs injecteurs + reprog | K9K766 | BV39 hybridé VGT | 260 Nm optimisé |
| **Phase 2** | Changement de bloc + gros turbo + meilleur démarreur | **K9K 896** | Gros turbo (à définir) | 260 Nm plat large plage |

### Changement K9K 858 → K9K 896

Le moteur cible Phase 2 passe du K9K 858 au **K9K 896** (Euro 6, ECU Bosch EDC17C84, monté sur Duster II / Dokker / Logan II). Avantages : ECU plus récent, injection plus précise, pompe huile variable, compression 15.2:1. L'embrayage Valeo 845077, la TL4B043, les cardans SKF et tout le train roulant restent compatibles (cloche K9K identique). Les fichiers Budget_phase_2, Tache_phase_2, et Entretient_phase_2 (encore en V15 K9K 858) devront être mis à jour.

### Nouveau protocole anti-corrosion

Ajout d'un protocole complet en 5 étapes : démontage/tri → préparation surface → conversion rouille (Férose) → blindage époxy blanc (Restom EAF 2092) → infiltration interne (Owatrol). Produits correspondants confirmés dans les paniers Amazon et Restom.

---

## 1 — ÉTAT DES PANIERS ACTUELS — 28 mai 2026

### 1A — CARTER CASH — 436,00 €

| Pièce | Réf. | Prix |
|---|---|---|
| Kit embrayage 4P conversion (volant rigide + disque + mécanisme + CSC) | VALEO 845077 | 340,90 € |
| Plaquettes AR | TRW GDB1330 | 19,90 € |
| Soufflets direction ×2 | SKF VKJP 2011 | 21,60 € |
| Biellette reprise de couple | LEMFÖRDER 36284 01 | 43,70 € |
| Graisse cuivre 150g | Bardahl | 9,90 € |
| **TOTAL** | | **436,00 €** |

**Verdict :** ✅ Cohérent. Embrayage 845077 = choix définitif.

---

### 1B — AUTODOC — 1 840,96 €

| Pièce | Réf. | Qté | Prix |
|---|---|---|---|
| Cardan D (652, 62.8mm) | SKF | ×1 | 187,99 € |
| Cardan G (312, 888mm, avec roulement) | SKF | ×1 | 172,30 € |
| Kit distrib + pompe eau 123 dents | SKF | ×1 | 54,99 € |
| Support BV gauche | LEMFÖRDER 37966 01 | ×1 | 61,99 € |
| Contacteur feu de recul | FEBI BILSTEIN | ×1 | 12,49 € |
| Contacteur pédale embrayage | METZGER | ×1 | 6,59 € |
| Huile BV 75W-80 1L | MOTUL | ×4 | 65,96 € |
| Graisse molybdène 90g | FEBI BILSTEIN | ×4 | 11,96 € |
| Joint SPI vileb. AR (PTFE/ACM) | REINZ | ×1 | 35,99 € |
| Triangle AV D | MEYLE | ×1 | 62,99 € |
| Triangle AV G | MEYLE | ×1 | 62,99 € |
| Rotule direction G (M14x1.5) | MEYLE | ×1 | 18,99 € |
| Rotule direction D (M14x1.5) | MEYLE | ×1 | 18,99 € |
| Biellettes stab AR (130mm) | MEYLE | ×2 | 56,98 € |
| Moyeux AV 4×100 | MEYLE | ×2 | 59,98 € |
| Amortisseurs AR Bilstein B8 monotube | BILSTEIN | ×2 | 271,98 € |
| Liquide frein DOT4 0.5L | MOTUL | ×4 | 53,96 € |
| Fusée AV G | VAICO | ×1 | 80,49 € |
| Fusée AV D | VAICO | ×1 | 79,49 € |
| Support étrier AV ×2 | TRW (64,98 €) | ×2 | 64,98 € |
| Étrier AR G (alu) | TRW | ×1 | 107,99 € |
| Étrier AR D (alu) | TRW | ×1 | 108,99 € |
| Étrier AV G (fonte) | FEBI BILSTEIN | ×1 | 62,99 € |
| Étrier AV D (fonte) | FEBI BILSTEIN | ×1 | 62,49 € |
| Bouchon vidange M16×1.5 | CORTECO | ×1 | 4,59 € |
| Support étrier AR ×1 | TRW (65,99 €) | ×1 | 65,99 € |
| Clé dynamométrique 1/2" 28-210 Nm | VOREL | ×1 | 23,49 € |
| Repousse-piston universel | NEO TOOLS | ×1 | 11,49 € |
| Piges K9K | YATO | ×1 | 19,49 € |
| Commande Sécurisée | — | — | 3,95 € |
| **TOTAL** | | | **1 840,96 €** |

**Freinage confirmé :** FEBI fonte = AV, TRW alu = AR. Pas de doublon.

**Support étrier AV (TRW ×2, 64,98 €) :** 🟡 Vérifier la référence exacte sur la page Autodoc. Si c'est le BDA671 marqué « pas pour ABS », il pourrait être incompatible avec tes disques 260 mm ABS (TRW DF4274BS). Filtrer par véhicule exact (Modus JP0F 1.5 dCi 85ch) pour confirmer.

**Support étrier AR (TRW ×1, 65,99 €) :** 🟡 Un seul côté. Il en faut deux (G+D). Vérifier la réf. Si c'est un BDA1088 ou 1089, ajouter l'autre côté. Si c'est un support universel G+D, OK.

**NEO TOOLS repousse-piston (11,49 €) :** ✅ Gardé — c'est le kit universel avec rotation pour les pistons AR TRW. Supprimer le TOOLFIRST d'Oscaro s'il y est encore.

---

### 1C — OSCARO — 661,50 € (12 articles)

| Pièce | Réf. | Qté | Prix |
|---|---|---|---|
| Bague étanchéité (SPI AAC) | REINZ 81-34367-00 | ×1 | 12,70 € |
| Kit coupelle suspension AV (6 pièces, complet) | SNR KB655.32 | ×2 | 117,80 € |
| Thermostat | AISIN THRAZ-7009 | ×1 | 18,90 € |
| Disques AV (lot 2) | TRW DF4274BS | ×1 | 109,88 € |
| Kit protection amortisseur | MEYLE 16-14 740 0001 | ×1 | 17,28 € |
| Ressorts AV+AR (lot) | EIBACH E10-75-008-01-22 | ×1 | 179,50 € |
| FMIC intercooler | NRF 30481 | ×1 | 118,90 € |
| Biellettes stab AV HD | MEYLE 35-16 060 0021/HD | ×2 | 31,14 € |
| Roulements AV | SKF VKBA 3596 | ×2 | 55,40 € |
| **TOTAL** | | | **661,50 €** |

**SNR KB655.32 :** ✅ Confirmé AV uniquement (kit 6 pièces complet : butée + roulement + coupelle + écrou + visserie). Pas besoin d'AR — l'essieu semi-rigide n'a pas de coupelle.

**Butées SKF VKDA 35639 retirées** du panier (remplacées par le SNR KB655.32 qui est plus complet). Pas de doublon.

**Verdict :** ✅ Cohérent.

---

### 1D — AMAZON — 525,68 € (20 articles)

| Pièce | Prix | Rôle |
|---|---|---|
| Owatrol Rustol aérosol 500ml | 34,50 € | Anti-corrosion — infiltration cavités |
| Ferose convertisseur rouille 1L | 49,99 € | Anti-corrosion — conversion R1-R2 |
| Owatrol huile 1L + pinceau | 29,00 € | Anti-corrosion — infiltration interne essieu |
| Support étrier G | TRW BDA605 | 32,00 € | ⚠️ voir alerte ci-dessous |
| Support étrier D | TRW BDA604 | 36,25 € | ⚠️ voir alerte ci-dessous |
| Disques AR (lot 2) | Brembo 09.9078.75 | 83,26 € | Freinage AR 240mm |
| Loctite 243 bleu 5ml | ×3 = 32,70 € | Freinage vis |
| Fusibles AGU 30A plaqué or ×2 | 1,76 € | Électrique — circuit batterie |
| Boîte fusibles 6 voies KAOLALI | 16,49 € | Électrique — distribution secondaire |
| Disjoncteur 30A réarmable | EPLZON | 13,99 € | Électrique — protection accessoires |
| Bouilloire 12V 450ml ×2 | 23,76 € | Confort |
| Plaquettes AV performance | Brembo P 68 033X | 45,49 € | Freinage AV |
| SPI vilebrequin AV | Corteco 20031906B | 21,02 € | Distribution — côté distrib |
| Batterie LiFePO4 12V 18Ah | RoyPow S1218 | 69,99 € | Électrique — bord |
| Rotules direction intérieures ×2 | Meyle 16-16 031 0015 | 28,58 € | Direction |
| **TOTAL** | | **525,68 €** |

**🔴 ALERTE — BDA604 + BDA605 = AUDI A6, PAS RENAULT.** Ces supports sont incompatibles. À retirer immédiatement et remplacer par des supports compatibles Clio III/Modus (voir section 2).

---

### 1E — TRODO — 185,60 €

| Pièce | Réf. | Prix |
|---|---|---|
| Passage de roue | BLIC 6601-01-6007804P | 21,99 € |
| Cache moteur | BLIC 6601-02-6007860P | 46,41 € |
| Boulons de bielle ×4 | ET ENGINETEAM BS0029 | 10,75 € |
| Émetteur embrayage | VALEO 804816 | 74,20 € |
| **TOTAL** | | **185,60 €** |

**Émetteur VALEO 804816 :** ✅ Pièce critique résolue. Complète le circuit pédale → émetteur → HEL → CSC (845077).

**Boulons de bielle :** Coussinets à commander plus tard après dépose et inspection d'usure.

**Verdict :** ✅ Cohérent.

---

### 1F — RESTOM — 73,90 €

| Pièce | Prix |
|---|---|
| Epoxy EAF 2092 blanc satiné RAL 9003 (1kg + diluant) | 64,00 € |
| Transport | 9,90 € |
| **TOTAL** | **73,90 €** |

Blindage époxy pour essieu AR / berceau AV — Phase 3 du protocole anti-corrosion (après Férose, avant Owatrol). ✅ Cohérent.

---

### 1G — AUTRES PANIERS (inchangés)

| Fournisseur | Contenu | Total | Statut |
|---|---|---|---|
| GT2i | Powerflex ×6 | 392,40 € | ✅ PAYÉ |
| Eurofrance24 | TL4B043 neuve | 531,79 € | ✅ PAYÉ |
| Norauto ×3 | Outils | 162,88 € | ✅ PAYÉ |
| Ultraperformance | JR-7 16×7 ×4 | 596,00 € | En panier |
| Goodridge | Kit flexibles frein aviation | 109,23 € | En panier |
| AliExpress | Kess V2 + KTAG + Maxwell 16V100F | 98,07 € | En panier |
| R.tech | Bilstein B8 AV 35-128649 ×2 | 277,33 € | En panier |

---

## 2 — PROBLÈMES À RÉSOUDRE

### 2A — 🔴 Supports étrier AR — BDA604/BDA605 AUDI incompatibles

Les TRW BDA604 et BDA605 dans le panier Amazon sont pour Audi A6 (OE 4F0 615 425). Ils ne sont absolument pas compatibles avec le Modus/Clio III.

**Situation AR :** Les supports étrier AR sur la plateforme Clio 3 GT avec disques sont intégrés aux fusées/porte-moyeux AR. En aftermarket neuf, la référence **GH GH-463975** (Autodoc, ~25-50 € pièce, essieu AR, compatible Clio III) est disponible. Toutefois, ces supports ne se montent que si le porte-moyeu AR a les bossages de fixation pour étriers à disque. Le Modus d'origine (tambours AR) n'a probablement pas ces bossages.

**Solution recommandée :** Les fusées AR complètes avec pattes étrier intégrées ne sont quasiment pas disponibles en aftermarket neuf (seule la version tambour MAPCO 26154 existe). Les options sont :

1. **OE Renault** — Commander les porte-moyeux AR version disque via un concessionnaire Renault avec un VIN de Clio 3 GT ou dCi 106 (100-180 € la paire estimé)
2. **Casse** — Récupérer les fusées AR complètes avec supports intégrés d'un donneur Clio 3 GT. Pièce structurelle qui ne s'use pas. Traiter avec Ferose + Owatrol + Restom Epoxy (déjà en paniers)

**Actions :**
- Retirer BDA604 + BDA605 d'Amazon (−68,25 €)
- Choisir option 1 ou 2

### 2B — 🟡 Support étrier AV — Compatibilité ABS à vérifier

Le TRW support AV ×2 (64,98 €) dans Autodoc — si c'est le BDA671 marqué « pas pour ABS », il pourrait être dimensionné pour des disques plus petits (238 mm non-ABS) au lieu des 260 mm ABS (TRW DF4274BS). Vérifier la référence exacte sur la page Autodoc en filtrant par véhicule Modus JP0F.

### 2C — 🟡 Support étrier AR Autodoc — Un seul côté

Le TRW support ×1 à 65,99 € dans Autodoc : vérifier si c'est un support AR. S'il est AR, ajouter le deuxième côté. S'il est AV (faisant doublon avec le ×2 à 64,98 €), vérifier la cohérence.

### 2D — 🟡 Goodridge flexibles — AV seulement ou AV+AR ?

Le kit Goodridge (109,23 €) est référencé Modus 1.5 dCi = probablement conçu pour tambours AR d'origine. Après conversion en disques AR, les flexibles AR Modus ne correspondent plus. Options :

- Remplacer par un kit Goodridge Clio 3 complet (AV+AR, 4 pièces)
- Garder le Goodridge Modus pour l'AV et ajouter des flexibles AR séparément
- Contacter GT2i/Goodridge pour confirmation

---

## 3 — PIÈCES MANQUANTES

| Pièce | Urgence | Budget estimé | Note |
|---|---|---|---|
| **Fusées AR version disque** (ou porte-moyeux AR complets) | 🔴 Critique | OE : 100-180 € / Casse : 50-80 € | Nécessaires pour la conversion disque AR |
| **2ème support étrier AR** (si 1 seul dans Autodoc) | 🟡 Important | ~56-66 € | Vérifier panier Autodoc |
| Flexibles frein AR (après conversion disque) | 🟡 Important | 50-70 € | Goodridge ou équivalent |
| Vis supports étrier M12 cl. 10.9 ×8 | 🟡 Important | 10-20 € | Non incluses avec supports |
| Coussinets de bielle (après dépose et inspection) | 🟢 Différé | 40-80 € | Boulons déjà en panier Trodo |
| Pneus 195/55 R16 ×4 | 🟢 Plus tard | 280-320 € | Norauto, après réception jantes |
| HASKYY Alubutyl ×3 | 🟢 Phase 0 | 78-93 € | Amazon |
| Pièces casse (levier 6V, pédalier, câbles FAM, démarreur, support alu sup.) | 🟡 Important | 100-400 € | Casse Clio 3 GT |
| Carré mâle 8mm (vidange TL4) | 🟡 Important | 3-5 € | Outils_audit |
| 2 chandelles 2T supplémentaires | 🟡 Important | ~40 € | Pour 4 points simultanés |

---

## 4 — BUDGET RÉCAPITULATIF

### Déjà payé

| Fournisseur | Montant |
|---|---|
| Eurofrance24 (TL4B043) | 531,79 € |
| GT2i (Powerflex ×6) | 392,40 € |
| Norauto (outils ×3) | 162,88 € |
| **TOTAL PAYÉ** | **1 087,07 €** |

### Paniers actuels

| Fournisseur | Montant |
|---|---|
| Carter Cash | 436,00 € |
| Autodoc | 1 840,96 € |
| Oscaro | 661,50 € |
| Amazon (après retrait BDA604/605 : −68,25 €) | ~457,43 € |
| Trodo | 185,60 € |
| Restom | 73,90 € |
| Ultraperformance | 596,00 € |
| Goodridge | 109,23 € |
| AliExpress | 98,07 € |
| R.tech | 277,33 € |
| **TOTAL PANIERS** | **~4 736 €** |

### Restant à acheter

| Poste | € mini | € maxi |
|---|---|---|
| Fusées AR disque (OE ou casse) | 50 | 180 |
| Support étrier AR (2ème côté si manquant) | 0 | 66 |
| Flexibles frein AR | 50 | 70 |
| Vis supports étrier ×8 | 10 | 20 |
| Pièces casse (levier, pédalier, câbles, démarreur, support alu) | 100 | 400 |
| Pneus 195/55 R16 ×4 | 280 | 320 |
| HASKYY Alubutyl ×3 | 78 | 93 |
| Outils manquants (carré 8mm, chandelles) | 43 | 45 |
| Divers (vis, consommables) | 20 | 50 |
| **TOTAL RESTANT** | **~631** | **~1 244** |

### Budget Phase 0 (complète)

| | € mini | € maxi |
|---|---|---|
| Payé | 1 087 | 1 087 |
| Paniers | 4 736 | 4 736 |
| Restant | 631 | 1 244 |
| **TOTAL PHASE 0** | **~6 454** | **~7 067** |

### Budget total projet (3 phases)

| Phase | € mini | € maxi |
|---|---|---|
| Phase 0 (TL4 + KP35 stock + reprog fine + train roulant complet) | 6 454 | 7 067 |
| Phase 1 (turbo hybride VGT + injecteurs + reprog) | 800 | 1 500 |
| Phase 2 (swap K9K 896 + gros turbo + démarreur) | 1 860 | 3 935 |
| **TOTAL PROJET** | **~9 114** | **~12 502** |

*Note : Phase 1 estimée sur base BV39 hybridé (~400-600 €) + injecteurs améliorés (~200-400 €) + reprog DIY Kess V2 (~130-430 €). Phase 2 basée sur Budget_phase_2 V15 (encore en K9K 858, à mettre à jour pour K9K 896).*

---

## 5 — INCOHÉRENCES FICHIERS PROJET

| Fichier | Problème | Action |
|---|---|---|
| **Budget_phase_2** | Encore en K9K 858, doit passer en K9K 896 | Mettre à jour |
| **Tache_phase_2** | Encore en K9K 858 | Mettre à jour |
| **Entretient_phase_2** | Encore en K9K 858 | Mettre à jour |
| **Cablage_electrique** (V5) | Doublon avec **elec** (V15) | Supprimer V5 |
| **Fournisseurs** | Pas à jour (montre 836223/EXEDY/SACHS comme en commande) | Mettre à jour |
| **Budget** | Encore en structure 2 phases | Passer en 3 phases |
| **Taches** | Encore en structure 2 phases | Passer en 3 phases |
| **Casse** | Gardes-boue + cache moteur listés en casse, maintenant neufs (Trodo) | Retirer |
| **Casse** | Fusées AV listées, maintenant VAICO neuves (Autodoc) | Retirer |

---

## 6 — ACTIONS PRIORITAIRES

| # | Action | Priorité |
|---|---|---|
| 1 | **Retirer BDA604 + BDA605 d'Amazon** (Audi, incompatibles) | 🔴 Critique |
| 2 | **Sourcer fusées AR version disque** (OE Renault ou casse) | 🔴 Critique |
| 3 | **Vérifier réf. supports étrier AV** dans Autodoc (ABS / 260mm) | 🟡 Important |
| 4 | **Vérifier le support AR ×1** dans Autodoc (quel côté ? en faut-il 2 ?) | 🟡 Important |
| 5 | **Clarifier Goodridge** : AV seul ou AV+AR après conversion disque ? | 🟡 Important |
| 6 | Mettre à jour les fichiers projet (K9K 896, 3 phases, Fournisseurs) | 🟢 Quand possible |

---

*Audit V16 — 28 mai 2026 — Basé sur les fichiers projet V15 + paniers actuels + nouveau README + protocole corrosion*
