# TD Ordonnancement Temps Réel - Résolution Interactive

Ce dépôt contient la résolution complète et détaillée d'une série d'exercices (TD Série 03) portant sur l'ordonnancement des systèmes temps réel et des systèmes d'exploitation. 

Le projet prend la forme d'un document HTML "Single-Page" (page unique) richement formaté, incluant les calculs, les interprétations et des diagrammes de Gantt natifs en CSS.

## 🚀 Fonctionnalités

* **Diagrammes de Gantt 100% CSS :** Les séquencements des tâches sont dessinés visuellement sans utiliser de bibliothèques graphiques lourdes (comme Chart.js ou D3.js). Tout est fait en HTML/CSS pur pour une légèreté maximale.
* **Support Mathématique :** Intégration de MathJax pour un rendu propre et professionnel des formules mathématiques et des calculs de facteurs d'utilisation (Critère de Liu & Layland, etc.).
* **Design Responsive et Accessible :** Une interface utilisateur claire, avec un code couleur par tâche pour faciliter la lecture des préemptions et des diagrammes.

## 📋 Contenu du TD

Le document couvre les algorithmes d'ordonnancement suivants :

* **Exercice 1 :** Rate Monotonic (RM) et test de Liu & Layland.
* **Exercice 2 :** Comparaison entre RM et Earliest Deadline First (EDF) avec calcul du taux d'utilisation.
* **Exercice 3 :** Application croisée de RM, EDF et Least Laxity First (LLF) sur un jeu de tâches à période égale à l'échéance.
* **Exercice 4 :** Analyse de systèmes où l'échéance est inférieure à la période (D < P) via RMA, DMA (Deadline Monotonic) et EDF.
* **Exercice 5 :** Analyse des diagrammes produits par DM et EDF.
* **Exercice 6 :** Ordonnancement de processus (OS) classique avec FCFS, Round Robin (RR) et SJF Préemptif (SRTF), incluant les calculs des temps de rotation (TAT) et d'attente (WT).

## 🛠️ Comment utiliser ce projet

Puisqu'il s'agit d'un simple fichier HTML autonome, son utilisation est extrêmement simple :

### En local
1. Clonez ce dépôt ou téléchargez le fichier `index.html`.
2. Double-cliquez sur `index.html` pour l'ouvrir dans n'importe quel navigateur web moderne (Chrome, Firefox, Safari, Edge).
3. Une connexion internet est requise uniquement lors du premier chargement pour récupérer le script *MathJax* (qui formate les équations).

### Hébergement via GitHub Pages
Ce dépôt est prêt à être hébergé gratuitement via GitHub Pages :
1. Allez dans les paramètres de votre dépôt GitHub (**Settings**).
2. Dans la barre latérale gauche, cliquez sur **Pages**.
3. Sous *Source*, sélectionnez la branche `main` (ou `master`) et le dossier `/root`.
4. Cliquez sur **Save**. Votre lien sera généré d'ici quelques minutes !

## 👨‍💻 Technologies Utilisées

* **HTML5** (Structure sémantique)
* **CSS3** (Flexbox pour les diagrammes de Gantt, Variables de couleurs)
* **MathJax** (Interprétation des balises LaTeX pour les mathématiques)
