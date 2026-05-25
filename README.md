# piedra-papel-tijera-como-practica-de-python
Practica de python con un juego de piedra papel y tijera

#  Piedra, Papel o Tijera

Un juego clásico de **Piedra, Papel o Tijera** jugado en la terminal contra una IA, con arte ASCII animado según el resultado de cada partida.

---

##  Descripción

Este programa te permite jugar una partida de Piedra, Papel o Tijera contra la computadora. La IA elige su opción de forma aleatoria y el programa determina automáticamente el ganador. El resultado se acompaña de una ilustración en arte ASCII que varía según quién gane o si hay empate.

---

##  Requisitos

- **Python 3.x**
- No requiere librerías externas (solo el módulo estándar `random`)

---

##  Cómo ejecutar

1. Clona o descarga el archivo `piedra_pape_tijera.py`.
2. Abre una terminal en la carpeta donde se encuentra el archivo.
3. Ejecuta el script con:

```bash
python piedra_pape_tijera.py
```

4. Cuando se te pida, escribe tu elección:

```
elije: piedra, papel, tijera:
```

---

##  Cómo jugar

- Escribe exactamente una de las tres opciones: `piedra`, `papel` o `tijera` (en minúsculas).
- El programa mostrará tu elección y la de la IA.
- El resultado puede ser:
  - **Jugador gana** 🏆
  - **IA gana** 🤖
  - **Empate** 🤝
- Cada resultado muestra una imagen diferente en arte ASCII.

---

##  Reglas del juego

| Jugador | IA     | Resultado     |
|---------|--------|---------------|
| Piedra  | Tijera | Jugador gana  |
| Papel   | Piedra | Jugador gana  |
| Tijera  | Papel  | Jugador gana  |
| Piedra  | Papel  | IA gana       |
| Papel   | Tijera | IA gana       |
| Tijera  | Piedra | IA gana       |
| Piedra  | Piedra | Empate        |
| Papel   | Papel  | Empate        |
| Tijera  | Tijera | Empate        |

---

## ⚠️ Consideraciones

- La entrada del jugador es **sensible a mayúsculas/minúsculas**. Solo se acepta en minúsculas: `piedra`, `papel`, `tijera`.
- Si se ingresa una opción inválida, el programa mostrará el mensaje:
  ```
  porfavor solo seleciones las opciones piedra, papel o tijera
  ```
- La IA elige de forma completamente aleatoria usando `random.choice()`.

---

##  Estructura del código

```
piedra_pape_tijera.py
├── Importación de random
├── Selección aleatoria de la IA
├── Input del jugador
├── Arte ASCII (ia_win, Ia_lose, ia_empate)
└── Lógica de comparación con if/elif/else
```

---

## 👤 Autor

Proyecto personal de práctica en Python.
