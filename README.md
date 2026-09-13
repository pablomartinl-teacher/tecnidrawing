
                   MANUAL DE USUARIO - MOTOR CAD 


Bienvenido al Motor CAD diseñado específicamente para Dibujo Técnico. 
Este documento explica todas las funciones, herramientas y atajos para sacar 
el máximo provecho a la aplicación.

-----------------------------------------------------------------------------
1. CONCEPTOS BÁSICOS DEL MOTOR
-----------------------------------------------------------------------------
- DIBUJO "CLIC A CLIC": Para dibujar (segmentos, circunferencias, etc.) NO 
  necesitas mantener el botón del ratón pulsado. Haz un clic para marcar 
  el inicio, mueve el ratón libremente, y haz un segundo clic para terminar.
- MEDIDAS EXACTAS POR TECLADO: Mientras mueves el ratón para dibujar un 
  elemento, simplemente teclea un número en tu teclado (ej. "50") y pulsa 
  ENTER. El elemento se dibujará con esa medida exacta en milímetros hacia 
  la dirección donde apunta el cursor.
- IMANTACIÓN (SNAPPING): El cursor se pegará automáticamente a los extremos, 
  puntos medios, centros, vértices e intersecciones exactas de las líneas. 
  Verás un pequeño círculo rojo cuando el imán detecte un punto clave.

-----------------------------------------------------------------------------
2. BARRA SUPERIOR (GESTIÓN DE ARCHIVOS Y LIENZO)
-----------------------------------------------------------------------------
- Tamaño Lámina: Cambia las dimensiones del papel en milímetros (Por 
  defecto DIN A4: 297x210mm).
- Márgenes: Genera un recuadro automático. Puedes darle la distancia a los 
  bordes del papel (ej. 25mm a la izquierda) o darle un Ancho/Alto exacto.
- PDF Base: Permite cargar un archivo PDF de tu ordenador para usarlo 
  como plantilla o enunciado de fondo.
- Guardar / Cargar: Guarda el estado editable de tu dibujo en un archivo 
  ligero (.json) para seguir trabajando otro día o enviarlo a los alumnos.
- PDF (Rojo): Exporta tu trabajo final a un PDF en alta calidad geométrica, 
  perfecto para imprimir a escala 1:1.
- Nuevo Lienzo: Borra todo y empieza con un papel en blanco.

-----------------------------------------------------------------------------
3. BARRA DE PROPIEDADES (ESTILOS)
-----------------------------------------------------------------------------
(Ubicada debajo de la barra superior)
- Botón Imán (Verde): Activa o desactiva la atracción automática del cursor.
- Color: Cambia el color de la línea del próximo elemento que dibujes.
- Fondo: Color de relleno para la herramienta de Relleno/Rayado.
- Grosor: Grosor de la línea en milímetros (0.1 a 8 mm).
- Trazo: Elige entre línea continua, discontinua o raya-punto (ejes).
- Acabado: Añade puntas de flecha o líneas de 45º a los extremos del 
  siguiente trazado (ideal para acotaciones manuales).
- Lados Polígono: Define el número de lados para la herramienta Polígono.

-----------------------------------------------------------------------------
4. HERRAMIENTAS DE DIBUJO (PANEL LATERAL)
-----------------------------------------------------------------------------
[👆] Selector / Mover
  - Un clic en un elemento: Lo selecciona (se pone azul) para arrastrarlo.
  - Mantener CTRL + Clic: Selecciona varios elementos a la vez.
  - Doble Clic en un elemento: Abre un menú para cambiar su color, 
    grosor, o editar su texto.

[📏] Segmento
  - Clic 1: Punto de inicio. Clic 2: Punto final.
  - Atajo: Mantén pulsada la tecla SHIFT para dibujar en modo Ortogonal 
    (líneas perfectamente horizontales o verticales).

[📏 mm] Acotar (Normativa ISO)
  - Requiere 3 pasos:
    1. Clic en el inicio de la línea a medir.
    2. Clic en el final de la línea a medir.
    3. Mueve el ratón hacia arriba, abajo o un lado y haz Clic. La cota 
       se dibujará desplazada a 5mm, con líneas de extensión y el texto 
       cortando la línea central.

[⫽] Paralela y [⟂] Perpendicular
  - Clic 1: Toca una línea base ya dibujada (se pondrá azul).
  - Clic 2 y 3: Dibuja tu nueva línea en cualquier parte; el motor 
    bloqueará la inclinación para que sea perfectamente paralela o 
    perpendicular a la seleccionada.

[📐] Línea con Ángulo
  - Clic 1: Toca una línea de referencia.
  - Te pedirá un ángulo exacto (ej: 30, 45, 60 grados).
  - Clic 2 y 3: Dibuja la línea que mantendrá ese ángulo respecto a la base.

[⭕] Circunferencia
  - Clic 1: Marca el centro. Clic 2: Marca el radio.

[◿] Arco (3 Pasos)
  - Clic 1: Marca el centro del compás.
  - Clic 2: Marca el punto de inicio (Apertura del compás).
  - Clic 3: Gira el ratón y marca dónde termina el trazado del arco.

[〰] Curva (Spline)
  - Ve haciendo clics para añadir los puntos de la curva.
  - Para finalizar, haz clic cerca del último punto que pusiste.
  - Si usas el Selector [👆] y haces clic en la curva, verás sus puntos de 
    control y podrás arrastrarlos para modificar la curvatura.

[⬟] Polígono Regular
  - Cambia los lados en la Barra de Propiedades.
  - Clic 1: Marca el centro. Clic 2: Marca la distancia del radio.

[🔲] Relleno / Rayado de piezas
  - Ve haciendo clics para dibujar el contorno cerrado de la pieza.
  - Haz clic cerca del inicio (o pulsa ESC) para cerrar la figura. 
  - Se rellenará automáticamente con líneas a 45º (patrón de corte ISO).

[➕] Punto
  - Añade un punto en forma de cruz horizontal y vertical (+).

[ A ] Texto y [🏷] Etiqueta
  - Texto: Haz clic en cualquier lugar y escribe un texto libre.
  - Etiqueta: Si haces clic sobre una línea dibujada, el texto que 
    escribas se rotará y alineará automáticamente con la pendiente de esa línea.

[🧽] Borrador
  - Opción A: Haz clic directamente sobre una línea para borrarla.
  - Opción B: Haz clic en un área vacía y arrastra para crear un 
    rectángulo azul. Todo lo que quede dentro se borrará.

-----------------------------------------------------------------------------
5. ATAJOS DE TECLADO RÁPIDOS
-----------------------------------------------------------------------------
- Escribir un número:   Fija la longitud, radio o ángulo exacto.
- Enter:                Confirma la medida escrita por teclado.
- Shift (Mantener):     Modo Ortogonal (Rectas a 0º o 90º).
- Escape (ESC):         Cancela la herramienta actual o suelta la selección.
- Suprimir / Retroceso: Borra los elementos seleccionados con el Dedo [👆].
- Ctrl + Z:             Deshacer última acción.
- Ctrl + Y:             Rehacer acción.
- Ctrl + Clic:          Selección múltiple de elementos.

=============================================================================
Desarrollado para la enseñanza de Educación Plástica y Dibujo Técnico
=============================================================================
