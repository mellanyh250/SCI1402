# Instructions pour exécuter le projet

## 1. Structure du projet

Recréer la structure suivant sur votre ordinateur :
```
SCI1402/
├── Données/    # Dossier contenant les fichiers Excel 'Forbes_Global_2000' initaux
│ ├── "Forbes Global 2000 - 2008  unified industry.xlsx"
│ ├── "Forbes Global 2000 - 2009  unified industry.xlsx"
│ └── ...
├── Image/      # Dossier contenant l'image utilisée dans le R Markdown
│ ├── "graph-8898188_640.jpg"
| └── "Référence.txt"
├── Output/     # Dossier contenant les fichiers qui seront générés par le R Markdown
│ ├── "Forbes_Global_2000.html"
│ └── "Forbes_Global_2000_output.csv"
├── Forbes_Global_2000.Rmd
└── README.md
```

## 2. Instructions pour exécuter ce projet

1. Vérifier que tous les fichiers Excel des données initiales sont dans le dossier `Données/` et que l'image est dans le dossier `Image/`, au même niveau que le fichier `"Forbes_Global_2000.Rmd"`.
2. Ouvrir `"Forbes_Global_2000.Rmd"` dans RStudio.
3. Exécuter le R Markdown pour générer :
   - `"Forbes_Global_2000.html"`
   - `"Forbes_Global_2000_output.csv"`
