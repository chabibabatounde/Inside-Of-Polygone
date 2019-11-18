# Inside-Of-Polygone
Ce script permet de vérifier l'appartenance d'un point de coordonnées connus, à un polygone dont les coordonnées des sommets sont connus également.
Le principe est simple: On trace une démi-droite depuis le point, vers l'infinie. Ensuite on compte le nombre d'intersection entre cette démi droite et le polygone.
  * Si le nombre est paire, alors le point est à l'extérieur du polygone;
  * Si le nombre est impaire, alors le point est à l'intérieur du polygone.
  
  
   
          |-----------------------------|
          |                             |
Point     | (Démi droite vers l'infini) |
*---------|-----------------------------|----------> (Nombre d'intersection paire)  Point hors du polygone
          |                             |
          |-----------------------------|



    |-----------------------------|
    |                             |
    |                    Point    | (Démi droite vers l'infini)
    |                      *------|----------> (Nombre d'intersection impaire) Point dans le polygone
    |                             |
    |-----------------------------|


