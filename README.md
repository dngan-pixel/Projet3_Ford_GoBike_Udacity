
# EXPLORATION Ford GoBike 
## by Ngan Desire


## Presentation Ford Gobike:

**Ford GoBike** est un service de velo-partage lancé par l'entreprise Ford dans la ville de San francisco.Nous avons dans le cadre de notre travail eu a analyser la structure du jeu de donnée(1) et en second lieu faire un nettoyage(2) avant l'exploration.

### Structure des données de Ford GoBike
Le jeu de données **Ford GoBike** est constitué de 183412 échantillions(lignes) et de 16 colonnes.les colonnes sont constituées des noms de colonnes suivants:**duration_sec,start_time,end_time,start_station_id,start_station_name , start_station_latitude,start_station_longitude,bike_id,user_type,member_birth_year,member_gender,bike_share_for_all_trip.**

### Nettoyage de Ford GoBike

Aprés une analyse préliminaire de notre jeu de données,il en est ressorti des problèmes de qualité et d'ordre suivant qu'il nous a fallut ressorber:


- Présence des valeurs manquantes Les attributs start_station_id, start_station_name, end_station_name ,end_station_name

- Les attributs start_time,end_time sont du type objet au lieu de datetime

- Les colonnes qui ne nous serviront pas seront éliminées:**start_station_name, end_station_name**

- Calculer les ages à partir de la date de naissance des membres.

- Calculer la distance parcourue entre 2 points a partir des attributs start_station_latitude,start_station_longitude,end_station_latitude,end_station_longitude

- Changer les types de start_station_id,end_station_id en integer

- Créer des colonnes start_date_time,end_date_time,start_hours_time,end_hour_time

 
## Resume des observations

 Notre étude exploratoire s'est concentrée sur la variable d'interet member_gender pour comprendre les habitudes de consommation des differents genres.Pour ce faire apres le nettoyage nous nous sommes appuye sur les attributs suivants:**duration_sec,la distance_travel,bike_id,user_type,age_member,start_time_weekdays,start_time_hour et enfin bike_share_for_all_trip**.
 
### Analyse univariée

- Les hommes participent le plus aux courses organisées.

-La journée de Jeudi est celle qui voit le plus de participation aux courses tandisque les week-ends sont les moins frequentes(samedi,dimanche).

-La grande majorité des participants ont un age compris entre 20 et 70 ans.

### Analyse bivariée

- La relation qui lie l'age et la distance parcourue est constante

-On remarque que pour les distributions sont les memes pour les trois genres et on remarques la présence des valeurs abérrantes

-On remarque qu'il y'a moins de consommateur chez les hommes que les autres catégories mais ils ont plus de consommateur que les autres genres repertoriéss marquées pour les hommes.

-Le Jeudi est le jour ou toutes les categories confondues assistent le plus aux courses par contre tres peu sont présent les week_ends(Samedi,dimanche)

### Analyse multivariée

On remarque qu'en considérant la durée des courses par semaine en moyenne les autres genres durent beaucoup plus longtemps que les hommes et les femmes.

## Informations clés pour la présentation

La présentation va porter sur 06 qui sont les suivantes:

-Le diagramme en cercle des différents genres(diagramme en cercle)

-Les jours de départ des courses(diagramme en barre)

-La répartition de la distribution des ages(histogramme)

-La repartition entre les genres et les jours de courses(Double diagramme en barre)

-La répartition des genres en fonction des types de consommateur(diagramme en barre)

-La répartition des genres en fonction de la durée du parcours et des journees de la semaine.

L'essentiel des modifications sur les graphes seront mettre sur les diagrammes en barres les pourcentages,modificier les couleurs 
pour les rendre les plus visibles,affininer les axes et les légendes,m'assurer tout les graphes ont des axes des abscisses et des ordonnées.
