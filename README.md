# NetCanvas

Éditeur de schémas réseau **vivants** : les équipements ont une vraie configuration (IP, VLAN, routes, OSPF, BGP,
ACL…) et un simulateur montre le chemin d'un ping, ou explique pourquoi il échoue. Terminaux Cisco IOS, MikroTik
RouterOS et PC, exports vers Packet Tracer, GNS3 et Containerlab, mode examen pour les enseignants.

Ce dépôt ne contient que les **installeurs**. Le code source n'est pas public.

## Utiliser NetCanvas

- **Sans installation**, dans le navigateur : <https://netcanvas.vercel.app>
- **Application de bureau** : télécharger l'installeur de la [dernière version](../../releases/latest).

| Système | Fichier | Première ouverture |
|---|---|---|
| Windows | `NetCanvas-x.y.z-win-x64.exe` | Avertissement SmartScreen : « Informations complémentaires », puis « Exécuter quand même » |
| macOS | `NetCanvas-x.y.z-mac-arm64.dmg` (Apple Silicon) ou `-x64.dmg` (Intel) | Clic droit sur l'app, « Ouvrir » |
| Linux | `NetCanvas-x.y.z-linux-amd64.deb` ou l'AppImage | `sudo apt install ./NetCanvas-….deb`, ou rendre l'AppImage exécutable |

Les installeurs ne sont pas signés (la signature d'un éditeur est payante) : c'est la raison de ces avertissements.
L'application installée vérifie ici les nouvelles versions au démarrage.

## Licence

Logiciel propriétaire, tous droits réservés : voir [`LICENSE`](LICENSE). Usage **gratuit pour apprendre et
enseigner**, sans usage commercial. Toute autre utilisation (entreprise, établissement payant, copie, modification,
redistribution) demande l'autorisation écrite du titulaire.

## Marques

Cisco, Cisco IOS et Packet Tracer sont des marques de Cisco Systems, Inc. ; MikroTik et RouterOS, des marques de
SIA Mikrotīkls ; GNS3, une marque de GNS3 Technologies Inc. NetCanvas est un produit indépendant, non affilié à ces
sociétés et non approuvé par elles : leurs noms servent uniquement à désigner les équipements, les syntaxes de
commandes et les formats de fichiers avec lesquels il est compatible.

NetCanvas est un outil d'apprentissage : sa simulation ne remplace pas du matériel réel et ne doit pas servir à
configurer ou valider un réseau de production.

## Un problème, une question ?

Ouvrir une [Issue](../../issues) sur ce dépôt (en précisant le système et la version de NetCanvas, menu Aide).
