# 🖨️ Impression 3D Open Source — RatRig VCore-4

> **Travaux Pratiques — Insertion Professionnelle | Polytech**  
> Une série de 4 séances pour maîtriser la chaîne complète d'impression 3D, de la découverte du matériel à votre premier print.

![Open-Source 3D Printer](assets/banner.png)

---

## 🗺️ Vue d'ensemble

Ce dépôt contient les supports de TP pour une introduction à l'**impression 3D FDM open source** autour de la **RatRig VCore-4** pilotée par **Klipper + RatOS**. L'ensemble de la chaîne logicielle est open source : firmware, interface web, slicer.

```
Modèle 3D  →  PrusaSlicer  →  G-code  →  Mainsail/Klipper  →  🖨️ Pièce physique
  (.stl)       (slicing)      (.gcode)     (pilotage)
```

---

## 📚 Programme des séances

| # | Séance | Durée | Contenu clé |
|---|--------|-------|-------------|
| [TP 1](TP1_Decouverte.pdf) | **Découverte** | 1h30 | FDM, open source, composants RatRig, mise sous tension |
| [TP 2](TP2_Interface_RatOS.pdf) | **Interface RatOS** | 1h30 | Mainsail, Klipper, console G-code, macros |
| [TP 3](TP3_PrusaSlicer.pdf) | **PrusaSlicer** | 1h30 | Slicing, paramètres, export G-code |
| [TP 4](TP4_Premier_Print.pdf) | **Premier Print** | 2h | Calibrations, Z-offset, Bed Mesh, lancement |

---

## 🔧 Stack technique

| Composant | Outil | Licence |
|-----------|-------|---------|
| Machine | RatRig VCore-4 | CC BY-SA 4.0 |
| Firmware | Klipper | GPL v3 |
| API | Moonraker | GPL v3 |
| Interface web | Mainsail | GPL v3 |
| Distribution | RatOS | MIT / GPL v3 |
| Slicer | PrusaSlicer | AGPL v3 |

---

## 📋 Prérequis

- Accès à une imprimante **RatRig VCore-4** sous RatOS
- Un navigateur web moderne (Chrome, Firefox, Edge)
- **PrusaSlicer** installé sur votre poste → [Télécharger](https://www.prusa3d.com/page/prusaslicer_424/)
- Un compte GitHub pour déposer vos rendus

---

## 🚀 Pour commencer

1. Commencez par lire **[TP1 — Découverte](TP1_Decouverte.pdf)** pour identifier les composants de la machine
2. Notez l'adresse IP de l'imprimante sur le réseau local
3. Suivez les séances dans l'ordre — chaque TP s'appuie sur le précédent

> ⚠️ **Sécurité** : La buse atteint 210°C et le plateau 60°C. Ne jamais toucher ces zones pendant ou juste après une impression.

---

## 📁 Structure du dépôt

```
📦 impression-3d-polytech/
├── 📄 README.md                  ← Vous êtes ici
├── 📄 TP1_Decouverte.pdf         ← Séance 1 : Découverte & open source
├── 📄 TP2_Interface_RatOS.pdf    ← Séance 2 : Mainsail & Klipper
├── 📄 TP3_PrusaSlicer.pdf        ← Séance 3 : Slicer & G-code
├── 📄 TP4_Premier_Print.pdf      ← Séance 4 : Calibrations & impression
└── 📁 assets/
    └── 🖼️  banner.png
```

---

## 📝 Rendu attendu

À la fin des 4 séances, vous devrez avoir déposé dans **votre fork** :

- [ ] Réponses aux questions de bilan (TP1 à TP4) dans un fichier `RAPPORT.md`
- [ ] Capture d'écran de votre mini-défi console (TP2)
- [ ] Paramètres PrusaSlicer utilisés (TP3)
- [ ] Photo de votre première pièce imprimée (TP4)

---

## 🌐 Ressources utiles

- [Documentation Klipper](https://www.klipper3d.org/Overview.html)
- [Documentation Mainsail](https://docs.mainsail.xyz/)
- [RatOS Configurator](https://github.com/Rat-Rig/RatOS-configurator)
- [PrusaSlicer Wiki](https://help.prusa3d.com/category/prusaslicer_204)
- [Communauté RatRig Discord](https://discord.gg/ratrig)

---

## 👨‍🏫 Encadrement

Cours d'**Insertion Professionnelle** — Département SE4  
**Polytech** | Semestre 8

---

*Tous les outils utilisés dans ce TP sont open source. Les fichiers de conception de la RatRig VCore-4 sont disponibles sur [github.com/Rat-Rig](https://github.com/Rat-Rig).*
