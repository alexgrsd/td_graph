# Reponses aux questions 

## Exercice 2 

- 1 : la struct WeightedGraph est dans DataStructure, elle sert a créer un graphe pondéré. Elle est utilisée pour stocker les infos sur un graphe pondéré et le manipuler facilement, pour par ex rajouter un sommet, lui donner un poid et une direction. 
La struct PositionnedGraph est dans osm, et elle sert a créer un graphe positionné. Elle peut les manipuler en rajoutant ou supprimant un sommet, et peut également les merge. Elle peut aussi renvoyer la liste des nodes. 

- 2 : Le module extraction 0SM sert a extraire les données d'un fichier OSM et à les convertir en un graphe positionné. 
La fonction simplify sert a simplifier le graphe en supprimant les noeuds proches entre eux.
Visualisation permet de visualiser le graphe dans une petite fenêtre graphique.

- 3 la fonction simplify est utilisée pour simplifier le graphe en supprimant les noeuds de degré 2 qui forment un angle proche de 180 degrés a 30 degrés de marge,  en regroupant les noeuds proches les uns des autres et en supprimant les petites branches. In fine elle crée un graphe plus simple.