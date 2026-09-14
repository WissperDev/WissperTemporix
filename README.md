# WissperTemporix

Client desktop **multi-compte** pour Dofus Touch, sous Windows. Plusieurs
personnages dans une seule fenêtre, chacun dans sa session isolée.

**Aucune fonction de bot.** Pas de scripts, pas d'IA de combat, rien qui joue à
votre place. Uniquement du confort pour jouer en équipe.

---

## ⚠ À lire avant d'installer

Utiliser un client tiers sur Dofus Touch **viole les conditions d'utilisation d'Ankama**, et un compte peut être banni pour ça — **même sans la moindre automatisation**.

N'y mettez pas un compte auquel vous tenez, ni un compte qui porte des achats. Un compte neuf, sur une adresse mail à part, est la seule façon raisonnable d'essayer. Personne ne vous remboursera un compte perdu.

C'est une beta, elle est gratuite, et elle est fournie **sans aucune garantie**.

---

## Installer

Téléchargez le `.exe` depuis [la dernière release](../../releases/latest).

**Windows affichera « Windows a protégé votre ordinateur »** → *Informations
complémentaires* → *Exécuter quand même*. L'installeur n'est pas signé — un
certificat de signature de code coûte plusieurs centaines d'euros par an. Ce
n'est pas un problème du fichier.

Vous pouvez vérifier l'empreinte du fichier téléchargé :

```powershell
Get-FileHash .\WissperTemporix-0.9.0-beta.1-win-x64.exe -Algorithm SHA256
```

L'empreinte attendue est publiée dans les notes de chaque release.

Pour la **0.9.0-beta.1** :

```
4a76eb95d5040f70db719a9b43d8b727db10fbe68dac8f70a7a6ebe452e227cc
```

**Les mises à jour sont automatiques** : l'application vérifie au lancement et
installe à la fermeture. Rien à réinstaller à la main.

---

## Ce qu'il fait

- plusieurs comptes côte à côte, chacun dans sa **session isolée**
- **suivi de groupe** : les suiveurs accompagnent le meneur de carte en carte
- **invitation automatique** au groupe, et dialogues en miroir
- **rejoindre le combat du meneur** et **se déclarer prêt**, avec un délai
  réglable — le tour, vous le jouez vous-même
- notifications (votre tour, message privé, agression, percepteur) et bascule
  automatique vers le compte concerné
- raccourcis clavier : `1`–`9` sorts, `Ctrl` + chiffre objets, `Retour arrière`
  fin de tour
- **quêtes** : la liste, l'objectif en cours, et « Aller » pour rejoindre sa carte —
  parler au personnage non-joueur, c'est vous
- proxy ou carte réseau **par compte**, résolution réglable

Les réglages d'équipe sont dans **Réglages → Jeu**, sous « Suivi de groupe ».

La **console** (l'icône à gauche des boutons de fenêtre) ouvre la fiche du
personnage, le sac, la carte du monde et les quêtes. Rien n'y joue tout seul :
les seuls ordres qu'elle envoie sont des déplacements.

---

## Discuter, signaler un bug

Le salon de la beta : **https://discord.gg/KHWBdvsGJ4**

---

## Licence

GPL-3.0. Ce programme dérive de [angine67/DofuEmu](https://github.com/angine67/DofuEmu),
sous la même licence.

Ce dépôt ne contient que des binaires. Pour obtenir le code source correspondant
à une version distribuée ici, ouvrez une issue : il vous sera fourni, comme la
licence l'exige.

Dofus Touch est une marque d'Ankama. Ce projet n'est ni affilié à Ankama, ni
approuvé par Ankama.
