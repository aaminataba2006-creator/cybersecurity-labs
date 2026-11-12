# Déploiement de pare-feu open source et durcissement réseau

[English version](README.en.md)

**Période :** 2024 – 2025 · **Outils :** pfSense, IPFire · **Thèmes :** segmentation réseau, filtrage de paquets

## Objectif

Mettre en place des pare-feu open source dans un réseau virtualisé et renforcer sa sécurité grâce à la **segmentation en zones** et à des **règles de filtrage de paquets**.

## Pourquoi ce projet

Le pare-feu est la première barrière entre un réseau interne et l'extérieur. Segmenter le réseau en zones distinctes limite la propagation d'une attaque : si une zone est compromise, les autres restent protégées.

## Environnement

- Réseau entièrement virtualisé : aucun équipement physique ni réseau réel n'est exposé.
- Pare-feu déployés : **pfSense** et **IPFire**.
- Machines de test pour vérifier le comportement des règles.

## Architecture

Le pare-feu est placé entre les différents segments du réseau. Chaque segment correspond à une **zone de sécurité distincte** : le trafic ne passe d'une zone à l'autre que s'il est autorisé par une règle explicite.

## Démarche

1. Installation et configuration initiale de pfSense et d'IPFire (interfaces réseau, adressage).
2. Définition des zones de sécurité et rattachement des interfaces à chaque zone.
3. Création des règles de filtrage entre les zones : seuls les flux nécessaires sont autorisés, le reste est refusé.
4. Tests : vérification que le trafic autorisé passe et que le trafic non autorisé est bloqué.

## Compétences développées

- Administration de pare-feu open source
- Conception de règles de filtrage de paquets
- Segmentation réseau et définition de zones de sécurité
- Durcissement d'une infrastructure réseau

## Pistes d'amélioration

- Ajouter un système de détection/prévention d'intrusion (IDS/IPS)
- Mettre en place un VPN pour l'accès distant sécurisé
- Centraliser et analyser les journaux du pare-feu
