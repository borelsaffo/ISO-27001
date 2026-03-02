# ISO-27001
# Traduire l'Annexe A de ISO/IEC 27001 en contrôles opérationnels

Si tu prends l'annexe A de ISO/IEC 27001 (93 mesures de sécurité),
l'idée n'est pas de les "appliquer telles quelles", mais de les traduire
en contrôles techniques et organisationnels concrets adaptés à ton
contexte (applications, infrastructure, cloud, etc.).

Voici une méthode claire et opérationnelle 👇

------------------------------------------------------------------------

## 1️⃣ Comprendre la logique de l'annexe A

Les 93 mesures sont regroupées en 4 grandes catégories :

-   Organisationnelles\
-   Humaines\
-   Physiques\
-   Technologiques

⚠️ Ce sont des objectifs de contrôle, pas des configurations techniques
prêtes à l'emploi.

------------------------------------------------------------------------

## 2️⃣ Méthode pour traduire une mesure en contrôle opérationnel

Pour chaque mesure :

### Étape 1 --- Identifier l'objectif

👉 Quel risque cherche-t-on à réduire ?

### Étape 2 --- Identifier le périmètre

-   Application ?\
-   Infrastructure ?\
-   Cloud ?\
-   Données sensibles ?\
-   Utilisateurs ?

### Étape 3 --- Définir des contrôles concrets

-   Processus\
-   Paramétrage technique\
-   Outils\
-   Preuves d'audit

### Étape 4 --- Définir des indicateurs

-   KPI\
-   Logs\
-   Tests\
-   Revues périodiques

------------------------------------------------------------------------

## 3️⃣ Exemple concret de traduction

### 🔐 Exemple 1 : Contrôle d'accès

**Mesure ISO :**\
Les accès aux systèmes doivent être contrôlés et revus régulièrement.

**Traduction opérationnelle :**

**Contrôles techniques :**

-   Mise en place de RBAC\
-   MFA obligatoire\
-   Désactivation automatique des comptes inactifs\
-   Revue trimestrielle des droits\
-   Journalisation des connexions

**Preuves :**

-   Export des logs IAM\
-   Rapport de revue des accès\
-   Capture des politiques de sécurité

------------------------------------------------------------------------

### 🛡 Exemple 2 : Gestion des vulnérabilités

**Mesure ISO :**\
Les vulnérabilités doivent être identifiées et corrigées rapidement.

**Traduction opérationnelle :**

**Contrôles techniques :**

-   Scan mensuel via outil de vulnérabilité\
-   Patch critique \< 7 jours\
-   Intégration SAST/DAST dans CI/CD\
-   Revue CVE hebdomadaire

**Indicateurs :**

-   \% vulnérabilités critiques corrigées sous SLA\
-   MTTR sécurité

------------------------------------------------------------------------

### 🔎 Exemple 3 : Sécurité des applications

**Mesure ISO :**\
Les applications doivent être développées de manière sécurisée.

**Traduction opérationnelle :**

-   Politique Secure SDLC\
-   Analyse SAST à chaque build\
-   Tests DAST en pré-production\
-   Revue de code obligatoire\
-   Protection OWASP Top 10

------------------------------------------------------------------------

## 4️⃣ Construire une matrice de traduction

Tu peux créer un tableau comme celui-ci :

  -------------------------------------------------------------------------
  Mesure ISO   Risque couvert  Contrôle technique  Outil    Preuve   KPI
  ------------ --------------- ------------------- -------- -------- ------

  -------------------------------------------------------------------------

Cela devient ta matrice de conformité opérationnelle.

------------------------------------------------------------------------

## 5️⃣ Astuce professionnelle

Pour être efficace :

Lie chaque mesure ISO à :

-   un risque\
-   un actif\
-   un propriétaire

Mutualise avec :

-   ISO/IEC 27002 (guide d'implémentation)\
-   NIS2\
-   CIS Controls\
-   OWASP

Ça évite les doublons et renforce ton cadre de contrôle.

------------------------------------------------------------------------

## 🎯 En résumé

Traduire l'annexe A, ce n'est pas faire un copier-coller.

C'est :

**Objectif de sécurité → Risque → Contrôle concret → Outil → Preuve →
Indicateur**
