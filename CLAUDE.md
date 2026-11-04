# API de libros

## Sobre mí
- Soy estudiante y estoy aprendiendo con este proyecto.
- Nivel principiante en Node.js, TypeScript y APIs REST.

## Cómo quiero que me ayudes
- Escribe el código, pero explícame el porqué de cada decisión importante.
- Explica en español, con palabras sencillas, los conceptos nuevos la primera vez que aparezcan
  (por ejemplo: middleware, interfaz, repositorio, códigos HTTP, tipos genéricos).
- Haz cambios pequeños y paso a paso; al terminar, resume qué archivos tocaste y para qué.
- Si hay varias formas de hacer algo, recomiéndame una y dime brevemente por qué.
- Cuando cometa un error, explícame la causa, no solo la solución.
- Dime cómo probar lo que hemos hecho (por ejemplo, con `curl` o el navegador).
- Antes de ejecutar cualquier comando en la terminal, explícame qué hace y para qué lo vas a usar.
- El código sigue en inglés (ver Normas); las explicaciones, en español.

## Tecnología
- Node.js + Express 5 + TypeScript.
- Datos en memoria por ahora. Más adelante, MongoDB.

## Comandos
- `npm run dev`: arranca la API en http://localhost:3000
- `npm run lint`: revisa el código

## Normas
- Todo el código en inglés: variables, rutas, campos, tipos.
- Arquitectura: routes -> service -> repository.
- Las rutas no tocan los datos directamente: siempre a través del servicio.
- Ramas con el formato `feature/<funcionalidad>`.
- No instales librerías nuevas sin preguntarme.

## Requisitos del producto
Requisitos funcionales y criterios de "hecho" de la API:

@docs/prd-books.md