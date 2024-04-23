## Requisitos Funcionales y Criterios de Aceptación
### 1. Configuración de Nivel de Dificultad
**Requisito:** El sistema debe permitir a los jugadores seleccionar el nivel de dificultad antes de comenzar el juego.

**Criterios de Aceptación:**
- Opciones de dificultad fácil, medio y difícil disponibles para selección.
- La configuración de dificultad debe influir en la mecánica del juego, como la frecuencia de regeneración de imágenes y la puntuación.
- Tiempos de regeneración específicos:
  - Fácil: cada 8 segundos.
  - Medio: cada 6 segundos.
  - Difícil: cada 5 segundos.


### 2. Gestión de Puntaje y Validación de RespuestasRequisito: 

**Requisito:** El sistema debe gestionar y actualizar el puntaje del jugador en tiempo real, validando las respuestas durante el juego.

**Criterios de Aceptación:**
- El puntaje del jugador se actualiza automáticamente según las respuestas seleccionadas.
- Se valida si la selección de una casilla es correcta o incorrecta comparándola con la imagen objetivo en la barra lateral.
- Se aplican bonificaciones por respuestas correctas y penalizaciones por respuestas incorrectas en la puntuación del jugador.


### 3. Inicio y Reinicio de JuegoRequisito:

**Requisito:** El jugador debe poder iniciar un nuevo juego en cualquier momento, lo que implica restablecer el tablero y las condiciones del juego según el nivel de dificultad elegido.

**Criterios de Aceptación:**
-Existe un botón o función clara para iniciar un nuevo juego.
- Al iniciar un nuevo juego, se restablece el tablero y se aplican las condiciones del nivel de dificultad seleccionado.


### 4. Visualización de Instrucciones y ReglasRequisito: 

**Requisito:** El juego debe proporcionar instrucciones detalladas y reglas de juego en la barra lateral para que el jugador las consulte antes de comenzar a jugar.

**Criterios de Aceptación:**
- Las instrucciones y reglas del juego son claras y accesibles desde la interfaz.
- Los jugadores pueden consultar las instrucciones en cualquier momento durante el juego para aclarar dudas.


### 5. Finalización del JuegoRequisito: 
**Requisito:** El juego debe finalizar cuando el jugador ha seleccionado todas las celdas en el tablero, mostrando un mensaje de felicitaciones o derrota según la puntuación obtenida.

**Criterios de Aceptación:**
- Al completar todas las selecciones en el tablero, se muestra un mensaje de felicitaciones si la puntuación es positiva.
- Si la puntuación es negativa, se muestra un mensaje de derrota.
- Se proporciona un botón para regresar a la página principal después de finalizar el juego.
