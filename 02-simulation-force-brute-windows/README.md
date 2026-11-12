# Simulation d'attaque par force brute sur Windows

**Période :** 2024 – 2025 · **Outils :** Kali Linux, outils de tests d'intrusion · **Thèmes :** authentification, gestion des mots de passe

> **Cadre :** ce projet a été réalisé uniquement dans un laboratoire virtualisé et isolé, sur des machines qui m'appartiennent. Aucun système réel n'a été visé. Ce dépôt ne contient ni liste de mots de passe, ni identifiants.

## Objectif

Réaliser un scénario complet de test d'intrusion contre une machine Windows afin d'analyser ses **mécanismes d'authentification** et d'identifier les **failles liées à la gestion des mots de passe**.

## Pourquoi ce projet

Les mots de passe restent l'un des points d'entrée les plus courants dans un système d'information. Comprendre comment une attaque par force brute fonctionne permet de concevoir des protections efficaces.

## Environnement

- Machine attaquante : Kali Linux et ses outils de sécurité offensive
- Machine cible : poste Windows
- Réseau virtualisé et isolé

## Démarche

1. Mise en place du laboratoire et vérification de son isolation.
2. Analyse du fonctionnement de l'authentification Windows.
3. Exécution de l'attaque par force brute avec les outils de Kali Linux.
4. Analyse des résultats et identification des faiblesses liées aux mots de passe.

## Enseignements

- La qualité des mots de passe et leur gestion déterminent directement la résistance d'un système à ce type d'attaque.
- Un test d'intrusion se prépare et se cadre : périmètre, environnement isolé, objectif défini.
- Prise en main approfondie de Kali Linux et des outils de sécurité offensive.

## Contre-mesures recommandées

- Politique de mots de passe robustes (longueur, complexité, absence de mots de passe courants)
- Verrouillage temporaire des comptes après plusieurs échecs de connexion
- Authentification multifacteur
- Surveillance et alertes sur les échecs de connexion répétés
