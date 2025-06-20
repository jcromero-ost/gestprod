# GestProd - Arquitectura MVC Escalable

Este proyecto propone una base simple para desarrollar una aplicaci\u00f3n web utilizando el patr\u00f3n MVC (Modelo Vista Controlador). La estructura est\u00e1 pensada para poder a\u00f1adir nuevas p\u00e1ginas y funcionalidades de forma organizada.

## Estructura de carpetas

```
src/
├── controllers/    # Controladores de la aplicaci\u00f3n
├── models/         # Modelos de datos
├── views/          # Plantillas de vistas (EJS u otro motor)
└── routes/         # Definici\u00f3n de rutas

public/
├── css/            # Hojas de estilo
├── js/             # C\u00f3digo JavaScript del lado del cliente
└── images/         # Recursos est\u00e1ticos

config/             # Configuraci\u00f3n de la aplicaci\u00f3n

docs/               # Documentaci\u00f3n adicional

tests/              # Pruebas autom\u00e1ticas
```

## Inicio r\u00e1pido

Se utiliza **Node.js** con **Express** como framework de servidor. Para poner en marcha el proyecto:

```bash
npm install
npm start
```

Esto iniciar\u00e1 un servidor en `http://localhost:3000`.

## A\u00f1adir nuevas p\u00e1ginas

1. Crear la vista correspondiente en `src/views`.
2. A\u00f1adir un m\u00e9todo en un controlador dentro de `src/controllers`.
3. Registrar la ruta en `src/routes` para que apunte al controlador.

De esta forma se mantiene la separaci\u00f3n de responsabilidades y resulta sencillo escalar la aplicaci\u00f3n.
