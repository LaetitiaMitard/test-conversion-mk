# Expression des besoins – AMI

## 1. Présentation du besoin métier

Le projet **AMI (Assistant Métier Intelligent)** vise à fournir une interface conversationnelle en langage naturel permettant aux utilisateurs métier d’accéder rapidement à des informations complexes, issues de bases de connaissances internes. Il s’inscrit dans une logique d’**APIsation des services** et d’amélioration de l’expérience utilisateur dans les parcours d’offres.

---

## 2. Personae / Profils utilisateurs

- Conseillers métier (utilisateurs finaux)
- Référents fonctionnels
- Équipes support et formation
- Product Owner et Business Analyst
- Architectes techniques

---

## 3. Parcours utilisateurs

Les utilisateurs interagissent avec l’assistant via une **interface web** ou intégrée à leur environnement de travail. Ils posent des questions en langage naturel, reçoivent des réponses contextualisées, et peuvent affiner leur requête. Des **suggestions automatiques** et des **historiques de requêtes** sont également proposés.

---

## 4. Fonctionnalités attendues

- Recherche en langage naturel sur des bases documentaires internes
- Suggestions de questions fréquentes
- Intégration de documents PDF et tableaux dans les réponses
- Indicateurs de fiabilité et de complétude des réponses
- Interface de configuration pour les administrateurs
- Historique des requêtes et feedback utilisateur

---

## 5. Contraintes

- Respect des normes de sécurité et de confidentialité des données
- Intégration avec les systèmes d’information existants
- Conformité réglementaire (RGPD, etc.)
- Performance et scalabilité du moteur de recherche
- Accessibilité de l’interface

---

## 6. Indicateurs de succès (KPIs)

- Taux de satisfaction des utilisateurs
- Taux de réponse pertinente dès la première requête
- Temps moyen de réponse
- Nombre de requêtes traitées
- Taux d’utilisation de l’assistant

---

## 7. Hypothèses / Points d’attention

- Les bases documentaires sont structurées et accessibles via API
- Les utilisateurs sont formés à l’usage de l’assistant
- Le moteur LLM est personnalisable selon les cas d’usage métier
- Les retours utilisateurs seront pris en compte pour améliorer le service