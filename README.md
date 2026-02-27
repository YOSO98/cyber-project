# cyber-project
## 👤 Auteur
Youssouf Souleyman  
Étudiant Bac+4/5 – Cybersécurité, DevOps, Cloud

## 🎯 Objectif du projet
Ce projet pédagogique a pour objectif de démontrer une approche structurée
de la cybersécurité en environnement industriel, intégrant des systèmes
informatiques (IT) et des systèmes industriels (OT).

Il vise à illustrer la compréhension et la mise en œuvre de :
- Concepts fondamentaux de la cybersécurité informatique et industrielle
- Opérations de sécurité de premier niveau
- Gestion des incidents de sécurité
- Sécurisation des accès sensibles
- Durcissement des systèmes informatiques et industriels
- Documentation et bonnes pratiques de sécurité
- Sensibilisation aux enjeux de cybersécurité

## 🏭 Contexte informatique et industriel
Les environnements industriels présentent des contraintes spécifiques :
- Continuité de service et de production
- Coexistence de systèmes historiques et modernisés
- Protection du savoir-faire et des données métiers

La cybersécurité doit être pragmatique, progressive et non intrusive.

## 🧩 Contenu du projet
Le dépôt est structuré autour des axes suivants :
- Contexte et gouvernance
- Cartographie des actifs informatiques et industriels
- Opérations de cybersécurité
- Sécurité des accès et des comptes à privilèges
- Durcissement des systèmes Windows, Linux et industriels
- Conformité et documentation sécurité
- Sensibilisation et bonnes pratiques

## 🛡️ Périmètre
Ce projet est strictement pédagogique :
- Aucune donnée réelle
- Aucune référence à une organisation existante
- Aucune infrastructure de production
- Aucun outil offensif

## 🚀 Finalité pédagogique
Ce dépôt vise à démontrer une compréhension concrète des enjeux de
cybersécurité informatique et industrielle dans un cadre académique.

## Architecture IT et industrielle
┌─────────────────────────────────────────────────────────────────────┐
│                              INTERNET                               │
└───────────────────────────────────┬─────────────────────────────────┘
                                    │
                          ┌──────────────────┐
                          │ Routeur / Box ISP │
                          └──────────────────┘
                                    │
                          ┌──────────────────┐
                          │   Pare-feu       │
                          │ (sécurité IT)    │
                          └──────────────────┘
                                    │
        ┌───────────────────────────┴───────────────────────────┐
        │                         ZONE IT                         │
        │                                                         │
        │   ┌──────────────┐      ┌─────────────────────────┐  │
        │   │ Postes       │      │ Serveurs internes        │  │
        │   │ utilisateurs │      │                         │  │
        │   │ PC / Laptop  │      │ - Annuaire              │  │
        │   └──────────────┘      │ - Messagerie            │  │
        │           │              │ - Fichiers             │  │
        │           │              └─────────────────────────┘  │
        │   ┌──────────────┐                                     │
        │   │ Réseau LAN   │  (Ethernet / Wi-Fi)                 │
        │   └──────────────┘                                     │
        │                                                         │
        └───────────────────────────┬───────────────────────────┘
                                    │
                        ┌────────────────────────┐
                        │  Pare-feu IT / OT       │
                        │  (filtrage strict)      │
                        └────────────────────────┘
                                    │
        ┌───────────────────────────┴───────────────────────────┐
        │                          DMZ                            │
        │                                                         │
        │   ┌──────────────────┐     ┌──────────────────────┐ │
        │   │ Bastion d’accès   │     │ Serveur supervision  │ │
        │   │ (accès sécurisé)  │     │ Logs / Alertes       │ │
        │   └──────────────────┘     └──────────────────────┘ │
        │              │                                      │
        │   ┌──────────────────┐                               │
        │   │ Jump Server       │                               │
        │   │ Accès contrôlé    │                               │
        │   └──────────────────┘                               │
        │                                                         │
        └───────────────────────────┬───────────────────────────┘
                                    │
                        ┌────────────────────────┐
                        │  Pare-feu industriel    │
                        │  (protection OT)        │
                        └────────────────────────┘
                                    │
        ┌───────────────────────────┴───────────────────────────┐
        │                         ZONE OT                         │
        │                                                         │
        │   ┌──────────────────┐     ┌──────────────────────┐ │
        │   │ Automates (PLC)   │     │ Supervision          │ │
        │   │ Industriels       │     │ Industrielle (SCADA)│ │
        │   └──────────────────┘     └──────────────────────┘ │
        │              │                                      │
        │   ┌──────────────────┐                               │
        │   │ Machines          │                               │
        │   │ Industrielles     │                               │
        │   └──────────────────┘                               │
        │                                                         │
        │  Réseau industriel isolé                               │
        │  Priorités : disponibilité et intégrité               │
        │                                                         │
        └─────────────────────────────────────────────────────┘


Ce schéma illustre une architecture segmentée entre les environnements
informatiques (IT) et industriels (OT), séparés par une zone intermédiaire (DMZ).
Cette segmentation permet de limiter les risques de propagation et de protéger
les systèmes industriels critiques.
