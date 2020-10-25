https://ecc521.github.io/background-remover/index.html

# background-remover
Remove a mostly solid background until reaching a border. 

Color defaults to white
Contrast defaults to 1.5

You may want to set contrast to ~20 for images in black borders on white backgrounds to minimize artifacts and stray blended pixels. 

This code works by marking all background tiles starting from the edges of the image, until reaching a non-background border. 
