# projet_etl

# récupérer le csv 
# extraire la colone département
# extraire les 2 premier chiffres de la colone
# extraire les évaluations 
# extraire les noms des restaurants 
# extraire le numéro d'inspection (utiliser comme id)
# PowerBi -> dataviz

# commit_1
# j'ai vérifier les types d'évaluation possible avec tuniquerow, tmap et tlogrow il y en a 4
# |Satisfaisant|Très satisfaisant|A améliorer|A corriger de manière urgente|
# j'ai remplacé ces évaluation par 0 pour l'évaluation la plus mauvaise et 3 our la meilleur etc 
# pour ça j'ai utilisé une regle dans tmap
# j'ai aussi extrait les 2 premiers chiffres des codes postaux à l'aide d'une regle tmap
# j'ai enlevé les doublons avec tuniq 
# j'ai tout mis dans une base de données sous forme de deux tables communes qui contient les numéros de département et evaluation_id qui contient : numero d'inspection, l'évaluation en int et le nom des resaurants.
