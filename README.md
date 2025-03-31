# new-car
 
### Manipulation des données

Au départ, notre base de donnée était de la sorte :

![Texte alternatif](screenshots/dataframe.png "Titre de l'image")

Selling et Present Price n'avaient pas l'air à l'échelle, nous l'avons donc multiplié par 1000 pour avoir des prix plus cohérents avec le marché (ex : de 4.43€ => 4430€).
Nous avons prit la décision de regrouper les données de sorte à les "Classifiers".

Fuel possède trois classes :
- '0'correspond à Pétrol 
- '1'correspond à Diesel 
- '2'correspond à CNG 

Seller possède deux classes :
- '0'correspond à Dealer
- '1'correspond à Individual

Transmission possède deux classes :
- '0'correspond à Manual
- '1'correspond à Automatic 
