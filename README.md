# CV
Introducing myskills


https://le-campus-numerique.fr/formations-developpeur2/

Gestion du slider: 

@lulufv
il y a 2 mois
Regarding the white space, my solution was to subtract the number of items in the animation-delay line, instead of just 1, so mine looks like this:  
animation-delay: calc((10s / var(--quantity)) * (var(--position) - var(--quantity))); 

set variable speed to the slider 

1. If you need to change the speed with a variable, you just need to create an additional --time variable like I did with quantity, then in the css, replace 10s with var(--time). 2. This slider, when you change the wifth for each different screen, will shrink itself without you needing to edit anything further.

### Things left to do 

- Finish  contact form and link 
  Voir pour virer la banderol de competences dev (en trop)l