## 🕹️NEXUS-9: Escape Laboratory — [Level 2]

 ![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?logo=flutter) ![Dart](https://img.shields.io/badge/Dart-3.x-0175C2?logo=dart) ![Node.js](https://img.shields.io/badge/Node.js-20%2B-339933?logo=node.js) ![Express](https://img.shields.io/badge/Express.js-REST-000000?logo=express) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-4169E1?logo=postgresql) ![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?logo=github) ![Jira](https://img.shields.io/badge/Jira-Project-0052CC?logo=jira) ![Figma](https://img.shields.io/badge/Figma-UX%2FUI-F24E1E?logo=figma)

> **Proyecto académico** — SENA ADSO / Centro de Diseño Tecnológico e Innovación

* **Integrantes:** 
  * [Juan Felipe Marin Restrepo] (Scrum Master)
  * [Dylan Yesid Cardona Posada]
  * [Juan David Vinasco Perez]
  * [Karen Daniela Tamayo]


### 🎰 Concepto del juego

**Género:** Escape Room educativo 2D.

**Estilo:** ciencia ficción, laboratorio tecnológico, misterio, programación y lógica.

**Interacción:** click/tap, botones, objetos interactivos, selección de respuestas, inventario y paneles.

No se requiere movimiento libre complejo del personaje para el MVP.


### 🦮 Personaje principal: K-9

K-9 es una **Jack Russell Terrier hembra**.

Características:

- Inteligente.
- Curiosa.
- Valiente.
- Resolutiva.

K-9 representa al jugador durante toda la experiencia.


### 🎮 Gameplay

```text
Explorar
   ↓
Interactuar
   ↓
Encontrar pistas
   ↓
Resolver puzzle
   ↓
Obtener recompensa
   ↓
Abrir puerta
   ↓
Avanzar de nivel
```


### 🚪 Nivel 2 • La Habitación de la Lógica

* **Historia:** Luna entra en una habitación circular con tres puertas: roja, azul y verde. Una pantalla anuncia: "SOLO UNA PUERTA ES SEGURA".
* **Objetivo:** Resolver los acertijos de lógica y conseguir la Llave 2.
* **Objetos y elementos:** Tres puertas, luces de colores, panel de condiciones, números y teclado.
  

### ◽ Nivel 2 — Control Room

**Dificultad:** Media  
**Concepto:** Condicionales if/else  
**Objetivo:** Reparar el sistema lógico que controla las puertas.

```text
if code == 927:
    openDoor()
else:
    keepDoorClosed()
```


### 🧩 Puzzles y soluciones

* **Puzzle 1 — Luces:** roja apagada, azul encendida, verde apagada. La pista dice que la puerta correcta tiene la luz encendida.
* **Puzzle 2 — Condiciones:** Roja: \(5 > 10\); Azul: \(10 > 5\); Verde: \(2 > 8\). Solo la condición azul es verdadera.
* **Puzzle 3 — Código:** aparecen 4, 7 y 2. La pista indica ordenarlos de menor a mayor: 247.


* **Recompensa:** 🗝️ LLAVE 2

* **Final del nivel:** Al introducir 247 aparece "LÓGICA CORRECTA". Se guarda el progreso y se abre el Nivel 3.

> ⚙️ **Responsabilidad técnica:** Diseñar reglas, pistas, soluciones, niveles de dificultad y feedback. Documentar claramente la respuesta correcta para integración.


### ⚙️ Mecánicas

- **Interacción:** seleccionar objetos para obtener información o ejecutar acciones.
- **Inventario:** almacenar objetos obtenidos.
- **Puertas:** bloqueadas, desbloqueadas y abiertas.
- **Pistas:** ayudan al jugador y reducen puntuación.
- **Temporizador:** muestra el tiempo restante del nivel.
- **Niveles:** completar el nivel actual desbloquea el siguiente.

### 📦 Inventario de ejemplo

```text
INVENTARIO

[Access Card]
[Master Code]
```

### 🛠️ Tecnologías

| Área | Tecnología |
|---|---|
| Frontend | Flutter / Dart |
| Backend | Node.js / Express |
| Base de datos | PostgreSQL |
| API | REST |
| Diseño | Figma / Canva |
| Gestión | Jira Software |
| Control de versiones | Git / GitHub |
| Pruebas API | Postman |
| IDE | Visual Studio Code / Android Studio |
