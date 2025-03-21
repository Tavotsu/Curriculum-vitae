-----------------------------------------------------------------------
1. ¿Qué etiquetas nuevas investigaste?
   
R:
-- <iframe>

-- UTF-8 simbolos (Ej: &#9856)

-- class="pdf-container"

-----------------------------------------------------------------------

2. ¿Para qué sirven y cómo las aplicaste en tu currículum?

R: 
-- Etiqueta <iframe>

Sirve para insertar otro documento (como un PDF, video o página web) dentro del documento actual.

Aplicación en el currículum: Lo utilicé para insertar los archivos pdf de mis certificados y que asi
sea mas facil la visualizacion de estos mismos.

-- UTF-8 simbolos (Ej: &#9856)

Propósito: Permite la decoracion de la pagina agregando puntos, figuras geometricas, etc

Aplicación en el currículum: Lo utilice para decorar algunos puntos en la seccion experiencia laboral

-- Clase pdf-container

Propósito: Es una clase que permite a los contenedores alojar PDFs u otros elementos.

Aplicación en el currículum: Lo utilice para insertar los certificados a la pagina para que se puedan visualizar sin necesidad de descargarlos.

-----------------------------------------------------------------------

3. Ejemplo de código en HTML donde las utilizaste
<!-- iframe y pdf-container  -->

        <div id="CertEng" popover>
            <div class="pdf-container">
              <iframe src="Cambridge certificate.pdf" width="800" height="600"></iframe>
            </div>
        </div>

        <div id="CertEmp" popover>
            <div class="pdf-container">
              <iframe src="Certificado emprendimiento_.pdf" width="800" height="600"></iframe>
            </div>
        </div>

        <div id="CertPython" popover>
            <div class="pdf-container">
              <iframe src="Python.pdf" width="800" height="600"></iframe>
            </div>
        </div>

<!--Simbolos UTF-8-->        
<p>
    
    &#9679;<strong>  Nombre:</strong> Gustavo Santana Fuentes<br>
    &#9679;<strong>  Fecha de nacimiento:</strong> 14-06-2005<br>
    &#9679;<strong>  Correo:</strong> gustavosantanafue@gmail.com<br>
    &#9679;<strong>  GitHub: <a href="https://github.com/Tavotsu">Click aqui</a>
</p>
