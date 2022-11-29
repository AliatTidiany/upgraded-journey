---
title: |
  "Resume python courses"
date: November, 2022
lang: en-EN
urlcolor: blue
geometry: "left=2.5cm,right=2.5cm,top=3cm,bottom=3cm"
documentclass: article
fontfamily: Alegreya
header-includes: |
    \usepackage{fancyhdr}
    \pagestyle{fancy}
    \fancyhf{}
    \rhead{Dakar Institute of Technology}
    \lhead{Patrick Nsukami}
    \rfoot{Page \thepage}
    \hypersetup{pdftex,
            pdfauthor={Patrick Nsukami},
            pdftitle={Introduction to Python programming},
            pdfsubject={Introduction to Python programming},
            pdfkeywords={Python, Programming},
            pdfproducer={Emacs, Pandoc, Latex, Markdown},
            pdfcreator={Emacs, Pandoc, Latex, Markdown}}
    
---
# Rapport cours python: 
## Notions de Classes, Instances et Méthodes
effectué par ***Alioune MBODJI***

### Les classes:
- Une classe nous permet de définir notre propre type.
- A chaque appel d’une classe, on aura la création de nouvelles instances.
- On parle de relation d’héritage entre les classes et les instances.
- Les instances vont pouvoir hériter de tous les attributs de l’espace de nommage de la classe.

  - Illustration:

  ![](./img/img_class.png){width=6in} 

### Les instances et les méthodes:
- Les classes et les objets sont des objets mutables.
- Les méthodes sont des fonctions définies à l’intérieur de la classe.
- Les classes et les instances ont leurs propres espaces de nommage
- Lorsqu’on ne trouve pas un attribut dans l’espace de nommage d’une instance, faudra remonter l’arbre d’héritage afin de le trouver au niveau de la classe. 
 
 - Illustration:

 ![](./img/img_inst.png){width=6in}




