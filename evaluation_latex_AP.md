
# Outils pour la rédaction du mémoire: LaTeX

-  La date limite est le 31 avril 2025
- Choix entre deux sujets.
Dans tous les cas devront être fournis: le fichier .tex et le fichier .pdf. 
- Le fichier .tex devra contenir des commentaires, le préambule devra être structuré. Tout élément de personnalisation devra être commenté (appel de package, choix d'option, définition de commandes, etc)

 
# Sujet 1 — Production d’un texte universitaire en latex

- Vous devrez rédiger en LaTeX un texte de votre choix (note de lecture/recension d'un ouvrage, article de type universitaire, mini-mémoire, résumé des recherches personnelles, etc) de trois pages minimum. 
 Il devra contenir au moins: 
	+ un titre
	+ des commandes de section (au moins deux niveaux)
	+ des notes de bas de page
	+ une bibliographie
	+ une table des matières
	+ un index et/ou un glossaire
	+ au moins un tableau, figure ou schéma
	+ au moins une nouvelle commande ou un nouvel environnement
	+ un appel de package autre que les packages obligatoires
	+ rq: L'appel de classe devra être cohérent avec la nature du document produit.
	


# Sujet 2 — Production d’un Curriculum vitae en LATEX

- Vous devrez rédiger en LaTeX votre cv ou un cv fictif. Il devra comporter:
	+ Des commandes de section
	+ Une photo
	+ Des informations générales (adresse, email, téléphone, etc)
	+ un ou plusieurs environnements de type liste
	+ Un titre (du type "Curriculum vitae")
	
Pour ce sujet, vous avez le choix entre deux options:

1. Utiliser la classe `article` ou la classe `book` pour rédiger votre cv. En ce cas, votre fichier .tex devra contenir au moins:
	+ une personnalisation de la mise en page des commandes de section (au moyen par exemple de `\renewcommand` ou du package `titlesec`)
	+ au moins une nouvelle commande ou un nouvel environnement
	+ un appel de package autre que les packages obligatoires

vous pouvez, si vous le souhaitez, vous inspirer de modèles trouvés en ligne, mais en ce cas:

+ indiquez en commentaire dans le préambule où vous avez trouvé le modèle
+ apportez des modifications à ce modèle

2. Utiliser la classe de document `moderncv` (consultez le manuel).
En ce cas, votre fichier .tex devra contenir au moins:
	+ les commandes adaptées pour les informations générales
	+ une des commandes expliquées dans la section 2.3.2 ("General macros") du manuel: `\cvitem`, `\cvdoublitem`, etc
	+ un choix de style et de couleur (`\moderncvstyle`et `\moderncvcolor`). `\moderncvstyle` devra comporter au moins une option (argument optionnel). 
	+ Un autre élément de personnalisation, au choix
	+ Au moins une nouvelle commande ou un nouvel environnement



	
