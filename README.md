
# 📄 Cahier des Charges – Projet 1 : Application de Chat via Email

## 1. 🎯 Présentation du Projet

Ce projet a pour objectif de développer une application de **messagerie instantanée** inspirée de WhatsApp, mais reposant sur les **adresses email comme identifiants uniques** des utilisateurs. Il s’agit d’une **application client-serveur desktop** utilisant les **sockets TCP/UDP en Java** pour assurer la communication en temps réel.

## 2. 🗂️ Périmètre du Projet

Le projet est structuré en deux niveaux :

* **Niveau de base** : Développement des fonctionnalités fondamentales de messagerie **sans interface graphique**.
* **Niveau avancé** : Ajout d’une interface graphique, intégration d’une **base de données**, modélisation UML, chiffrement, et extensions fonctionnelles.

## 3. ✅ Fonctionnalités

### 3.1 Niveau de base

* Enregistrement et **authentification par email**.
* Envoi et réception de **messages texte** en temps réel via **sockets TCP/UDP**.
* Gestion des **connexions/déconnexions** des utilisateurs.
* **Stockage temporaire** des messages pour les utilisateurs hors ligne.
* **Validation** et **gestion des erreurs** des données échangées.

### 3.2 Niveau avancé

* **Interface graphique** (JavaFX ou Swing) simple et intuitive.
* **Système de contacts** : ajout, suppression, affichage du statut en ligne/hors ligne.
* **Base de données relationnelle** (MySQL/PostgreSQL/SQLite) pour le stockage des messages.
* **Groupes de discussion** avec gestion des membres.
* **Notifications** sonores/visuelles pour les nouveaux messages.
* Prise en charge des **fichiers multimédias** : images, audio, vidéo.
* **Historique des conversations** accessible à l’utilisateur.
* 🔐 **Chiffrement des messages** pour assurer la **confidentialité** des communications entre les utilisateurs, en utilisant des bibliothèques de cryptographie Java (ex. : **Bouncy Castle**).

## 4. ⚙️ Contraintes Techniques

* **Langage** : Java
* **Communication** : Sockets TCP et UDP
* **Base de données** : MySQL / PostgreSQL / SQLite
* **Interface graphique** : JavaFX ou Swing
* **Architecture** : Client-serveur
* **Sécurité** : Intégration de mécanismes de chiffrement symétrique ou asymétrique pour les messages

## 5. 🔧 Modélisation UML

* **Diagramme de classes** : structure des objets.
* **Diagrammes des cas d'utilisation** : interactions entre les acteurs et le système.
* (Optionnel) Diagrammes de séquence pour les scénarios clés.

## 6. 🚀 Déploiement

* Application conçue pour être installée sur des **ordinateurs de bureau**.
* Distribution sous forme de **fichier exécutable `.jar`**.
* Déploiement possible en local ou sur un réseau local (LAN).

## 7. 🗓️ Planification du Développement

### Phase 1 : Niveau de base

* Communication réseau via sockets.
* Authentification et gestion de sessions.
* Envoi/réception de messages texte.

### Phase 2 : Niveau avancé

* Développement de l’interface graphique.
* Intégration de la base de données.
* Gestion des contacts, groupes et historique.
* Ajout de la **gestion des médias**, notifications, et **chiffrement**.

## 8. 🧠 Conclusion

Ce projet a pour vocation d’initier les élèves ingénieurs à la **programmation réseau**, au **développement d’applications Java complexes**, et à la **sécurisation des échanges** par **chiffrement**. Il s’inscrit dans une démarche pédagogique complète, alliant logique client-serveur, interfaces graphiques, gestion des données et sécurité.


