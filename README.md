<!DOCTYPE html>
<html lang="en"> <!-- Indica el idioma de la página (español) -->
<head>
    <meta charset="UTF-8"> <!-- Codificación de caracteres universal (Es el que se utiliza para todo código HTML5) -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
    <title>Ejercitación HTML - MDN</title> <!-- El Título es importante para SEO y para la visualización de la pestaña en el navegador -->
</head>
<body>
    <!-- HEADER: Contenido introductorio/semántico para la página -->
    <header>
        <h1>Ejercitación CLASE 3 HTML</h1> <!-- Solo un h1 por página (Es lo recomendable, por SEO)-->
        <p>Recrear la estructura del navegador lateral izquierdo de MDN Web Docs</p> <!-- Descripción en párrafo ya que no corresponde encabezado-->
    </header>
    
    <!-- NAV: Sección de navegación principal --> 
    <nav>
        <!-- 
        Jerarquía de encabezados:
        h1 (en header) > h2 (secciones principales)
        -->
        <h2><a href="#html">HTML</a></h2> <!-- #como placeholder (enlace interno) -->
        <!-- Lista anidada para un menú multinivel (Nivel 1-2) -->
        <ol> <!-- Lista ordenada (ol) para el menú principal --> 
            <!-- PRIMER NIVEL ♠-->
            <li>
                <a href="#guides">Guides</a> <!-- #guides como placeholder - marcador de posición - solo como referencia de que debe ir un LINK -->
                
                <!-- SEGUNDO NIVEL ♥ (submenú) -->
                <ol> <!-- Lista ordenada (ol) para el submenú -->
                    <li><a href="#content-categories">Content categories</a></li>
                    <li><a href="#quirks-and-standards-modes">Quirks and standards modes</a></li>
                    <li><a href="#comments">Comments</a></li>
                    <li><a href="#constraint-validation">Constraint validation</a></li>
                    <li><a href="#microdata">Microdata</a></li>
                    <li><a href="#microformats">Microformats</a></li>
                    <li><a href="#responsive-images">Responsive images</a></li>
                    <li><a href="#viewport-meta-element">Viewport meta element</a></li>
                </ol>
            </li>
            
            <!-- PRIMER NIVEL ♠ -->
            <li>
                <a href="#how-to">How To</a>
                
                <!-- SEGUNDO NIVEL ♥ -->
                <ol> <!-- Lista ordenada (ol) para el submenú -->
                    <li><a href="#cross-origin-images">Cross-origin images</a></li> 
                </ol>
            </li>
            
            <!-- PRIMER NIVEL ♠ -->
            <li>
                <a href="#reference">Reference</a>
                
                <!-- SEGUNDO NIVEL ♥ -->
                <ol>   <!-- Lista ordenada (ol) para el submenú -->
                    <li><a href="#elements">Elements</a></li>
                    <li><a href="#input-types">&lt;input&gt; types</a></li> <!-- Símbolos escapados correctamente ya que los angulares están reservados para código--> 
                    <li><a href="#attributes">Attributes</a></li>
                    <li><a href="#global-attributes">Global attributes</a></li>
                </ol>
            </li>
        </ul>
    </nav>
</body>
</html>
