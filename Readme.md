##instalación

Hola Carla para poder instalar bootstrap a traves de npm , lo que debemos hacer es crear el archivo package.json, este archivo se hace a través de un comando por terminal

```
npm init -y

```

Esto se hace para poder tener diferentes dependencias y manejarlas por nodo_modules.

luego de eso ya puedes instalar bootstrap

```
npm i bootstrap@5.2.2
```

Luego es cosa de crear los directorios , por ejemplo le puse src, y dentro va la carpeta de sass y lo otro que incluyas , assets , js etc.

para copilar bootstrap + sass 

```
sass --watch  src/sass/main.scss src/css/main.css
```


