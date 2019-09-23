# Serempre

## Part 1: Nativo (Opcional)
Cree una biblioteca o módulo para Android e iOS que simule un diccionario en línea. Este diccionario tendrá su propia interfaz de usuario, por lo que el módulo debe instanciar su propia vista.

La vista debe contener una entrada y un botón de búsqueda. La respuesta a esta búsqueda será la definición de la palabra, el sonido si lo tiene, y una imagen descriptiva.

Para la búsqueda de definiciones, puede utilizar la siguiente API pública:

```
http://api.urbandictionary.com/v0/define?term=dog
```

Para la imagen puede usar lo siguiente:

```
https://api.flickr.com/services/feeds/photos_public.gne?tags=dog&tagmode=any&format=json
```
Si no hay resultados, muestre algún mensaje descriptivo manteniendo la estructura de la vista.

Puede utilizar otra API si lo desea.

## Part 2: Nativo (Opcional)
Cree una aplicación sencilla, utilizando el marco de trabajo creado en la parte 1. Debe añadir los controles necesarios para buscar una palabra cada vez que el usuario lo desee. Añada también un botón Compartir, que muestra el recurso compartido nativo del dispositivo. No es necesario (para ello) compartir. Sólo necesita ser mostrado.

## Part 3: React Native 
Al igual que en la parte 2, sólo que en esta ocasión hay que integrar lo nativo en react-native.

Si la parte 1 y 2 no se realizan, realizar todo en react-native.

Adjuntamos maquetas para que las utilice como guía, pero esto no significa que deban ser exactas. Recuerde que el diseño debe verse bien tanto en el modo vertical como en el horizontal.

## Importante!

Utilizar las siguentes dependencias:

1.- Navigación (react-native-navigation) https://github.com/wix/react-native-navigation

2.- Redux

3.- react-native-size-matters




