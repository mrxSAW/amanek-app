# 🛡️ Amanek (أمانكِ) — Outil Numérique Camouflé de Lutte contre les Violences faites aux Femmes

> **Projet développé dans le cadre du concours d'innovation numérique organisé par le Conseil National des Droits de l'Homme (CNDH) — Maroc.**

---

## 📋 Présentation du Projet

**Amanek** (*« Ta sécurité »*) est une application web progressive (PWA) conçue pour accompagner, protéger et orienter les femmes victimes de violences au Maroc, en s'appuyant sur les dispositions de la **Loi 103.13** relative à la lutte contre les violences faites aux femmes.

Face au contrôle numérique souvent exercé par l'agresseur sur le téléphone de la victime, Amanek adopte l'approche **"Privacy & Safety by Design"** : l'application se dissimule derrière une **calculatrice fonctionnelle** et ne dévoile son espace sécurisé qu'après la saisie d'un code secret.

---

## 🔐 Fonctionnement du Code Secret (`10313`)

Le mécanisme de déverrouillage discret est au cœur de la sécurité de l'application :

* **Pourquoi le code `10313` ?** Ce chiffre est un hommage direct à la **Loi n° 103.13** promulguée au Maroc pour la lutte contre les violences faites aux femmes, rendant le code facile à mémoriser dans un contexte de sensibilisation tout en restant anodin sur une calculatrice.
* **Comment ça marche techniquement ?**
  1. **Mode Camouflage (Par défaut) :** Tant que le code n'est pas saisi, l'application exécute de véritables opérations mathématiques (`+`, `-`, `×`, `÷`). Si une tierce personne ouvre l'application, elle ne voit qu'une calculatrice ordinaire.
  2. **Déclenchement Silencieux :** Lorsque l'utilisatrice tape la séquence **`10313`** puis appuie sur la touche **`=`**, le script intercepte la chaîne avant tout calcul mathématique, masque instantanément le clavier de la calculatrice et déverrouille le tableau de bord **« مساحة أمانكِ » (Espace Sécurité)**.
  3. **Verrouillage d'Urgence (Bouton `خروج سريع ✕`) :** À tout moment, un simple clic sur le bouton rouge de sortie rapide efface la session visuelle et réaffiche immédiatement l'interface de la calculatrice.

---

## ✨ Fonctionnalités Principales

* **🎭 Camouflage Intelligent :** Interface extérieure 100 % opérationnelle permettant d'effectuer des calculs réels sans éveiller de soupçons.
* **🚨 Bouton de Sortie Rapide (Panic Button) :** Bascule instantanée vers la calculatrice en cas d'intrusion.
* **🆘 Alerte SOS Silencieuse avec Géolocalisation :** Récupération automatique des coordonnées GPS et envoi d'une alerte discrète aux contacts de confiance.
* **📸 Coffre-fort Numérique Chiffré (Preuves) :** Capture de photos et d'enregistrements vocaux horodatés, stockés de manière sécurisée sans laisser de trace dans la galerie du téléphone.
* **🗣️ Assistance Vocale Inclusive :** Guide juridique et psychologique accessible en **Darija**, **Amazighe** (Tarifit, Tamazight, Tachelhit) et **Arabe** pour garantir l'accès aux femmes en milieu rural ou non alphabétisées.
* **📍 Cartographie des Structures d'Aide :** Localisation des cellules de prise en charge des femmes victimes de violences (hôpitaux, tribunaux, associations, sûreté nationale).

---

## 🛠️ Stack Technique

* **Frontend :** HTML5, CSS3 (Responsive Design / Mobile-First), JavaScript Vanilla (ES6+).
* **APIs Web Natives :** `Geolocation API` (localisation d'urgence), `Web Storage / IndexedDB` (stockage sécurisé).
* **Déploiement :** Compatible PWA (Progressive Web App) installable sur Android et iOS.

---

## 🚀 Installation et Utilisation

### 1. En local (Sur ordinateur)
1. Clonez ce dépôt :
   ```bash
   git clone [https://github.com/mrxSAW/amanek-app.git](https://github.com/mrxSAW/amanek-app.git)