todo_content = """
# TODO LIST - PROJET DATA MINING (FUSION SÉANCES 1 & 2)

## 1. NETTOYAGE (CRITIQUE)
[x] Charger le CSV avec les bons paramètres (on_bad_lines, sep)
[x] Supprimer les colonnes vides (les virgules de fin)
[ ] Supprimer les lignes sans TAGS (dropna subset=['tags'])
[ ] Supprimer les doublons
[ ] Filtrer les coordonnées GPS (Garder uniquement Lyon)

## 2. VISUALISATION
[ ] Afficher la carte de Lyon (Folium)
[ ] Afficher un échantillon de points bruts

## 3. CLUSTERING (ALGORITHMES)
[ ] Standardiser les données (StandardScaler sur Lat/Long)
[ ] Trouver le k optimal (Courbe Elbow)
[ ] Exécuter K-Means
[ ] Exécuter DBSCAN (Ajuster eps et min_samples)
[ ] Visualiser les clusters sur la carte (Couleurs différentes)

## 4. TEXT MINING (SENS)
[ ] Fonction pour récupérer les tags d'un cluster
[ ] Nettoyer les tags (enlever les guillemets, tout mettre en minuscule)
[ ] Afficher les 10 mots les plus fréquents par cluster

## 5. ANALYSE (POUR LE RAPPORT/DEMO)
[ ] Vérifier la diversité des utilisateurs par cluster (éviter le spam)
[ ] Comparer K-Means (zones rondes) vs DBSCAN (zones de forme libre)
"""

with open('TODO.txt', 'w', encoding='utf-8') as f:
    f.write(todo_content)

print("Le fichier TODO.txt a été créé ! Tu peux l'ouvrir pour suivre ton avancement.")