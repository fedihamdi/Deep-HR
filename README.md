This project was coached and supervised by :

<center>


>> <span style="color:blue"> **Jean-Charles Tassan** </span> as the business coach : [LinkedIn](https://fr.linkedin.com/in/jean-charles-tassan-1a5011b) 

>> <span style="color:blue"> **Théo Gigant** </span> as the technical coach : [LinkedIn](https://fr.linkedin.com/in/theo-gigant) 

</center>
<center>

# Deep-HR
A toolbox of deep neural networks designed for HR to analyze emotions via facial expression, connecting images and HR description of the Person and classifying the profiles.
</center>

>> 

![ Demo ](https://github.com/fedihamdi/Deep-HR/blob/main/img/demo.png?raw=true)

<center>

# Membre du groupe

| Nom      | Prenom |   |
| :---        |    :----:   |          ---: |
| HAMDI      | Fedi       |    |
| CHIHAOUI   | Hamza        |       |
| DOUZI     | Ali       |    |
| GUEDROUZ  | Yassine        |       |
| MOUSSONO  | Alexia Promise  |     |
| MADENKO TADIE | Yverine | |

</center>

## Ressources

* Objectives & description: A dessein de permettre aux nouveaux consultants RH de mieux appréhender les entretiens clients pour une prestation donnée et ainsi agir sur le stress d'un échec éventuel, l'objectif sera de bâtir un classifieur à partir de photos clients qui ont déjà adhéré et les non-adhérents (en l'occurence ici, on s'appuiera sur ma base de données consultant). Cela permettra en amont au consultant de pouvoir obtenir un repère quant à une adhésion ou une non- adhésion éventuelle. La précision n'est pas fondamentale de prime abord dans la mesure où la prévision de l'issue de l'entretien orientera vers une stratégie plutôt active (être en confiance) ou passive (rester vigilant)

## Dependencies

* Google Colab

## Environement et Le *Stack* technologique

1. Uploader les notebook dans colab et tous ça marche bien

2. Pytorch, OpenCV, PIL,
```

```

3. Activer l'acces à google drive:
```
from google.colab import drive
drive.mount("drive/")
```


## Project structure

 
    


----- 


```
project
│   README.md
│   file001.txt    
│
└───Documents & Roadmap : contient la docummentation du ce projet.
|   |
│   │------- Résumé et ressources bibliographiques.docx
│   │------- Avancement Semaines.docx
│   │
│   └───Fiches tachniques
│       │   ...   
│       │
│       │
│   
└───Notebooks
    |
    │----- Notebook 1 _ Data preprocessing.ipynb : Contient le code
    |      qui permettent l'exploitation des images et les premiere 
    |      manipulation (i.e preprocess)
    |
    │----- Notebook 2 _ Suppression des fonds.ipynb : Contient 
    |      l'expérimentation de suppression des fonds des images en 
    |      utilisant Tensorflow
    |
    |----- Notebook 3 _ One shot classification avec Pytorch.ipynb
    |
    |----- [Intermediaire]_Conception_d'un_modèle_de_détection_d'émotion.ipynb
    |      Contient le code qui permet la création d'un modèle qui permet la détection
    |      et la reconnaissance des émotions
    |
    |----- Notebook_4_Emotion_detection.ipynb : Contient l'application
           du modèle responsable à la détection des émotions

```

## Appendix

the link to the ```HETIC PFA``` Folder is :

> ```https://drive.google.com/drive/folders/1oznqVEAUe_bNdDiS5Vi93s7h1RXzmwQh?usp=sharing```

the link to the ```All Ressources``` Folder is :

> ```https://drive.google.com/drive/folders/1ZMVFRWRhYpfg8qr3Idq6LMTeDa8XewL6?usp=sharing```