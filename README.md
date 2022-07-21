# Tutoriel PyTorch

Bonjour,

Dans ce repository, vous trouverez tous les éléments principaux pour apprendre à maitriser PyTorch sur Python.

Ce repository est en cours de construction, il est possible qu'il manque certains cours essentiels pour la compréhension de PyTorch. Il sera rempli au fur et à mesure de l'écriture de ces cours.

Avant toute chose, veuillez lire cette courte introduction si jamais vous n'avez pas installé PyTorch sur votre ordinateur. 

# I. Installation d'Anaconda 3

Personnellement, j'utilise Anaconda 3 comme environnement virtuel. Si jamais vous ne souhaitez pas utiliser Anaconda 3, passez directement à la deuxième étape.  

Il existe plusieurs manières d'installer Anaconda 3 selon votre système d'exploitation. Je vous recommande d'aller sur la [documentation officielle d'Anaconda 3](https://docs.anaconda.com/anaconda/install/) et de suivre les étapes selon votre système d'exploitation. 

# II. Installation de CUDA 

CUDA (_Compute Unified Device Architecture_) est une technologie de GPGPU (_General-Purpose Computing on Graphics Processing Unit_) qui utilise le processeur graphique (GPU) pour exécuter des calculs généraux à la place du processeur central (CPU)

Pour ceux possédant un GPU compatible avec CUDA (principalement ceux possédant une carte graphique Nvidia), je vous invite à vous rendre sur le [lien officiel](https://developer.nvidia.com/cuda-11.3.0-download-archive) et de suivre les instructions d'installation afin d'installer CUDA sur votre ordinateur.

Cette étape est optionnelle, vous n'avez pas besoin d'installer CUDA pour pouvoir utiliser PyTorch. Néanmoins, cette étape permet d'améliorer la vitesse des calculs réalisés et de stocker sur différentes mémoires certaines variables, je vous recommande donc de la faire. 

# III. Installation de PyTorch 

Rendez-vous sur le [site internet d'installation de PyTorch](https://pytorch.org/get-started/locally/) et renseignez vos préférences d'installation. Il est recommandé de prendre la version stable de PyTorch pour éviter tout désagrémment pendant vos sessions de programmation. 

Après avoir choisi vos préférences, recopiez la ligne de commande dans votre terminal et attendez la fin de l'installation. 

Pour vérifier si l'installation a été effectué, lancer Python et importez PyTorch avec la commande "**import torch**". Si vous n'avez reçu aucune erreur, c'est que l'installation s'est effectuée correctement. 

_____________________________________________________________

Voilà, vous êtes prêts pour programmer de nombreuses Machines Learning avec PyTorch ! Amusez-vous bien ! 
