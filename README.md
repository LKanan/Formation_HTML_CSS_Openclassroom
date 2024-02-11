# FORMATION HTML & CSS Openclassroom
## HTML

### 1. Les balises de base
Nous avons les balises de base en HTML

![Les balises de bases en HTML](supports/balises_de_base.png)

### 2. Les balises universelles

C'est une balise de type **inline** c'est-à-dire une balise que l'on place au sein d'un paragraphe de texte pour sélectionner certains mots uniquement.

![Image des balises universelles](supports/les_balises_universelles.png)

### 3. Les ancres(Les liens) 
Ceci est un type de lien hypertexte appelé un lien absolu
`<p>Lien vers openclassroom  <a href="https://openclassrooms.com">ici</a></p>`
**Dans href on peut mettre le chemin vers notre autre fichier ou le nom d'un id precedé d'un # pour nou ramener à un endroit précis de notre page**
**Et si l'ID se trouve dans un autre fichier on va mettre dans la valeur du href="nom_fichier_ou_chemin#nom_id"**
**L'attribut target="_blank" dans la balise permet d'ouvrir la cible dans un nouvel onglet que l'onglet actuel**
`href = "mailto: adressemail@gmail.com"` permet de creer un lien vers l'ouverture de la boite mail avec un nouveau message vide vers l'adresse indiqué et `href  = "nom_du_fichier_ou_chemin_du_fichier.extension` permet de creer un lien lien pour telecharger un fichier au prealable dans le meme dossier que notre page web.

## 4. La balise `<img>`
Pour ajouter une infobulle lorsque la souris survole notre image sur la page web on doit ajouter l'attribut `title = ""` et comme valeur on lui donne le texte qui sera affiché lorsque la souris survole notre image.

![Image qui explique l'ajout de l'info bulle](supports/ajout_info_bulle_image.png) 

## CSS

### 1. Syntaxe de base du CSS

En CSS la syntaxe générale est la suivante :

![Image de la syntaxe généale du CSS](supports/image_syntaxe_css.jpg)

