## Partie 1
Installation fluide via VS Code
![Install ESLint](image-1.png)

## Partie 2
Avec le code app.js que vous nous avez fournis, je n'ai pas eu d'erreur en lancant *npx eslint app.js* alors j'en ai cree en ajoutant des balises *<html> et <script>*

npx eslint app.js
```bash
tp-eslint-git\app.js      
  7:1  error  Parsing error: Unexpected token <     

✖ 1 problem (1 error, 0 warnings)
```
![Erreur](image-2.png)

npx eslint --fix app.js
```bash
tp-eslint-git\app.js      
  7:1  error  Parsing error: Unexpected token <     

✖ 1 problem (1 error, 0 warnings)
```

J'ai ensuite corriger le fichier manuellement. Apres l'avoir corrige, j en'ai plus eu d'erreur en lancant *npx eslint app.js*


## Partie 3
installation de husky sans problem tick
![Install Husky](image.png)