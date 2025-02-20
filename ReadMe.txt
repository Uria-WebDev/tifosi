Script d'import : 
	mysql -u tifosi -p RSpa5*9CGfwujqig tifosi < Chemin_Du_Fichier/tifosi.sql



Script d'insertion : 
	INSERT INTO Table (colonne_1, colonne_2, colonne_3)

                              VALUES (valeur_1, valeur_2, valeur_3),

                                           (valeur_1, valeur_2, valeur_3),

                                           (valeur_1, valeur_2, valeur_3);​



Script de backup : 
	mysqldump - u tifosi - p RSpa5*9CGfwujqig tifosi > Chemin_Pour_Backup/Nom_De_Backup.sql