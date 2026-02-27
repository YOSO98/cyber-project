# Playbook de gestion des incidents de sécurité – Niveau 1

---

## 1. Objectif du playbook

Ce playbook décrit de manière détaillée la procédure de **gestion des incidents de cybersécurité de niveau 1** dans un cadre pédagogique simulant un environnement informatique et industriel.

Il a pour objectifs :
- Détecter rapidement un incident de sécurité
- Qualifier l’incident de manière structurée
- Appliquer les premières actions de réponse autorisées
- Décider d’une escalade si nécessaire
- Garantir la traçabilité complète des actions
- Contribuer à l’amélioration continue de la posture de sécurité

Ce document s’adresse principalement à un **profil opérationnel débutant** intervenant en support cybersécurité.

---

## 2. Définition d’un incident de sécurité

Un incident de sécurité est tout événement susceptible d’affecter :
- La confidentialité des informations
- L’intégrité des systèmes ou des données
- La disponibilité des services

Un incident peut être :
- Confirmé
- Suspecté
- En cours d’analyse

---

## 3. Périmètre d’intervention du niveau 1

Le niveau 1 est le **premier point de contact** dans la chaîne de gestion des incidents.

### 3.1 Responsabilités
- Surveillance des alertes de sécurité
- Analyse et qualification initiale
- Application de procédures standardisées
- Documentation systématique
- Escalade vers le niveau 2 ou 3 si nécessaire

### 3.2 Limites
Le niveau 1 ne doit pas :
- Modifier des configurations critiques
- Intervenir directement sur des systèmes industriels sensibles
- Supprimer des preuves ou journaux
- Appliquer des mesures non documentées

---

## 4. Typologie des incidents de niveau 1

### 4.1 Incidents courants
- Tentative de connexion anormale
- Alerte antivirus ou EDR
- Courriel de phishing signalé
- Poste utilisateur lent ou comportement anormal
- Détection de logiciel non autorisé
- Connexion à un site malveillant bloquée

### 4.2 Incidents nécessitant vigilance accrue
- Incidents touchant plusieurs utilisateurs
- Incidents impliquant des comptes à privilèges
- Incidents sur serveurs critiques
- Incidents liés à des environnements industriels

---

## 5. Sources de détection

Les incidents peuvent être détectés via :
- Outils de sécurité (antivirus, EDR, pare-feu)
- Journaux systèmes et applicatifs
- Outils de supervision
- Signalement d’un utilisateur
- Alertes automatisées
- Observations manuelles

Chaque alerte doit être analysée et **jamais ignorée**.

---

## 6. Processus de gestion des incidents

### 6.1 Étape 1 – Réception et enregistrement
- Réception de l’alerte
- Attribution d’un identifiant d’incident
- Horodatage
- Enregistrement dans le journal des incidents

---

### 6.2 Étape 2 – Qualification initiale

Le niveau 1 doit identifier :
- Type d’incident
- Système concerné
- Utilisateur impacté
- Date et heure
- Contexte d’apparition

#### Questions clés :
- L’incident est-il réel ou un faux positif ?
- Est-il isolé ou récurrent ?
- Y a-t-il un impact utilisateur ou métier ?
- Le système est-il critique ?

---

### 6.3 Étape 3 – Évaluation de la criticité

#### Critères d’évaluation :
- Nombre de systèmes impactés
- Sensibilité des données
- Impact sur la production
- Risque de propagation
- Contexte industriel ou bureautique

#### Niveaux de criticité :
- Faible : incident isolé sans impact
- Modéré : impact limité et maîtrisé
- Élevé : impact métier ou risque majeur

---

### 6.4 Étape 4 – Actions de réponse initiales

Actions autorisées au niveau 1 (selon procédures) :
- Réinitialisation de mot de passe
- Blocage temporaire d’un compte
- Mise en quarantaine d’un fichier
- Isolement logique d’un poste
- Information et accompagnement utilisateur

⚠️ Toute action doit être :
- Justifiée
- Tracée
- Conforme aux procédures internes

---

### 6.5 Étape 5 – Décision d’escalade

L’escalade est obligatoire si :
- La criticité est élevée
- Plusieurs systèmes sont touchés
- Un environnement industriel est concerné
- L’incident dépasse les compétences N1
- L’incident persiste après actions initiales

#### Informations à transmettre :
- Description claire de l’incident
- Systèmes et utilisateurs impactés
- Actions déjà effectuées
- Éléments de preuve disponibles

---

### 6.6 Étape 6 – Clôture de l’incident

Un incident peut être clos si :
- La menace est neutralisée
- Aucun impact résiduel n’est observé
- Les actions sont documentées

La clôture doit être validée et tracée.

---

## 7. Documentation et traçabilité

Chaque incident doit être documenté avec :
- Identifiant unique
- Date et heure
- Type d’incident
- Criticité
- Actions menées
- Décision finale

La documentation permet :
- Le retour d’expérience
- Les audits
- L’amélioration continue
- La conformité réglementaire

---

## 8. Sensibilisation et communication

Le niveau 1 joue aussi un rôle pédagogique :
- Rappeler les bonnes pratiques
- Expliquer les risques aux utilisateurs
- Encourager le signalement d’incidents

Une communication claire réduit les incidents futurs.

---

## 9. Amélioration continue

Après chaque incident :
- Identifier les causes racines
- Repérer les tendances
- Proposer des mesures préventives
- Mettre à jour les procédures si nécessaire

La gestion des incidents est un **processus évolutif**.

---

## 10. Cadre pédagogique

Ce playbook est élaboré dans un cadre strictement pédagogique :
- Aucun système réel
- Aucun environnement de production
- Aucune donnée sensible
- Aucun outil offensif

Il vise à démontrer une approche professionnelle et structurée
de la gestion des incidents de cybersécurité.
