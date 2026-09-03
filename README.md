# 🛡️ La Cybersécurité sans mal de tête
> *Protéger sa maison (et son entreprise) sans prise de tête ni jargon d'expert.*

Ce guide est un manuel de survie numérique pensé pour être compris par tous (de vos parents à un collaborateur en entreprise), tout en posant les bases indispensables de la gouvernance et de la sécurité opérationnelle.

---

## Sommaire
1. [Introduction : La maison et la forteresse](#1-introduction--la-maison-et-la-forteresse)
2. [Étape 1 : Le grand inventaire de printemps](#2-étape-1--le-grand-inventaire-de-printemps-savoir-ce-quon-possède)
3. [Étape 2 : La fin de la clé sous le paillasson (Le Passwordless)](#3-étape-2--la-fin-de-la-clé-sous-le-paillasson-le-passwordless)
4. [Étape 3 : Le réflexe du douanier](#4-étape-3--le-réflexe-du-douanier-déjouer-les-pièges)
5. [Étape 4 : Le double des clés chez les beaux-parents](#5-étape-4--le-double-des-clés-chez-les-beaux-parents-la-résilience)

---

## 1. 🏠 Introduction : La maison et la forteresse
Tout le monde comprend qu'on ne laisse pas la porte d'entrée grande ouverte avec les clés sur la serrure, ni la fenêtre du salon entrouverte en partant en vacances. Pourtant, sur Internet, on fait l'équivalent tous les jours sans s'en rendre compte. 
La cybersécurité fait souvent peur parce qu'on la résume à du code incompréhensible. Oublions le jargon. Ce guide pose **4 règles simples de bon sens** pour verrouiller sa vie numérique. Ce qu'on fait chez soi pour protéger ses photos de famille, c'est exactement ce qu'une entreprise ou une administration doit faire à grande échelle. La seule différence, c'est l'échelle, pas les principes.

---

## 2. 📋 Étape 1 : Le grand inventaire de printemps (Savoir ce qu'on possède)
> *La règle d'or : Impossible de protéger ce qu'on ignore posséder.*

* **Le problème :** Au fil des ans, on accumule du matériel et des logiciels. Un vieux PC portable au fond du placard, une tablette qui ne sert plus, une application téléchargée pour une occasion précise. Chacun de ces éléments oublié est une porte d'entrée potentielle que personne ne surveille.
* **Le cas concret :** C'est retrouver une vieille application météo ou un jeu sur sa tablette qu'on n'a pas ouvert depuis 3 ans, mais qui a toujours accès à votre localisation ou à vos photos.
* **Ce qu'on fait concrètement :**
  * **Faire le tour de la maison :** Lister tous les appareils connectés à Internet (ordinateurs, smartphones, box, téléviseurs connectés).
  * **Faire le grand ménage :** Désinstaller toutes les applications et programmes inutilisés depuis 6 mois. Moins il y a de fenêtres ouvertes sur l'extérieur, moins on risque les courants d'air.
* **L'œil du pro :** En entreprise, c'est ce qu'on appelle la *gestion des actifs* et la *réduction de la surface d'attaque*. Si l'informatique ne sait pas ce qui est branché sur le réseau, elle ne peut pas le mettre à jour.

---

## 🔑 3. Étape 2 : La fin de la clé sous le paillasson (Le *Passwordless*)
> *La règle d'or : Les mots de passe, c'est comme les brosses à dents : on ne les prête pas, on en change, et avouons-le, les nôtres sont souvent beaucoup trop faibles.*

* **Le problème :** Utiliser "Azerty123" ou le prénom de son chat partout, c'est donner le double de ses clés à tous les cambrioleurs du web. L'humain est nul pour retenir des suites de caractères complexes.
* **Le cas concret :** Réutiliser exactement le même mot de passe pour sa boîte mail principale, son site de e-commerce préféré et son espace bancaire. Si un site se fait pirater, le pirate a accès à toute votre vie.
* **Ce qu'on fait concrètement :**
  * **Option A (Le coffre-fort) :** Utiliser un gestionnaire de mots de passe (comme Bitwarden ou KeePass) pour ne plus avoir à en retenir qu'un seul, ultra-solide.
  * **Option B (Le futur / Le *Passwordless*) :** Supprimer le mot de passe quand c'est possible. On le remplace par un **objet physique** (une clé USB de sécurité, un badge) ou par la biométrie (empreinte digitale, reconnaissance faciale). Si on perd l'objet, on prévient le support, il est désactivé en deux clics.
* **L'œil du pro :** C'est la transition vers l'authentification forte (MFA/FIDO2). On élimine le facteur humain faible (le mot de passe devinable ou volé par phishing).

---

## 🎣 4. Étape 3 : Le réflexe du douanier (Déjouer les pièges)
> *La règle d'or : Face à un inconnu qui débarque en courant en criant au feu, on ne lui donne pas la caisse enregistreuse. On vérifie sa carte d'identité.*

* **Le problème :** Le phishing (l'hameçonnage) utilise l'urgence pour vous court-circuiter le cerveau : *"Votre colis est bloqué"*, *"Votre compte va être clôturé"*. 
* **Le cas concret :** Recevoir un SMS disant que le colis de Noël est bloqué, cliquer sur le lien, arriver sur un site parfait qui demande 2 euros de frais de port, et se faire piquer sa carte bancaire.
* **Ce qu'on fait concrètement :**
  * **La règle absolue du "souffle et clique ailleurs" :** Face à un e-mail ou un SMS alarmiste, **on ne clique jamais sur les liens du message**. 
  * On ferme le message, on ouvre son navigateur soi-même, on tape l'adresse officielle du site (par exemple laposte.fr) et on vérifie si le problème existe vraiment. L'urgence est l'arme numéro un du cambrioleur.
* **L'œil du pro :** C'est la sensibilisation comportementale. Aucun logiciel au monde ne peut empêcher un humain de cliquer s'il cède à la panique. La seule parade, c'est le réflexe de vérification.

---

## 💾 5. Étape 4 : Le double des clés chez les beaux-parents (La résilience)
> *La règle d'or : Si un virus bloque toutes les portes de la maison et prend vos souvenirs en otage, qu'est-ce qui se sauve ?*

* **Le problème :** Les ransomwares chiffrent vos fichiers et exigent une rançon. Si votre ordinateur plante, tout est perdu... sauf si vous avez une copie.
* **Le cas concret :** Le disque dur de l'ordinateur familial lâche du jour au lendemain, ou un virus bloque l'accès à toutes les photos de famille depuis 10 ans. 
* **Ce qu'on fait concrètement :**
  * **Faire une sauvegarde intelligente :** Mettre une copie de ses documents importants sur un support externe (un disque dur).
  * **Le piège à éviter :** Si le disque dur de sauvegarde reste branché en permanence sur l'ordinateur, le virus chiffrera l'ordinateur... **ET** la sauvegarde en même temps. La vraie sauvegarde, c'est le double des clés qu'on met chez les beaux-parents : on le branche pour copier, et on le débranche et le range en lieu sûr ensuite.
* **L'œil du pro :** En entreprise, c'est la mise en place de sauvegardes immuables et isolées (Air-Gapped), la pierre angulaire du Plan de Reprise d'Activité (PRA).
