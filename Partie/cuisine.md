# Intendance
## Page
# List
Liste afficher dans une datatable
recherche :
	- nom
	- type
	- autheurs
	- ingrédients (possibilités de quantité)
	- matériels (possibilités de quantité)
	- note (avec type de note)
	- nombres de varianteee
# Detail
## Onthologie
### Note
* Nom : Grade
* Attribut :
	- Variant: Variation de la recette notée (FK: variant)
	- Type : Type de notation (FK : GradeType)
	- Value : Note (Int)
	- Unit : Unité de mesure e la note (FK: Unit)
	- Comment : Commentaire justifiant la note (Text)

### Type de note (a mettre en referentiel, type de note, type de recette)
* Nom : GradeType
* Attribut : 
	- Name : nom du type (string)

### Ingredient
* Nom : Ingredient
* Attribut : 
	- Name : nom de l'ingredient (string)

### Quantité d'ingrédient
* Nom : IngredientQuantity
* Attribut : 
	- Ingredient : Ingredient a quantifier (FK: Ingredient)
	- Variant : Variant qui appelle cette quantification (FK: Variant)
	- Quantity : Quantité de l'ingrédient (Int)
	- Unit : Unité de messure de l'ingredient (FK: Unit)

### Matériel
* Nom : Material
* Attribut : 
	- Name : Nom du matériel (string)

### Quantité de matériel
* Nom : MatérialQuantity
* Attribut : 
	- Material : Materiel a quantifier (FK: Material)
	- Variant : Variant qui appelle cette quantification (FK: Variant)
	- Quantité : Quantité du matériel (int)

### Recette
* Nom : Recipe
* Attribut : 
	- Name : Nom de la recette (string)
	- Variants : différentes variante de la recette (FK[]: Variant)

### Type de recette
* Nom : RecipeType
* Attribut : 
	- Name : Nom du type de recette(string)

### Etape de la recette
* Nom : Step
* Attribut :
	- Variant : Variante associée a l'étape (FK: Variant)
	- Text : Description de l'action (text)
	- Picture : Photo présenteant la fin de l'étape (text)

### Unité
* Nom : Unit
* Attribut : 
	- Name : Nom de l'unité (string)
	- Symbol : Symbole de l'unité(string)

### Variation de la recette
* Nom : Variant
* Attribut :
	- Recipe : Recette associée a ces recettes (FK: Recipe)
	- Steps : Etapes de la variante (FK[]: Step)
	- Ingredients : Ingredient de la variante (FK[]: Ingredient)
	- Materials : Materelle de la variante (FK[]: Material)
	- Author : Autheur de la variante(string)
	- Visible : Affichage ou non de la recette au public (bool)
	- Grades : Notation diverse de la recette (FK[]: grade)
	- Types : Type de recette (FK[]: type)
	- MainVariant : Est-ce la variante a afficher en priorité lors de la demande de la recette (bool)
	- Comment : Commentaire sur la recette (text)