# 🧠 Résolution de Labyrinthe avec IA

Ce projet explore la résolution de labyrinthes à l’aide de différents algorithmes de recherche classiques en intelligence artificielle :  
**DFS (Depth-First Search), BFS (Breadth-First Search), Dijkstra et A\***.

Le labyrinthe est généré aléatoirement, puis modélisé sous forme de graphe non orienté.  
Chaque algorithme est appliqué pour trouver un chemin entre le départ et l’arrivée, avec des comparaisons selon :

- 🔍 le **nombre de nœuds explorés**
- 🛣️ la **longueur du chemin trouvé**
- ⏱️ le **temps d'exécution**
- 📉 le **ratio d’exploration** = *nœuds explorés / taille du graphe*

Le labyrinthe et son graphe sont visualisés avec `matplotlib` et les données affichées avec `pandas` pour mieux comprendre les différences de comportement.

---

### 🇬🇧 A note in English

This notebook was written in French as part of a school project.  
However, **all code cells are fully understandable and reproducible**.
---

### 👩‍💻 Auteur

Créé par **Nadia Simard-Villa**  
Étudiante en AEC Internet des objets et Intelligence artificielle  
Collège Ahuntsic – Printemps 2025

Encadré par Thibault D'heilly, enseignant en informatique.

---

### 📁 Fichiers
- `labyrinthe_IA.ipynb` – Notebook principal
- `README.md` – Présentation du projet

---

### 📌 Objectifs pédagogiques
- Implémenter et comparer des algorithmes classiques de recherche
- Comprendre les impacts de différentes stratégies sur un graphe
- Visualiser les performances et métriques de manière intuitive

---

### 🧰 Technologies utilisées
- Python 3 (Google Colab)
- `pandas`, `matplotlib`, `time`, `random`, `math`

