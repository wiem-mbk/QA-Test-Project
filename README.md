# QA-Test-Project
# Projet QA – Test de la fonctionnalité Login d’un site e-commerce

## Description
Ce projet est un exercice pratique de test logiciel réalisé dans le cadre de ma préparation ISTQB.  
L’objectif était de mettre en pratique les bonnes pratiques QA : rédaction de cas de test, exécution manuelle, détection de bugs, et documentation structurée.

La fonctionnalité testée : **Login (connexion) d’un utilisateur** sur un site e-commerce.

---

## Contenu du projet

- `Cas_de_Test.xlsx` : 10 cas de test couvrant les scénarios suivants :
  - Connexion avec email existant et inexistant
  - Mot de passe correct ou incorrect
  - Champs vides ou limites (espaces, caractères spéciaux)
  - Préconditions : compte existant, inscription préalable, compte lié à un réseau social
- `Bug_Report.xlsx` : Bug report détaillé pour les anomalies détectées, incluant :
  - Cas de test associé
  - Étapes pour reproduire
  - Résultat obtenu vs résultat attendu
  - Sévérité et priorité
  - Commentaires sur l’environnement de test

---

## Méthodologie QA utilisée

1. **Analyse de la fonctionnalité** : compréhension des objectifs de la page login et des scénarios possibles  
2. **Rédaction de cas de test** : cas nominaux, cas d’erreur, cas limites  
3. **Exécution des tests** : suivi du statut Pass / Fail  
4. **Documentation des anomalies** : création de bug reports détaillés  
5. **Outils utilisés** :
   - Google Sheets pour cas de test et bug report
   - Navigateur Chrome pour exécution des tests manuels

---

## Résultat

- 10 cas de test exécutés  
- 1 bug majeur identifié (email mal orthographié redirige vers page d’inscription au lieu d’un message d’erreur)  
- Documentation complète disponible dans les fichiers Excel

---

## Objectif pédagogique

- Appliquer les bonnes pratiques ISTQB en test logiciel manuel  
- Développer la capacité à rédiger des cas de test clairs et reproductibles  
- Savoir documenter les anomalies de manière professionnelle  
- Créer un projet QA complet à montrer aux recruteurs ou inclure dans un portfolio
