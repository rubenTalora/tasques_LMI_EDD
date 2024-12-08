Primer documento LMI
=
Características de los lenguajes de marcas en diferentes documentos
-
<br> <br>

1. ***HTML (HyperText Markup Language)***
    - **Propósito:** 
        Crear documentos web y definir su estructura.
        <br> <br>
    - **Características:**
        Utiliza etiquetas para definir elementos como cabeceras, párrafos, imágenes, enlaces, etc.
        Las etiquetas suelen ser predeterminadas (```<p>```, ```<a>```, ```<div>```, etc.).
        Su estructura sigue una jerarquía de elementos nidificados.
        Combina con otras tecnologías como CSS (para el estilo) y JavaScript (para la interactividad).
        Es tolerante a errores, los navegadores suelen corregir automáticamente códigos mal formados.
        Orientado a la presentación en pantalla o 
        otros medios (papel, voz, etc.).
        <br> <br>
        <br> <br>

2. ***XML (eXtensible Markup Language)***
    - **Propósito:** 
        Almacenar y transportar datos de manera legible tanto por humanos como por máquinas.
        <br> <br>
    - **Características:**
        Las etiquetas son definidas por el usuario y no son predeterminadas (flexible).
        Es estrictamente estructurado, sigue una jerarquía bien definida.
        No define la presentación, sólo estructura y describe datos.
        Es sensible a mayúsculas y minúsculas.
        Requiere que cada etiqueta abierta tenga una etiqueta de cierre (```<element>``` ```</element>```).
        Utilizado en la transmisión de datos entre sistemas (SOAP, RSS, etc.).
        <br> <br>
        <br> <br>

3. ***SVG (Scalable Vector Graphics)***
    - **Propósito:** 
        Representar gráficos vectoriales escalables dentro de páginas web u otros documentos.
        <br> <br>
    - **Características:**
        Es una aplicación de XML, por lo tanto sigue sus reglas básicas.
        Permite la creación de gráficos vectoriales como líneas, formas, texto y caminos definidos por coordenadas.
        Escalable sin pérdida de calidad, ya que trabaja con vectores y no píxeles.
        Puede contener animaciones e interactividad (normalmente con JavaScript).
        Cada elemento del gráfico puede ser manipulado por CSS y JavaScript.
        Se utiliza a menudo por gráficos web que necesitan adaptarse a múltiples dispositivos y resoluciones.
        <br> <br>
        <br> <br>

4. ***XHTML (Extensible Hypertext Markup Language)***
    - **Propósito:**Una combinación de HTML y XML, pensado para llevar la rigurosidad de XML a documentos HTML.
    <br> <br>
    - **Características:**
        Las etiquetas de HTML deben seguir las normas estrictas de XML (todas las etiquetas deben cerrarse correctamente, los atributos deben estar entre comillas, etc.).
        Mantiene la misma estructura y etiquetas que HTML, pero con una sintaxis más estricta.
        Aporta mayor consistencia e intercambiabilidad en entornos XML.
        <br> <br>
        <br> <br>


5. ***MathML (Mathematical Markup Language)***
    - **Propósito:** 
        Representar fórmulas y expresiones matemáticas en documentos XML.
    <br> <br>
    - **Características:**
        Es un subconjunto de XML diseñado específicamente para representar expresiones matemáticas complejas.
        Utilizado a menudo junto con otros lenguajes como HTML o SVG.
        Las etiquetas describen la semántica de las expresiones matemáticas (```<math>```, ```<mrow>```, ```<mi>```, ```<mo>```, etc.).