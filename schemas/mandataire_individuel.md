### Mandataire individuel

|nom|type|description|format|enum|
|-|-|-|-|-|
|id|integer|Identifiant unique emjpm du mandataire individuel<br>**example**: 134|||
|num_siret|string|Numéro SIRET du mandataire individuel (14 chiffres)<br>**example**: 80295478500028|`^\d{14}$`||
|email|string|Email du mandataire individuel<br>**example**: mandataire@monmail.com|||
|sexe|string|Sexe du mandataire individuel<br>**example**: H||H<br>F|
|nom_naissance|string|Nom de naissance du mandataire individuel<br>**example**: Dupont|||
|nom_usage|string|Nom d'usage du mandataire individuel<br>**example**: Dupont|||
|prenom|string|Prénom d'usage du mandataire individuel<br>**example**: Thomas|||
|adresse|string|L'adresse du lieu de travail du mandataire individuel<br>**example**: 14 Avenue Duquesne|||
|code_postal|string|Code postal du lieu de travail du mandataire individuel<br>**example**: 75350|`^\d{5}$`||
|Ville|string|Ville du lieu de travail du mandataire individuel<br>**example**: Paris|||
|telephone_bureau|string|Numéro de téléphone du bureau du mandataire individuel<br>**example**: 01 40 56 60 00|`^\0d{1} d{2} d{2} d{2} d{2}$`||
|telephone_mobile|string|Numéro de téléphone mobile du mandataire individuel<br>**example**: 06 60 56 60 00|`^\0d{1} d{2} d{2} d{2} d{2}$`||