# Ruleta 21

Juego 2D de ruletas por universos. Esta versión contiene las dos primeras etapas de cada partida.

## Universos disponibles

- Isekai
- Avengers
- Ragnarok
- One Piece
- Naruto
- Jujutsu Kaisen

## Etapa 1: ¿Naces?

La primera ruleta determina si el jugador nace en el universo elegido:

- **SÍ: 95 %**
- **NO: 5 %**

El resultado se calcula en cada tirada. Si sale «NO», la partida termina y el jugador puede volver a elegir universo. Si sale «SÍ», la aplicación muestra la confirmación y pasa automáticamente a la segunda etapa.

## Etapa 2: ¿Cuál será tu raza?

La segunda ruleta contiene ocho opciones con la misma probabilidad (12,5 % cada una):

- Humano
- Elfo
- Enano
- Bestia
- Demonio
- Ángel
- Vampiro
- Dragónido

Al completar esta tirada, se muestra la raza asignada y el jugador puede comenzar otra partida eligiendo un universo.

## Diseño y funcionamiento

- Interfaz oscura de estilo cinematográfico, con detalles metálicos.
- Ruletas 2D vectoriales, generadas en el navegador.
- Sorteos independientes para cada visitante.
- Usa `crypto.getRandomValues` cuando el navegador lo admite.
- No requiere bibliotecas, dependencias ni servidor para jugar localmente.

## Ejecutar

Abre `index.html` en un navegador moderno.

## Publicar con GitHub Pages

1. Abre **Settings → Pages** en el repositorio.
2. En **Build and deployment**, selecciona **Deploy from a branch**.
3. Selecciona la rama **main** y la carpeta **/(root)**.
4. Guarda y espera a que GitHub Pages publique el sitio.

La dirección esperada será:

https://thiandominguez100-stack.github.io/ruleta21/

La publicación requiere activar GitHub Pages desde los ajustes del repositorio.
