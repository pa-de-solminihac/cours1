TOC
* auto-gen TOC:
{:toc}

PHP/PHP5
===

Historique:
---
- 1994-1995 : PHP par Rasmus Lerdorf
- 2004 : PHP version 5

Principales caractéristiques :
---
- Langage de programmation de **script** interprété 
- Conçu pour le développement d'**applications Web**
- Exécuté **côté serveur** (code non accessible côté client)
- **Génération de pages Web dynamiques**
- Possibilité d’être couplé à une **base de données**
- Langage **objet faiblement typé**
- _Open source_

Utilisation
===

- Fichier texte avec l’extension : .php
- Script PHP : langage PHP et/ou langage HTML
- Balises `<?php` `?>` :
```php
<?php
    instruction_1
    instruction_2
    …
?>
```

Commentaires
===
- Non interprétés
- Commentaires de type C/C++ et shell Unix 
- Exemples :
```php
// Commentaire PHP (une seule ligne).
# Autre commentaire PHP (une seule ligne).
/* Autre commentaire PHP (une ou plusieurs lignes). */
/*
    Commentaire PHP
    (sur plusieurs lignes).
*/
```

Définition de type
===
- **Pas de déclaration explicite** du type d'une variable
- Le type d'une variable est déterminé par le contexte d'utilisation
- Conversion automatique
