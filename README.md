Je suis étudiante en deuxième année de classe préparatoire intégrer informatique et je souhaite devenir ingénieur Data Analyst.
Ce document est pour ce qui débute comme moi. 
Projet 1 : ANALYSE DES NOTES D’ELEVES
Objectif Global : Analyser un tableau de résultats de notes d’élèves pour extraire des statistiques utiles et créer des visualisations.
Objectifs Spécifiques : • Charger et lire des données dans Excel 
• Calculer les moyennes par élève
• Trouver la meilleure et pire note par matière
• Calculer la moyenne générale par matière
• Créer des graphes (barres ou courbes)

1.	Charger et lire des données dans Excel
Les données dans Excel sont fictives et ne servent qu’a menés à bien notre projet.
2.	Calculer les moyennes par élève
Pour obtenir les moyennes par élèves nous avons utilisés la fonction MOYENNE . 
Nom	Maths	Français	Anglais	Informatique
Alice	14	13	16	18
Boris	11	9	14	15
Claire	17	16	15	17

Pour obtenir la moyenne de l’élève Alice: =MOYENNE(B2 :E2)
Pour obtenir la moyenne de l’élève Boris : =MOYENNE(B3 :E3)
3.Trouver la meilleure et pire note par matière
 Pour trouver la meilleure et la pire note par matière nous avons utilisés la fonction  MAX et MIN. 
Nom	Maths	Français	Anglais	Informatique
Alice	14	13	16	18
Boris	11	9	14	15
Claire	17	16	15	17
Pour obtenir la meilleure note en maths on fera : =MAX(B2 :B4)
Pour obtenir la pire note en maths on fera : =MIN(B2 :B4)
4.Calculons la moyenne générale par matière
Nom	Maths	Français	Anglais	Informatique
Alice	14	13	16	18
Boris	11	9	14	15
Claire	17	16	15	17

Pour obtenir la moyenne générale en maths on fera : =MOYENNE(B2 :B4)
Pour obtenir la pire note en maths on fera : =MIN(B2 :B4)
		5.Tracons les graphes 
a. traçons un histogramme des moyennes par élève
🔹 Étape 1 : Sélectionne tes données
•	Sélectionne les deux colonnes Nom et Moyenne
•	Exemple : de A1 à B4
🔹 Étape 2 : Insère un histogramme
•	Clique sur l’onglet Insertion
•	Clique sur Graphique en colonnes ou barres
•	Choisis "Histogramme groupé" ou "Colonne groupée"
🔹 Étape 3 : Personnalise le graphique
•	Donne un titre
•	Ajoute les valeurs sur les barres (clic droit > Ajouter des étiquettes)
•	Change les couleurs si tu veux
✅ Résultat : un histogramme clair qui montre visuellement qui a les meilleures ou pires moyennes.
