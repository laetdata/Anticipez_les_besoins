# Anticipez les besoins en consommation de batiments

<div>
    <img Align="left" alt="Seattle" width="200px" src="https://github.com/laetdata/Anticipez_les_besoins/blob/main/img/seattle.png" style="padding-right:10px;" />
</div>
<br />
                                                                                                                                           

---

Nous avons travaillé pour la ville Seattle. Pour atteindre son objectif de ville neutre en émissions en 2050, notre équipe s'est interessée de près à la consommation et aux émissions des batiments non définies à l'habitation. 

---
<br />
<br>
Notre mission était de tenter de prédire les émissions de CO2 et la consommation totale d'énergie de bâtiments non destinés à l'habitation. Nous devions aussi juger de l'intérêt  de l'EnergyStarScore pour la prédiction.  

Nos prédictions devront se baser sur les données structurelles des bâtiments (taille et usage des bâtiments, date de construction, situation géographique,...).

Pour atteindre nos objectifs, nous devions réaliser une courte analyse exploratoire puis tester differents modèles de prédiction. 

Nous devrions faire attention au traitement des differentes variables et optimiser les performances en appliquant des transformations simples aux variables( normalisation, passage au log etc.)

Nous devions mettre en place une évaluation rigoureuse des performances de la regression et le choix d'algorithmes de Machine Learning à l'aide d'une validation croisée. 
<br />
                                                                                                                                      

---
<br />
Nous avons fait le nettoyage des données puis l'analyse exploratoire. Nous avons fait la matrice de correlation pour étudier les différentes correlations.
 <img Align="left" alt="Matrice" width="200px" src="https://github.com/laetdata/Anticipez_les_besoins/blob/main/img/matrice_correlation.png" style="padding-right:10px;" />
<br />
                                                                                                                                      
Nous avons ensuite fait les analyses statistiques univariée et bivariée puis nous avons encore fait l'exploration des données. Ensuite nous avons fait les prédictions. 
---


<br />
En conclusion les meilleurs modèles sont pour TotalGHEmissions c'est la Regression Gradient Boosting le meilleur modèle. ENERGYSTARScore améliore le modèle pour la prévision d'émissions de CO2. Pour SiteEnergyUse le meilleur modèle c'est la regression Gradient Boosting.
<br />
                                                                                                                                      

---
