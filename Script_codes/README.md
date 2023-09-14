
#### La plupart des codes ici sont similaires : Ils contiennent une importation de données, l'entrainement d'un encodeur-décodeur et l'entrainement d'un auto-encodeur pour la reconstruction des vecteurs latents du premier. Certains d'entre eux sont spécifiques à des bases de données bien précises (Simulation hydrodynamique par exemple) et nécessite une importation différente, ou à des structures d'auto-encodeurs particulières etc...

**1D_convo** : test sur figure en 1D                                                                                                                                                     
**Beta_VAE_MNIST** : Test de demelage sur MNIST                                                                                                                                      

**Courbe_parametre** : Script avec les splines pour approximer les courbes des espaces latents du fichier hydro_1                                                                       
**gener_geo** : fihcier pour generer les carrés cercles et triangles (Jean-Luc FEUGEAS)                                                                                               


**Hydro_1** : Animation Hydro AE Simple                                                                                                                                                 
**Hydro_1VAE** : Animation Hydro VAE                                                                                                                                                    
**hydri_IMAGE_UNIQUE** : Animation hydro AE Simple entrée une image (instant t) et sortie (instant t+dt)                                                                                


**Circular_motion_learned** [AE1 (AE) AE2 (AE)]: Prédiction sur phénomène physique convolutif AE simple + Partie METRIQUE                                                               
**Pendule_double_ae2** [AE1 (AE) AE2 (AE)] : Génération d'une base de données de 60000 de vecteur latent et AE2 en VAE (pour double pendule) "pas très utile"                          


**Pendule_AE** [AE1 (AE) AE2 (VAE)] : VAE et AE + visualisation espace latent (et bdd 60k en utilisant un autoencodeur déjà construit) (pas très utile hmmm)                               
**Pendule_VAE** [AE1 (AE) AE2 (VAE+AE)] Prédiction sur phénomène physique convolutif VAE avec generation de BDD (de taille 60k) et visualisation ++ d'espace latent,
Visualisation des variables (sous forme de gif)                                                                                                                                     


**VAE_Circular_motion** [AE1 (VAE)] Prédiction sur phénomène physique convolutif VAE                                                                                                    
**VAE_Circular_motion_60k** [AE1 (VAE) AE2 (VAE+AE)] : Prédiction sur phénomène physique convolutif avec generation de BDD (de taille 60k) et visualisation ++ d'espace latent         





Les scripts pour les prédictions contiennent une partie chargement de bases de données, une partie Encodeur-décodeur et une partie auto-encodeur 2. À cela s'ajoute suivant les fichiers des parties pour le visionnage des espaces latents, pour la création de métrique de stabilisation, pour l'impression des gifs des prédictions à long terme.

Tous les modèles ou bases de données à importer doivent être à l'exterieur du dossier contenant les codes. Les BDD doivent être dans un répertoire Datasets, les modèles dans un fichier Modele etc. (Voir au cas par cas).

