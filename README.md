neo-dist
========

squelette-dist pour spip intégrant la tinytypo

introduction
--------
intégrer le framework css minimal tinytypo http://tinytypo.tetue.net/ dans le squelette par défaut de SPIP http://www.spip.net/


installation
--------
1. renommer squelettes-dist en squelettes-dist-old
2. télécharger neo-dist et la placer à la racine de votre site dans le répertoire squelettes-dist 


issues
--------
quelle est la méthode d'intégration de CSS à adopter ?

- un appel par type (font.css, form.css, ....)
point +:  pédagogique et  facile à adapter pour un public débutant
point -:  performance pour les sites ne configurant rien (pas de compression activée)

- un appel à un ficher unique (tinytypo.css regroupant tout)
point +:  performance pour les sites ne configurant rien
point -: peu pédagogique

roadmap
--------
- passer en véritable HTML5
- simplifier 
- passer en responsive
