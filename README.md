# Juego Pokémon: ¿Quién tiene la ventaja?

¡Un sencillo pero adictivo juego web donde pones a prueba tu conocimiento sobre la tabla de tipos de Pokémon! Se te presentarán dos Pokémon aleatorios y tu misión es adivinar cuál de los dos tiene una ventaja de tipo sobre el otro.

[Link para jugar en vivo](https://halverto.github.io/poketest/)

---

## 🎮 Cómo Jugar

1.  Al cargar la página, aparecerán dos Pokémon.
2.  Analiza ambos y haz clic en el botón **"Elegir"** debajo del Pokémon que crees que tiene un ataque súper efectivo contra el otro.
3.  El juego te dirá si has acertado o no y te mostrará la razón de la ventaja (p. ej., "Fuego es fuerte contra Planta").
4.  ¡Acumula la mayor racha de aciertos posible! Si fallas, tu racha se reiniciará a cero.
5.  Haz clic en **"Siguiente Ronda"** para continuar jugando.

## ✨ Características

-   **Modo Oscuro:** Una interfaz elegante y agradable a la vista.
-   **Sprites Animados:** Los Pokémon se muestran con sus sprites animados de la 5ª Generación.
-   **Efectos de Sonido:** Sonidos minimalistas para aciertos y errores que se generan directamente en el navegador.
-   **Contador de Racha:** ¡Lleva la cuenta de cuántas respuestas correctas llevas seguidas!
-   **Educativo:** Aprende la tabla de tipos con una explicación clara en cada ronda.
-   **Totalmente Responsive:** Juega cómodamente desde tu ordenador, tablet o móvil.

## 🛠️ Tecnologías Utilizadas

Este proyecto está construido únicamente con tecnologías web del lado del cliente, lo que lo hace ligero y fácil de desplegar.

-   **HTML5:** Para la estructura básica del juego.
-   **Tailwind CSS:** Para un diseño moderno y responsivo de forma rápida.
-   **JavaScript (Vanilla):** Para toda la lógica del juego, incluyendo:
    -   Llamadas a la [PokéAPI](https://pokeapi.co/) para obtener los datos de los Pokémon.
    -   Generación de sonidos con la `Web Audio API`.
    -   Manipulación del DOM para actualizar la interfaz.

## 🚀 Cómo Ejecutar Localmente

No necesitas ninguna herramienta de compilación ni servidor. Simplemente:

1.  Clona o descarga este repositorio.
2.  Abre el archivo `index.html` en tu navegador web preferido (como Chrome, Firefox, etc.).
3.  ¡Y listo para jugar!

## 🌐 Despliegue

Este proyecto está listo para ser desplegado gratuitamente en **GitHub Pages**. Solo tienes que subir el archivo `index.html` a un repositorio público y activar GitHub Pages en la configuración del mismo.

## 🙏 Agradecimientos

-   A la **[PokéAPI](https://pokeapi.co/)** por proporcionar una increíble y gratuita base de datos de Pokémon.
-   A **Pokémon** y **Nintendo** por crear este universo tan fantástico.
