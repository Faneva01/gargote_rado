# gargote_rado

Recoltes des données:
Une salle, 8 tables, deux serveurs, une cuisinière, chargé clientèle.

## Etape 1: La carte
<< Je veux la liste de mes plats avec leur prix >>

### Table plat:

plat( **id_plat** , nom_plat , categorie, prix)

- `**id_plat**`: Identifiant unique, clé primaire
- `nom_plat`: nom du plat, obligatoire
- `categorie`: nom de la categorie
- `prix` : Prix du plat, obligatoire

### Contraintes
    - `id_plat` est unique à chaque plat
    - `nom_plat` est obligatoire
    -  `prix` est un entier est obligatoire

### Données de test

7 Plats inserés au debut

### Reponse aux questions `Piège`: 
- J'ai choisi le type integer pour le prix parce que selon les consignes, on utilisera toujours des prix exactes en entier.

- J'ai mis `id_plat`comme identifiant unique à chaque plat qui permet fcilement d'identifier chaque plat.

