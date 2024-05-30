# Documentation pour le Network Attached Storage (NAS)

## Introduction
Ce dépôt contient une documentation détaillée pour la mise en place et la configuration d'un système de stockage en réseau (NAS). Un NAS est un appareil connecté à un réseau permettant de stocker et de partager des fichiers de manière centralisée, sécurisée et flexible entre plusieurs utilisateurs. Ce guide est idéal pour les particuliers et les petites et moyennes entreprises souhaitant mettre en œuvre une solution NAS pour le stockage de données, la sauvegarde et l'accès à distance.

## Sommaire
1. [Qu'est-ce qu'un NAS?](#qu-est-ce-qu-un-nas)
2. [Pourquoi utiliser un NAS?](#pourquoi-utiliser-un-nas)
3. [Qui devrait utiliser un NAS?](#qui-devrait-utiliser-un-nas)
4. [Mise en place d'un NAS](#mise-en-place-d-un-nas)
   - [Installation de la VM Debian](#installation-de-la-vm-debian)
   - [Mise en place du RAID 5](#mise-en-place-du-raid-5)
5. [Configuration du NAS](#configuration-du-nas)
   - [SSH/SFTP](#sshsftp)
   - [SAMBA](#samba)
   - [WebDAV](#webdav)
   - [Rsync](#rsync)
   - [Webmin](#webmin)
6. [Accès client au NAS](#accès-client-au-nas)
   - [Cyberduck](#cyberduck)
   - [Filezilla](#filezilla)
7. [Conclusion](#conclusion)

## Licence
Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.
