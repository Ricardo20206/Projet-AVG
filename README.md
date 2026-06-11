# Projet-AVG

Carte électronique de **monitoring** basée sur un microcontrôleur **ESP32**, réalisée dans le cadre du projet **Équipe 4 — GROUPE WEED** (2026).

## Description

Ce dépôt contient la conception complète de la carte de monitoring AVG : schémas, routage PCB, bibliothèques de composants et documentation associée. Le projet est développé sous **Altium Designer**.

### Fonctionnalités principales

- Microcontrôleur **ESP32**
- Acquisition via **capteurs**
- Pilotage d'**actionneurs**
- Gestion d'un **circuit de priorité**
- Alimentation et **régulateurs**
- Interface **USB / UART**
- **Connecteurs** pour l'intégration système

## Structure du dépôt

| Dossier       | Contenu                                              |
|---------------|------------------------------------------------------|
| `10_doc_ext/` | Documentation externe (datasheets, recherches, …)      |
| `20_doc_int/` | Documentation interne (suivi, notes de version, …)  |
| `30_src/`     | Sources du projet Altium (schémas, PCB, bibliothèques) |
| `40_tmp/`     | Fichiers temporaires (non versionnés)                |
| `50_out/`     | Fichiers générés (exports, sorties de fabrication)   |
| `60_valid/`   | Fichiers de validation et tests                      |

## Fichiers principaux (`30_src/`)

| Fichier / dossier              | Description                          |
|--------------------------------|--------------------------------------|
| `ESP32_Projet.PrjPcb`          | Projet Altium principal              |
| `Feuille_2_ESP32.SchDoc`       | Schéma ESP32                         |
| `Capteurs.SchDoc`              | Schéma capteurs                      |
| `Actionneur.SchDoc`            | Schéma actionneurs                   |
| `Circuit de priorité.SchDoc`   | Schéma circuit de priorité           |
| `Regulateurs.SchDoc`           | Schéma alimentation / régulateurs    |
| `Connecteurs.SchDoc`           | Schéma connecteurs                   |
| `USB_UART.SchDoc`              | Schéma interface USB / UART          |
| `PCB/PCB11.PcbDoc`             | Carte imprimée                       |
| `Rapport de la carte de monitoring AVG..pdf` | Rapport de conception |

## Prérequis

- [Altium Designer](https://www.altium.com/altium-designer) (version compatible avec les fichiers du projet)
- Accès aux bibliothèques `SCHLibrary.SchLib` et `PCBLibrary.PcbLib` incluses dans le dépôt

## Ouverture du projet

1. Cloner le dépôt :
   ```bash
   git clone https://github.com/Ricardo20206/Projet-AVG.git
   ```
2. Ouvrir Altium Designer.
3. Charger le fichier `30_src/ESP32_Projet.PrjPcb`.

## Équipe

**Équipe 4 — GROUPE WEED**

## Licence

À définir.
