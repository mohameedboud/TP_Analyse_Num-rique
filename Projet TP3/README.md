# TP3: Intégration numérique 
- [Introduction](#Introduction)
- [Les methodes simples d'intégration numérique](#Les_methodes_simples_d'intégration_numérique)
     - [Formule des trapèzes](##Formule_des_trapèzes)
     - [Formule de Simpson](##Formule_de_Simpson) 
     - [Formule de quadratures](##Formule_de_quadratures)
- [Conclusion](#Conclusion)
     
- # Introduction 
L'integration est un des problemes les plus importants que l'on rencontre en analyse. En effet, on
rencontre souvent des integrales dont le calcul par des methodes analytiques est tres complique
ou meme impossible, car il n'existe pas d'expression analytique d'une primitive de la fonction
à integrer.
Le but de ce chapitre est d’aborder le calcul général de l’intégrale d’une fonction f(x) sur un domaine
fini délimité par des bornes finies a et b

- ## Les methodes simples d'intégration numérique
L'intégration numérique est un chapitre important de l'analyse numérique et un outil indispensable en physique numérique. 
On intègre numériquement dans deux cas principaux :

               * On ne peut pas intégrer analytiquement,
               * L'intégrande est fourni non pas sous la forme d'une fonction mais de tableaux de mesures.
            
Les méthodes numériques d'intégration d'une fonction sont nombreuses et les techniques très diverses.

- ### Formule des trapèzes
- La méthode d'intégration approchée, dite des trapèzes, décrite ci-après, introduite par Newton & Cotes est plus précise que la méthode élémentaire, dite des rectangles, correspondant aux sommes de Cauchy-Riemann, consistant à remplacer la fonction initiale par une approximation en escalier. 
![Alt Text](Trapeze.gif)
- ### Formule de Simpson
- En analyse numérique, la méthode de Simpson, du nom de Thomas Simpson, est une technique de calcul numérique d'une intégrale.
![Alt Text](simpson.png)
- ### Formule de quadratures
- On appelle formule de quadrature une expression linéaire dont l’évaluation fournit une valeur approchée de l’intégrale sur un morceau typique (l’intervalle [0 ; 1] par exemple). Une transformation affine permet de transposer la formule sur un morceau particulier.



- # Conclusion
![Alt Text](demo.gif)

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/nevermind78/num_integ/main?filepath=widget_final.ipynb)