### 2. Les fifférentes epaisseurs de texte en CSS
 L'epaisseur du texte est donné à un texte dans une balise grace à la proprieté `font-weight` et les valeur qu'elle peut prendre sont listés sur l'image ci-dessous :

 ![Differntes valeurs d'epaisseurs du texte en CSS](supports/les_differentes_epaisseur_du_texte.png) 


### 3. Comment utiliser une police externe sur notre page web

Pour utiliser une police externe sur notre page web on va utiliser la proprieté CSS `font-family` et en valeur on va lui donner le nom de la police selectionnée, les etapes pour faire cela sont definies sur la photos suivante :

![Utilisation de la police de Google Font sur notre page web](supports/comment_ajouter_une_police_de_google_font_dans_le_fichier.png)

## 4. Soulignement du texte en CSS

Pour définir des soulignement on utilise la proprieté `text-decoration` et il peut prendre comme valeurs, les valeurs listés sur la photo suivante:

![Type des doulignements en CSS](supports/types_de_soulignement_en_CSS.png)

### 5. Modification du comportement d'une image de fond en CSS

Pour modifier le comportement d'une image de defond en CSS on utilise la proprieté `background` et il peut prendre diverses formes comme indiqué à l'image ci-dessous:

![Differentes formes de modification du comportement de l'image de fond](supports/modification_comportement_image_de_fond.png)

### 6. Création des dégradés

Pour créer des dégradés en CSS on utilise la proprieté `linear-gradient` qui prend commme valeur une lise de valeurs particulieres comme `(90deg, #360C3, #2EBF91)`, le premier parametre est le degré qui va separer les deux couleurs puis on met la couleur qui va commencer et la seconde valeur est la couleur qui va finir. Un exemple à l'image ci-dessous:

![Image de création des degradés en cSS](supports/exemple_degrade_CSS.png)

### 7. Gestion de l'opacité de l'image en CSS

![Image de gestion de l'opacité de l'image en CSS](supports/gestion_opacite_pour_image_de_fond.png)

### 8. Ajouter des ombres en CSS

Pour ajouter l'ombre à un element CSS pour les balises conteneur on utilise la proprieté `box-shadow` et pour le texte on utilise `text-shadow` et les explications concernants les valeurs de ces proprieté s'equivalent.

![Image qui explique comment ajouter de l'ombre sur les elements html](supports/box-shadow.png)
![Resultat du box Shadow](supports/resultat_du_box-shadow.png)

On peut aussi adoussir l'ombre des element en suivant cette syntaxe :

![Adoussissement des ombres d'un element HTML](supports/adoussiment_des_ombres.png)

On peut aussi qjoutes des ombres su des texte avec la proprieté `text-shadow` avec la syntaxe suivante:

![Ajout des ombres sur des texte](supports/ajout_des_ombres_sur_texte.png)

### 9. Arrondissement des bords des éléments HTML

Pour faire un arrondissement des bords independants pour chaque coin la procédure est la suivante:

![Arrondissemnt indépendants des coins d'un element html](supports/arrondissement_des_bords.png) 

On peut aussi créer des elipses avec du CSS en utilisant la syntaxe suivante:

![Image de la facon de créer des ellipse en CSS](supports/creation_ellipse.png)
![Suite de la facon de créer des ellipse en CSS](supports/suite_creation_ellipse.png)

**Resumé de box-shadow et border-radius**

![Resumé de box-shadow et border-radius](supports/resume_shadow.png)

### 10. CREATION DES APPARENCES DYNAMIQUES

![La pseudo classe :hover](supports/la_pseudo_classe_hover.png)

![La pseudo classe :active](supports/la_pseudo_classe_ctive.png)

![La pseudo classe :focus](supports/la_pseudo_classe_focus.png)

![La pseudo classe :visited](supports/la_pseudo_class_visited.png)

### 11. QUELQUES SELECTEURS SPECIAUX

![Selecteur special 1](supports/selecteur_special1.png)
![Selecteur special 2](supports/selecteur_special2.png)

### 12. STRUCTURATION DE LA PAGE WEB

![Selecteur special 2](supports/la_balise_header.png)

![Selecteur special 2](supports/la_balise_nav.png)

![Selecteur special 2](supports/la_balise_main.png)

![Selecteur special 2](supports/la_balise_aside.png)

![Selecteur special 2](supports/la_balise_footer.png)

**En resumé on a :**

![Selecteur special 2](supports/synthese_structuration_page.jpg)

![Selecteur special 2](supports/resume_final_structuration_page.png)

### 12. LES MODELES DE BOITES EN HTML

**Remarque :**
![Remarques sur l'utilisation des models de boites](supports/remarque_sur_les_models_de_boites.png)

### 13. LES MARGES EN CSS

![Les marges padding et margin en CSS](supports/margin_et_padding.png )

![Conclusion su le margin et le padding](supports/conclusion_margin_padding.png)

Il n'est cependant pas possible de centrer verticalement un bloc avec cette technique. Seul le centrage horizontal est permis.

### 14. LA MISE EN PAGE AVEC FLEXBOX

![Image de l'introduction à l'utilisation de flexbox](supports/introduction_flex_box.png)

![Image du retour à la ligne des elements d'un conteneur(responsivité)](supports/retour_a_la_ligne_responsive.png)

Lorsque on utilise la proprieté-valeur `flex-direction: row-reverse` l'inversion commence à la position du dernier element et on continue avec les elements qui le suivent en partant de la droite vers la gauche, ce qui fait que le dernier element sera l'ancien premier element et il sera le plus à droite de l'ancien premier element aui est devenu le premier element. 
**Remarquez** que quand vous mettez la direction inversée, le début et la fin sont aussi inversés.
cela signifie que meme le `justify-content: flexs-start` et `justify-content: flex-end` sont inversées

![Alignement des elements d'un conteneur](supports/alignement_des_elements.png)

![Alignement sur axe secondaire des elelments](supports/alignement_sur_axe_secondaire.png)

- `align-content` permet d'aligner les blocs se trouvant dans un conteneur.
  
![Alignement avec align-content](supports/explication_align_content.png)

- Proprieté **`Order`**

![Proprieté order de flexbox](supports/propriete_Order_de_flex_box.png)

- On a aussi la proprieté **`flex-flow`** 

![Proprieté flex-flow de flexbox](supports/flex-flow_de_flex_box.png)

![Resumé sur l'alignement des boites](supports/resume_alignement_box.png)