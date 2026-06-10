# LAB-1-HelloToast-Manipuler-les-composants-et-les-v-nements
markdown_content = """# LAB-20 : Création d'une application Android basique (Toast & Compteur)

> **Objectif pédagogique :** Ce lab d'initiation permet de se familiariser avec l'environnement Android Studio, la création d'interfaces utilisateur (UI) en XML, et la gestion des événements (clics) dans le code source.

## 📝 Contexte et But du Lab
L'objectif est de créer une petite application Android fonctionnelle comprenant :
* **Un affichage (TextView)** : pour montrer un compteur numérique.
* **Un premier bouton (Toast)** : qui, lorsqu'on clique dessus, affiche un message éphémère au bas de l'écran (un "Toast").
* **Un second bouton (Compteur)** : qui incrémente le nombre affiché à l'écran à chaque clic.

---

## 🛠️ Environnement de Travail

| Élément | Spécification / Détail |
| :--- | :--- |
| **IDE** | Android Studio |
| **Langage** | Java (ou Kotlin) |
| **Interface** | XML (Android Layout) |
| **Cible** | Émulateur Android (API 24+) ou appareil physique |

---

## 🚀 Guide Opérationnel Étape par Étape

### Étape 1 — Création du projet dans Android Studio
1. Ouvrez Android Studio et cliquez sur **New Project**.
2. Choisissez le modèle **Empty Views Activity** (ou *Empty Activity* selon la version).
3. Nommez l'application (ex: `ToastAndCountApp`), choisissez **Java** comme langage, et cliquez sur **Finish**.

---

### Étape 2 — Conception de l'interface utilisateur (XML)
Le fichier d'interface gère la disposition visuelle des éléments. Nous allons utiliser un `LinearLayout` pour empiler nos éléments verticalement.

Ouvrez le fichier `res/layout/activity_main.xml` et remplacez son contenu par le code suivant :
