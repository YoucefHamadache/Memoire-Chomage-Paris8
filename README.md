# Mémoire – Le Chômage : Mécanisme et Reproduction de Graphiques

**Université Paris 8 – Année 2023-2024**  
Enseignante encadrante : PIZZO Alessandra  

Auteurs :  
- Hamadache Youcef  
- Rahou Aymen  
- Zenagui Walid  


## Objectif du Mémoire

Ce mémoire a pour objectif de reproduire et d’analyser certains résultats de l’article académique :

**Cairo, I. & Cajner, T. (2018)**  
*“Human Capital and Unemployment Dynamics: Why More Educated Workers Enjoy Greater Employment Stability”*  
(The Economic Journal)

L’étude analyse les dynamiques du chômage en fonction du niveau d’éducation et met en évidence l’impact du capital humain sur :

- Le taux de chômage
- La volatilité du chômage
- Les flux d’entrée (inflow rate)
- Les flux de sortie (outflow rate)


## Problématique

Pourquoi les travailleurs plus éduqués bénéficient-ils d’une plus grande stabilité d’emploi ?

Le mémoire montre que :

- Les individus moins éduqués subissent des taux de chômage plus élevés
- Les taux de séparation sont plus volatils pour les travailleurs peu qualifiés
- L’éducation agit comme un signal de productivité (théorie du capital humain – Spence)
- La formation continue renforce la stabilité d’emploi

## Méthodologie

Les analyses reposent sur les données du **Current Population Survey (CPS)** couvrant la période **1976–2015**.

Les principales étapes réalisées :

- Importation et traitement des données en R
- Calcul du taux de chômage global et par niveau d’éducation
- Reconstruction des séries des chômeurs de courte durée
- Calcul :
  - Probabilité de sortie mensuelle (Ft)
  - Taux de risque (ft)
  - Inflow rate
  - Outflow rate
- Lissage des séries (méthode LOESS)
- Reproduction des graphiques de l’article original


## Résultats Principaux

Les résultats confirment :

- Une corrélation négative forte entre niveau d’éducation et taux de chômage
- Une plus grande stabilité d’emploi pour les diplômés universitaires
- Une sensibilité accrue des travailleurs peu qualifiés aux cycles économiques
- L’importance de l’investissement dans l’éducation et la formation continue


## Outils Utilisés

- **R**
- Analyse de séries temporelles
- Méthode de lissage LOESS
- Traitement de données économiques longitudinales



## Références Académiques

- Cairo, I., & Cajner, T. (2018). Human Capital and Unemployment Dynamics.
- Shimer, R. (2012). Reassessing the ins and outs of unemployment.
- Mortensen & Pissarides (1994). Job creation and job destruction.
- Nickell, S. (1979). Education and lifetime patterns of unemployment.



## Conclusion

Ce mémoire met en évidence le rôle central du capital humain dans la stabilité du marché du travail.  
L’éducation apparaît comme un facteur déterminant de résilience face aux fluctuations économiques.

Il souligne l’importance des politiques éducatives et des programmes de formation continue pour réduire les inégalités face au chômage.

---

📎 Le document complet est disponible dans ce repository au format PDF.
