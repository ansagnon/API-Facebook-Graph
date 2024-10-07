# API-Facebook-Graph
Extraction des données de migrations à partir de l'API Marketing Facebook Graph et construction d'un outil d'alerte précoce des flux migratoires au Burkina Faso.

**********************************

Lorsque vous souhaitez boostez une publication sur Facebook, le média social social vous permet de definir les caractéristiques de la populations que vous souhaitez ciblées (vous pouvez, par exemple, choisir de cibler les femmes de 18 a 35 ans, vivant a Bobo Dioulasso et utilisant un téléphone i_phone 14 ). Une fois que vous définissez la population ciblée, Facebook vous donne une estimation du nombre de personnes que votre publication pourrait atteindre, ce qui correspond a priori a une estimaton du nombre d'utilisateur de Facebook respectant les caractéristiques de population spécifiées.

L'idée de ce projet est de recupérer de maniere programmatique, les estimations d'audiiances de Facebook a l'aide de l'API Marketing Facebook Graph. Les caractéristiques comportementaux de population a estimer devraient ressembler a ceci.
*  Nombre d'utilisateur de Facebook qui vivaient à Bobo Dioulasso et qui vivent desormais a Ouagadougou
*  Nombre d'utilisateur de Facebook qui vivaient à Ouagadougou et qui vivent desormais a Bobo Dioulasso
*  Nombre d'utilisateur de Facebook qui vivaient à Ouagadougou et qui vivent desormais a Koudougou
*  etc. 

L'objectif de ce projet est de construire un outil d'alerte des flux de migration interne au Burkina Faso a partir de source de données innovantes (non traditionelle). Pour ce faire les objectifs spécifiques sont :
* Extraction des données de migrations a partir de l'API Marketing Facebook Graph
* Utilisation des methodes d'inférence statistqiues et de correction de biais
* Construction d'un outil d'alerte précoce.
