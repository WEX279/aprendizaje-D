# Diagnóstico de lógica JS

Diez funciones, de menos a más. Tu trabajo es **hacer que pasen los tests**: cuando todos estén en verde, has terminado.

No es un examen de teoría ni hay que estudiar nada. Es para ver si puedes **enfrentarte tú solo/a a un ejercicio**: leer lo que se pide y escribir el código. Eso es exactamente lo que harás cada día como desarrollador/a.

## Cómo se hace

```bash
npm install      # solo la primera vez: instala Vitest
npm test         # ejecuta los tests
```

Al arrancar, **todo estará en rojo** (las funciones están vacías). Es normal: tu objetivo es ir poniéndolas en verde.

1. Abre **`ejercicios.js`**. Cada función tiene arriba un comentario con la regla y un par de ejemplos.
2. Implementa la función (escribe el cuerpo entre las llaves).
3. Guarda y mira `npm test`: Vitest vuelve a correr solo y te dice cuáles pasan.
4. Repite con la siguiente.

## Reglas del juego

- **Individual.** Trabaja solo/a, sin copiar de un compañero ni pedírselo a una IA. Aquí no se trata de aprobar, sino de ver de verdad qué controlas y qué no, para poder ayudarte donde haga falta. Si copias, el único que pierde información útil eres tú.
- **En orden, de la 1 a la 10.** Suben de dificultad a propósito.
- **No te bloquees.** Si una función se te atasca y no sabes ni por dónde empezar, **déjala vacía y pasa a la siguiente**. Es mejor dato dejar 3 sin tocar que perder media hora en una. Llega tan arriba como puedas.

## Leer un test cuando falla

Cuando una función esté mal, Vitest te dirá algo como:

```
expected false to be true   // esperaba true, recibí false
```

Eso es información, no una regañina: te está diciendo con qué entrada tu función devuelve lo que no toca. Úsalo para encontrar el fallo.
