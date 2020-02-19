### Information sur la mesure de protection

|nom|type|description|format|enum|
|-|-|-|-|-|
|id|integer|Identifiant unique emjpm de la mesure de protection|||
|nom_naissance|string|Nom de naissance du majeur protégé|||
|nom_usage|string|Nom d'usage du majeur protégé|||
|prenom|string|Prénom du majeur protégé|||
|date_naissance|date|Date de naissance du majeur protégé<br>**example**: 22/05/1938|||
|sexe|string|Sexe du majeur protégé||H<br>F|
|date_jugement|date|Date de jugement de la mesure de protection<br>**example**: 01/02/2020|||
|tribunal_siret|string|Siret du tribunal ayant attribué la mesure de protection.|`^\d{14}$`||
|numero_rg|string|Numéro répertoire général (RG)|||
|date_revision|date|Date de revision de la mesure de protection<br>**example**: 01/02/2020|||
|resultat_revision|string|Résultat de la révision de la mesure de protection||mainlevee<br>masp<br>reduction<br>changement_mesure<br>transfert_famille<br>transfert_autre_mjpm|
|date_fin_mesure|date|Date de fin de la mesure de protection<br>**example**: 01/02/2020|||
|cause_sortie|string|Causes de sortie de la mesure de protection||mainlevee<br>deces<br>masp<br>caducite|
|nature_mesure|string|Nature de la mesure de protection||curatelle_simple<br>curatelle_renforcee<br>tutelle<br>sauvegarde_justice<br>maj<br>subroge_curateur<br>subroge_tuteur<br>mandat_protection_future<br>mesure_ad_hoc|
|champs_mesure|string|Champs de la mesure de protection||protection_bien<br>protection_personne<br>protection_bien_personne|
|lieu_vie|string|Lieu de vie du majeur protégé||domicile<br>etablissement<br>etablissement_conservation_domicile|
|type_etablissement|string|Si établissement||etablissement_handicapes<br>etablissement_personne_agee<br>autre_etablissement_s_ms<br>etablissement_hospitalier<br>etablissement_psychiatrique|