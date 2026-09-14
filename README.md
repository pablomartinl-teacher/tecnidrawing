![Badge](https://hitscounter.dev/api/hit?url=https%3A%2F%2Fgithub.com%2Fpablomartinl-teacher%2Ftecnidrawing&label=&icon=github&color=%23198754&message=&style=flat&tz=Europe%2FMadrid)

                 # 📐 Motor CAD - TecniDib

![Versión](https://img.shields.io/badge/Versi%C3%B3n-4.8-blue?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Licencia](https://img.shields.io/badge/Licencia-Open_Source-success?style=for-the-badge)

Una aplicación web de Dibujo Técnico y Diseño Asistido por Ordenador (CAD) diseñada específicamente para la docencia en Educación Plástica y Visual. Se ejecuta de forma nativa en el navegador, sin necesidad de instalación ni bases de datos, permitiendo trabajar en pizarras digitales, ordenadores, tablets y exportar los resultados a formato PDF a escala exacta 1:1.

---

## 📑 Índice
1. [Filosofía de Uso](#-filosofía-de-uso)
2. [Gestión de Archivos y Lienzo](#-gestión-de-archivos-y-lienzo)
3. [Herramientas de Dibujo](#-herramientas-de-dibujo)
4. [Edición Avanzada y Estilos](#-edición-avanzada-y-estilos)
5. [Atajos de Teclado](#-atajos-de-teclado-cheat-sheet)

---

## 🧠 Filosofía de Uso

Para garantizar la máxima precisión técnica, el motor utiliza un paradigma profesional:

*   **Trazado "Clic a Clic":** No es necesario mantener pulsado el botón del ratón para dibujar. Haz un clic para marcar el punto de inicio, mueve el ratón libremente, y haz un segundo clic para terminar.
*   **📐 Medidas por Teclado:** Mientras mueves el ratón para trazar una línea, un radio o un ángulo, simplemente **teclea un número** (ej: `50`) y pulsa <kbd>Enter</kbd>. El elemento se dibujará con esa medida milimétrica exacta en la dirección de tu cursor.
*   **🧲 Imantación Automática (Snapping):** El cursor se verá atraído automáticamente a extremos de líneas, puntos medios, centros de circunferencias, vértices e **intersecciones exactas**. Lo sabrás porque aparecerá un pequeño círculo rojo indicador.
*   **❌ Cancelación Rápida:** Si estás a mitad de trazar cualquier elemento y te equivocas, simplemente haz **Clic Derecho** (o pulsa <kbd>ESC</kbd>) para cancelar el dibujo en curso.

---

## 📄 Gestión de Archivos y Lienzo

En la barra superior encontrarás los controles generales del proyecto:

*   **Tamaño Lámina:** Ajusta el tamaño del papel en milímetros (Por defecto DIN A4 apaisado: 297x210 mm).
*   **Márgenes:** Genera un recuadro paramétrico basado en las distancias a los bordes del papel o un tamaño exacto. *(Nota: Se generan mediante segmentos independientes para que puedas borrarlos o modificarlos individualmente).*
*   **PDF Base:** Importa un PDF desde tu equipo para usarlo como enunciado o plantilla de calco (se ajusta al fondo en alta calidad).
*   **Guardar / Cargar:** Exporta el estado actual editable en un archivo local `.json` para continuar otro día o enviarlo a tus alumnos.
*   **Exportar PDF:** Renderiza tu solución en un documento PDF a escala real respetando los grosores y tipos de línea.
*   **Zoom:** Usa los botones `➕`/`➖`, o mantén <kbd>Ctrl</kbd> + **Rueda del ratón** para acercarte al milímetro. En tablets, utiliza el gesto de *pellizcar*.

---

## 🧰 Herramientas de Dibujo

Cada herramienta tiene un **atajo de teclado** asignado (una sola letra) para agilizar el flujo de trabajo en clase:

| Icono | Herramienta | Atajo | Comportamiento |
| :---: | :--- | :---: | :--- |
| 👆 | **Selector / Mover** | <kbd>V</kbd> | Haz clic para mover. Mantén <kbd>Ctrl</kbd> para multiselección. |
| 📏 | **Segmento** | <kbd>L</kbd> | Clic inicial y final. Mantén <kbd>Shift</kbd> para trazos Ortogonales (0º/90º). |
| 📏 | **Acotar (Normativa ISO)** | <kbd>M</kbd> | **3 Pasos:** 1º Clic inicio, 2º Clic fin, 3º Desplaza el ratón hacia un lado para separar la cota 5mm y haz clic para fijarla. |
| ⫽ | **Paralela** | <kbd>P</kbd> | Selecciona una línea base. Luego dibuja libremente; la inclinación estará bloqueada. |
| ⟂ | **Perpendicular** | <kbd>O</kbd> | Selecciona una línea base. Dibuja bloqueado a 90º respecto a ella. |
| 📐 | **Línea Ángulo** | <kbd>A</kbd> | Selecciona línea base. Introduce el ángulo (ej: `45`) y traza. |
| ⭕ | **Circunferencia** | <kbd>C</kbd> | Clic para el centro, mueve para definir el radio (Muestra línea guía). |
| ◿ | **Arco** | <kbd>R</kbd> | **3 Pasos:** 1º Centro, 2º Punto de Inicio (fija el radio), 3º Punto Final. |
| 〰 | **Curva (Spline)** | <kbd>S</kbd> | Ve haciendo clics. Haz clic cerca del último punto para cerrar el trazado. |
| ⬟ | **Polígono** | <kbd>G</kbd> | Configura los lados en la barra superior. 1º Clic Centro, 2º Radio. |
| 🔲 | **Relleno (Rayado)** | <kbd>F</kbd> | Dibuja un contorno cerrado haciendo clics. Se rellenará automáticamente (ideal para cortes en piezas). |
| ➕ | **Punto** | <kbd>X</kbd> | Dibuja un punto exacto en forma de cruz ortogonal. |
| A | **Texto Libre** | <kbd>T</kbd> | Añade una etiqueta de texto horizontal. |
| 🏷 | **Etiqueta Orientada** | <kbd>E</kbd> | Toca un elemento. La etiqueta se **rotará y separará automáticamente** para no pisar el trazado. |
| 🧽 | **Borrador** | <kbd>B</kbd> | Haz clic sobre un elemento, o arrastra en el vacío para crear una caja de borrado masivo. |

---

## ⚙️ Edición Avanzada y Estilos

### Panel de Estilos (Barra Inferior)
Antes de dibujar un elemento, puedes definir sus propiedades globales:
*   **Imantado:** Enciende/Apaga el motor de Snapping automático.
*   **Color de Línea y Fondo:** Elige el color del trazo y el relleno.
*   **Grosor y Trazo:** Define milímetros (ej: `0.5`) y tipo de línea (Continua, Oculta discontinua, Ejes raya-punto).
*   **Acabados (Cotas):** Añade terminaciones de flechas bidireccionales o líneas a 45º para acotaciones.

### Edición Post-Trazado (Clic Derecho)
Si ya has dibujado un elemento y quieres modificarlo:
1. Activa la herramienta **Selector** (<kbd>V</kbd>).
2. Haz **Clic Derecho** sobre cualquier línea, círculo o texto.
3. Se abrirá un panel flotante donde podrás editar su grosor, color, tipo de línea, o si es un texto, cambiar su tamaño y contenido en tiempo real.

> **💡 Truco de edición de curvas:** Si seleccionas una curva *Spline* con la herramienta Selector, verás aparecer sus **puntos de control**. Puedes arrastrar estos puntos para modificar la curvatura como en un programa de diseño vectorial profesional.

---

## ⌨️ Atajos de Teclado (Cheat Sheet)

Para una velocidad máxima de dibujo, usa la mano izquierda en el teclado y la derecha en el ratón.

| Acción | Atajo |
| :--- | :---: |
| Seleccionar / Mover | <kbd>V</kbd> |
| Medida por Teclado | Escribir número + <kbd>Enter</kbd> |
| Cancelar trazado actual | <kbd>Clic Derecho</kbd> o <kbd>ESC</kbd> |
| Borrar elemento/s seleccionado/s | <kbd>Suprimir</kbd> o <kbd>Retroceso</kbd> |
| Selección Múltiple | Mantener <kbd>Ctrl</kbd> + Clics |
| Deshacer | <kbd>Ctrl</kbd> + <kbd>Z</kbd> |
| Rehacer | <kbd>Ctrl</kbd> + <kbd>Y</kbd> |
| Zoom + / - | <kbd>Ctrl</kbd> + **Rueda Ratón** |

---
*Desarrollado para facilitar la docencia y el aprendizaje de la Geometría Descriptiva y el Dibujo Técnico.*
