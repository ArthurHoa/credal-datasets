# Credal Datasets

## Presentation

## Reference

When using one of those datasets please refer to :  
C. Thierry, A. Hoarau, A. Martin, J.-C. Dubois, Y. Le Gall, Real bird
dataset with imprecise and uncertain values, in: *7th International Con-
ference on Belief Functions*, 2022.

## Descriptions

Each dataset has its own directory:

```bash
Repository
├── Credal Dog-7
├── Credal Dog-4
├── Credal Dog-2
├── Credal Bird-10
└── Credal Dog-2
```

Within a dataset, you can find the dataset itself in *data* and additional resources in *extra* :

```bash
Credal dataset
├── data
│   ├── classes.csv: Classes of the dataset
│   ├── X.csv: Features of the dataset
│   ├── X_512.csv: Learge 512 features vector of the dataset
│   ├── X_pictures.csv: Rawn features (The picture itself)
│   ├── y.csv: Rich labels
│   └── y_true.csv: True labels
└──  extra
    ├── y_hard.csv: Hard labels given during a new campaign
    ├── DATA_imperfect.csv: Imperfect answers given during the campaign
    ├── ITERATION_imperfect.csv: Imperfect 2nd step answers given during the campaign
    ├── EVENT_imperfect.csv: Contributors events
    ├── ID_imperfect.csv: Contributors IDs
    └── DATA_perfect.csv: Precise answers given during a new campaign
```

### Access to pictures
You can access all the pictures and decide to use them as observations by following this link : [Credal Datasets Pictures](https://www.dropbox.com/sh/fwc4xf09ti12dt3/AADJNlncG6b3Z_3jdiVUsnTha?dl=0)  
Refer to data/X_pictures.csv to know which picture corresponds to which observation.

## Credal Dog-7

Welsh Corgi | Collie | Shetland Sheepdog | Foxhound | Basset | Brittany | Beagle
:--:|:--:|:--:|:--:|:--:|:--:|:--:
<img src="ressources/pictures/Welsh_Corgi.jpg" width="70"> | <img src="ressources/pictures/Collie.jpg" width="70"> | <img src="ressources/pictures/Shetland_Sheepdog.jpg" width="70"> | <img src="ressources/pictures/Foxhound.jpg" width="70"> | <img src="ressources/pictures/Basset.jpg" width="70"> | <img src="ressources/pictures/Brittany.jpg" width="70"> |  <img src="ressources/pictures/Beagle.jpg" width="70">)  

## Credal Dog-4

Foxhound | Basset | Brittany | Beagle
:--:|:--:|:--:|:--:
<img src="ressources/pictures/Foxhound.jpg" width="70"> | <img src="ressources/pictures/Basset.jpg" width="70"> | <img src="ressources/pictures/Brittany.jpg" width="70"> |  <img src="ressources/pictures/Beagle.jpg" width="70">)  

## Credal Dog-2

Brittany | Beagle
:--:|:--:
<img src="ressources/pictures/Brittany.jpg" width="70"> |  <img src="ressources/pictures/Beagle.jpg" width="70">)  

## Credal Bird-10

Carrion Crow | Common Raven | Rook | Western Jackdaw | European Robin
:--:|:--:|:--:|:--:|:--:
<img src="ressources/pictures/Carrion_Crow.jpg" width="100"> | <img src="ressources/pictures/Common_Raven.jpg" width="100"> | <img src="ressources/pictures/Rook.jpg" width="100"> | <img src="ressources/pictures/Western_Jackdaw.jpg" width="100"> | <img src="ressources/pictures/European_Robin.jpg" width="100">  

Coal Tit| Great Tit | Marsh Tit | Common Wood Pigeon | Rock Dove
:--:|:--:|:--:|:--:|:--:
<img src="ressources/pictures/Coal_Tit.jpg" width="100"> | <img src="ressources/pictures/Great_Tit.jpg" width="100"> | <img src="ressources/pictures/Marsh_Tit.jpg" width="100"> | <img src="ressources/pictures/Common_Wood_Pigeon.jpg" width="100"> | <img src="ressources/pictures/Rock_Dove.jpg" width="100">  

## Credal Bird-2

Western Jackdaw | Rook
:--:|:--:
<img src="ressources/pictures/Western_Jackdaw.jpg" width="100"> | <img src="ressources/pictures/Rook.jpg" width="100">

## Acknowledgement