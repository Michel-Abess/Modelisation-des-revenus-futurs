=============================================================================
Effectuez une prédiction de revenus
=============================================================================

l'objectif de ce travail est de créer un modèle permettant de déterminer le revenu potentiel d'une personne. Il est en ligne avec les travaux sur la banque mondiale sur la mobilité intergenerationnelle du revenu

ce modèle prends en compte comme variable:
	- le revenu des parents ;
	- le revenu moyen du pays dans lequel habite le prospect ;
	- l'indice de Gini calculé sur les revenus des habitants du pays en question. 

==============================================================================
Files
==============================================================================

Ce fichier contient les données de la World Income Distribution, datée de 2008.

Cette base de données est composée principalement d'études réalisées au niveau national pour bon nombre de pays, et contient les distributions de revenus des populations concernées.

Les indices de Gini sont estimés par la Banque mondiale et disponible sur leur site. De plus, ils ont été aussi recalculer à partir des données de la World Income Distribution.

le nombre d'habitants de chaque pays présent dans votre base provient de la base de données de la banque mondiale.
	
==============================================================================
How to open file : predire_des_revenus_futurs.ipynb in jupyter notebook
==============================================================================

S'assurer que le chemin d'accès aux fichiers est bien spécifié pour que le notebook puisse charger les données. Les fichiers peuvent être placés à la racine du dossier(Au même niveau que /predire_des_revenus_futurs.ipynb)

Open terminal and use the following command line:
	- ipython notebook detection de predire_des_revenus_futurs.ipynb
 	- jupyter notebook detection de predire_des_revenus_futurs.ipynb
If you haven't installed python yet, you can use the command line: pip install ipython 


