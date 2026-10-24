# 🌐 Cisco Packet Tracer — Infrastructure réseau physique

![Cisco Packet Tracer](https://img.shields.io/badge/Cisco-Packet%20Tracer-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
![Réseau](https://img.shields.io/badge/Réseau-Infrastructure-0A66C2?style=for-the-badge)
![IT Support](https://img.shields.io/badge/IT%20Support-Pratique-2E7D32?style=for-the-badge)

> **Mise en place, configuration et test d'une infrastructure réseau physique simulée avec Cisco Packet Tracer.**

---

## 🖼️ Captures du lab

### Environnement physique

<img src="Screenshots/physical-environment.jpg" alt="Environnement physique du réseau" width="100%">

### Équipements réseau

<img src="Screenshots/rack-and-patch-panel.jpg" alt="Rack et panneau de brassage" width="100%">

---

## 📌 Présentation

Ce projet s'inscrit dans ma progression pratique en **IT Support et réseaux informatiques**.

L'objectif était de reproduire une **infrastructure réseau physique** dans Cisco Packet Tracer, en travaillant directement dans le **mode Physique**, plutôt que de se limiter à une représentation logique du réseau.

Ce lab m'a permis de travailler notamment sur :

- L'infrastructure réseau physique
- L'identification des équipements réseau
- Les connexions Ethernet
- Le câblage réseau
- Les panneaux de brassage
- Les commutateurs réseau (switches)
- Les postes de travail
- La connectivité réseau
- Le diagnostic et le dépannage de problèmes de connectivité

---

## 🎯 Objectifs du lab

Les principaux objectifs étaient de :

- Comprendre le lien entre l'infrastructure physique et le réseau logique
- Identifier et organiser les équipements réseau
- Réaliser les connexions entre les différents équipements
- Utiliser les connexions Ethernet appropriées
- Configurer les interfaces nécessaires
- Permettre la communication entre les équipements
- Vérifier la connectivité du réseau
- Mettre en pratique une méthodologie de dépannage réseau

---

## 🏢 Environnement physique

Le réseau a été construit dans le **mode Physique de Cisco Packet Tracer**.

Cet environnement permet de représenter plus concrètement l'organisation d'une infrastructure réseau, notamment les équipements, les postes de travail et les connexions physiques.

### Architecture du réseau

```text
                    ┌───────────────────────┐
                    │   INFRASTRUCTURE      │
                    │       RÉSEAU          │
                    └───────────┬───────────┘
                                │
                         ┌──────▼──────┐
                         │    SWITCH   │
                         └──────┬──────┘
                                │
              ┌─────────────────┼─────────────────┐
              │                 │                 │
        ┌─────▼─────┐     ┌─────▼─────┐     ┌─────▼─────┐
        │   POSTE   │     │   POSTE   │     │  SERVEUR  │
        │  CLIENT   │     │  CLIENT   │     │           │
        └───────────┘     └───────────┘     └───────────┘
```

---

## 🔌 Infrastructure physique

Ce lab m'a permis de mettre en pratique plusieurs aspects de l'infrastructure réseau physique :

- Organisation des équipements
- Identification du matériel réseau
- Connexions Ethernet
- Brassage réseau
- Identification des ports
- Connexion des équipements
- Organisation de la topologie physique

L'objectif n'était pas uniquement de faire communiquer les équipements, mais de comprendre **comment l'infrastructure physique supporte le fonctionnement du réseau logique**.

---

## ⚙️ Configuration

La mise en place du lab a suivi plusieurs étapes :

```text
Installation physique
        ↓
Connexion des équipements
        ↓
Configuration des interfaces
        ↓
Configuration IP
        ↓
Tests de connectivité
        ↓
Dépannage
        ↓
Validation
```

---

## 🧪 Tests et dépannage

Une fois l'infrastructure mise en place, la connectivité a été vérifiée entre les différents équipements.

La démarche de dépannage suivie repose sur une approche progressive.

### 1. Couche physique

- Vérification de l'état des équipements
- Vérification des câbles Ethernet
- Vérification des connexions
- Vérification des ports utilisés

### 2. Configuration réseau

- Vérification de l'adressage IP
- Vérification de la configuration réseau
- Vérification des interfaces

### 3. Tests de connectivité

- Test de communication entre les équipements
- Utilisation de `ping`
- Identification d'un éventuel point de défaillance

### 4. Correction

- Correction de la configuration
- Nouveau test de connectivité
- Validation du fonctionnement du réseau

---

## 📁 Structure du projet

```text
cisco-packet-tracer-physical-network-lab/
│
├── README.md
│
├── packet-tracer/
│   └── physical-network-infrastructure.pkt
│
└── screenshots/
    ├── physical-environment.png
    └── rack-and-patch-panel.png
```

---

## 🛠️ Outils utilisés

| Outil / Technologie | Utilisation |
|---|---|
| **Cisco Packet Tracer** | Simulation et mise en place de l'infrastructure réseau |
| **Mode Physique** | Représentation de l'environnement physique |
| **Ethernet** | Connexion des équipements |
| **Ping** | Test de connectivité |

---

## 📚 Compétences mises en pratique

### 🌐 Réseaux

`LAN` · `IPv4` · `Ethernet` · `Switching` · `Topologie réseau`

### 🏢 Infrastructure

`Réseau physique` · `Câblage réseau` · `Équipements réseau` · `Identification des ports`

### 🖥️ IT Support

`Dépannage` · `Tests de connectivité` · `Diagnostic réseau`

### 🔧 Méthodologie

`Configurer → Tester → Diagnostiquer → Corriger → Documenter`

---

## 🧠 Ce que j'ai appris

Ce lab m'a permis de mieux comprendre la relation entre **l'infrastructure physique et le fonctionnement logique d'un réseau**.

Il m'a également permis de mettre en pratique une approche importante du support informatique :

> **Avant de chercher une erreur complexe dans la configuration, il faut vérifier les éléments physiques.**

Une configuration réseau peut être correcte sur le plan logique et pourtant ne pas fonctionner à cause d'un problème de connexion, de câblage ou de port.

---

## 🔜 Prochaines étapes

Ce projet fait partie d'une progression pratique dans le domaine des réseaux informatiques.

Les prochains labs porteront progressivement sur :

- [ ] Switching
- [ ] VLAN
- [ ] DHCP
- [ ] DNS
- [ ] Routage
- [ ] Routage inter-VLAN
- [ ] ACL
- [ ] Dépannage réseau
- [ ] Simulation d'une infrastructure réseau d'entreprise

L'objectif est de progresser d'une **infrastructure réseau fondamentale vers des scénarios réalistes d'IT Support et d'administration réseau**.

---

## 👨‍💻 Auteur

**Vamoussa KANATE**

IT Support · Réseaux · Administration systèmes · Cybersécurité

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Vamoussa%20KANATE-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vamoussa-kanate-801641187/)

[![GitHub](https://img.shields.io/badge/GitHub-vamoussa00225-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vamoussa00225)

---

<p align="center">

**Learn · Build · Troubleshoot · Document · Improve**

</p>
