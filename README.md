# retos-tienda

## Reto 1

1. Agregar un titulo a la página y un footer con copyright
2. Agregar datos a la base de datos de pocketbase: https://pocketbase.io/
3. Llamar la api de pocketbase para traer la información de todos los items
4. Usando Ant Design (https://ant.design) crear cartas donde se muestren los juegos, estas cartas deben mostrar: Nombre, imagen, pequeña descripción (no superar los 100 caracteres y poner "..." al final). Estas cartas deben tener un indicador visual de que se les puede dar click

La idea general de este reto es que al uno entrar a la página se muestren las cartas con todos los juegos y entender que les puedo dar click

## Reto 2

1. Agregar TS al proyecto, cambiar los componentes creados por componentes .tsx
2. Agregar una barra de navegación (por ahora solo añadir un botón, estilos libres)
3. Agregar botones a las imagenes, estos deben ser: MORE y ADD

## Reto 3

1. Agregar redux al proyecto (https://react-redux.js.org/introduction/getting-started)
2. Añadir a la barra de navegación un botón para manejar el tema de la página (modo diurno/nocturno)
3. Al darle click al botón, se deben cambiar los estilos de los componentes para que cuadren con estos modos (usar redux para manejar esta lógica)

## Reto 4

1. Instalar react-router "npm i react-router-dom"
2. Agregar una barra de navegación donde estará: El botón de cambio de tema, un botón para volver a "Home" donde se verán otra vez todas las cartas
3. Utilizar las rutas dinámicas para crear una página por juego, donde se deberá tener mínimo: nombre, titulo, descripción. (Puedes agregar más cosas que creas que harán la página más entretenida)

Documentación útil: https://reactrouter.com/en/main/start/overview

## Reto 5

1. Crear una página (por ahora pública) donde puedas hacer 1 de las siguientes operaciones (POST, PUT, DELETE)
2. Usar un componente que te permita elegir cuál acción elegir (ejemplo: https://ant.design/components/select)
3. Dependiendo de la acción a elegir, se debe mostrar un formulario en la página
4. Realizar la acción elegida
5. Mostrar de alguna forma si la acción se resolvió bien o falló (ejemplo: https://ant.design/components/alert)
