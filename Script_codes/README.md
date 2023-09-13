1D_convo : test sur figure en 1D                                                                                                                                                    #COMMENTÉ 
Beta_VAE_MNIST : Test de demelage sur MNIST                                                                                                                                         #COMMENTÉ

Courbe_parametre : Script avec les splines pour approximer les courbes des espaces latents du fichier hydro_1                                                                       #COMMENTÉ
gener_geo : fihcier pour generer les carrés cercles et triangles (Jean-Luc FEUGEAS)                                                                                                 #COMMENTÉ


Hydro_1 : Animation Hydro AE Simple                                                                                                                                                 #COMMENTÉ
Hydro_1VAE : Animation Hydro VAE                                                                                                                                                    #COMMENTÉ
hydri_IMAGE_UNIQUE : Animation hydro AE Simple entrée une image (instant t) et sortie (instant t+dt)                                                                                #COMMENTÉ


Circular_motion_learned [AE1 (AE) AE2 (AE)]: Prédiction sur phénomène physique convolutif AE simple + Partie METRIQUE                                                               #COMMENTÉ
Pendule_double_ae2 [AE1 (AE) AE2 (AE)] : Génération d'une base de données de 60000 de vecteur latent et AE2 en VAE (pour double pendule) "pas très utile"                           #COMMENTÉ


Pendule_AE [AE1 (AE) AE2 (VAE)] : VAE et AE + visualisation espace latent (et bdd 60k en utilisant un autoencodeur déjà construit) (pas très utile hmmm)                            #COMMENTÉ   
Pendule_VAE [AE1 (AE) AE2 (VAE+AE)] Prédiction sur phénomène physique convolutif VAE avec generation de BDD (de taille 60k) et visualisation ++ d'espace latent,
Visualisation des variables (sous forme de gif)                                                                                                                                     #COMMENTÉ


VAE_Circular_motion [AE1 (VAE)] Prédiction sur phénomène physique convolutif VAE                                                                                                    #COMMENTÉ
VAE_Circular_motion_60k [AE1 (VAE) AE2 (VAE+AE)] : Prédiction sur phénomène physique convolutif avec generation de BDD (de taille 60k) et visualisation ++ d'espace latent          #COMMENTÉ





Les scripts pour les prédictions contiennent une partie chargement de bases de données, une partie Encodeur-décodeur et une partie auto-encodeur 2. À cela s'ajoute suivant les fichiers des parties pour le visionnage des espaces latents, pour la création de métrique de stabilisation, pour l'impression des gifs des prédictions à long terme.

Tous les modèles ou bases de données à importer doivent être à l'exterieur du dossier contenant les codes. Les BDD doivent être dans un répertoire Datasets, les modèles dans un fichier Modele etc. (Voir au cas par cas).

