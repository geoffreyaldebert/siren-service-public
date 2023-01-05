# Extraction des unités légales du service public

Traitement python (dans un notebook jupyter) pour la génération des données.

Nous avons pris la règle suivante pour déterminer si une unité légale appartient à un service public :

catégorie juridique égale à 3110 : Représentation ou agence commerciale d'état ou organisme public étranger immatriculé au RCS
catégorie juridique égale à 3210 : État, collectivité ou établissement public étranger
catégorie juridique commençant par 4 : Personne morale de droit public soumise au droit commercial
catégorie juridique commençant par 7 : Personne morale et organisme soumis au droit administratif
