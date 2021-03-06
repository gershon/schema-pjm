### Mesure de protection

|nom|type|description|format|enum|
|-|-|-|-|-|
|uuid|string|Identifiant unique emjpm de la mesure de protection<br>**donnée requise**|||
|antenne_uuid|string|Dans le cas d'un service mandataire, identifiant unique emjpm de l'antenne'|||
|date_naissance|date|Date de naissance du majeur protégé *(example: 22/05/1938)*<br>**donnée requise**|||
|civilite|string|Civilité du majeur protégé<br>**donnée requise**||madame<br>monsieur|
|date_jugement|date|Date de jugement de la mesure de protection *(example: 01/02/2020)*<br>**donnée requise**|||
|tribunal_siret|string|Siret du tribunal ayant attribué la mesure de protection.<br>**donnée requise**|`^\d{14}$`||
|tribunal_cabinet|string|Cabinet du tribunal ayant attribué la mesure de protection.|||
|numero_rg|string|Numéro répertoire général (RG)<br>**donnée requise**|||
|numero_dossier|string|Numéro de dossier|||
|date_revision|date|Date de revision de la mesure de protection *(example: 01/02/2020)*|||
|resultat_revision|string|Résultat de la révision de la mesure de protection||mainlevee<br>masp<br>reduction<br>changement_mesure<br>transfert_famille<br>transfert_autre_mjpm|
|date_fin_mesure|date|Date de fin de la mesure de protection *(example: 01/02/2020)*|||
|cause_sortie|string|Causes de sortie de la mesure de protection||mainlevee<br>deces<br>masp<br>caducite|
|cause_sortie_mainlevee_detail|string|Causes de sortie de la mesure de protection, détail de la main levée||masp<br>maj|
|nature_mesure|string|Nature de la mesure de protection<br>**donnée requise**||curatelle_simple<br>curatelle_renforcee<br>tutelle<br>sauvegarde_justice<br>maj<br>subroge_curateur<br>subroge_tuteur<br>mandat_protection_future<br>mesure_ad_hoc|
|champs_mesure|string|Champs de la mesure de protection<br>**donnée requise**||protection_bien<br>protection_personne<br>protection_bien_personne|
|lieu_vie|string|Lieu de vie du majeur protégé<br>**donnée requise**||domicile<br>etablissement<br>etablissement_conservation_domicile|
|etablissement_finess|string|Si établissement, FINESS de l'établissement|||
|type_etablissement|string|Si établissement<br>**donnée requise**||etablissement_handicapes<br>etablissement_personne_agee<br>autre_etablissement_s_ms<br>etablissement_hospitalier<br>etablissement_psychiatrique|
|niveau_ressource|integer|Niveau de ressource correspondant à l'assiette<br>**donnée requise**|||
|prestations_sociales|array|Prestations sociales perçues<br>**donnée requise**||AAH<br>PCH<br>ASI<br>RSA<br>ALS<br>APL<br>ASPA<br>APA|
