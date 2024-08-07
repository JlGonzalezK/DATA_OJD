# Ejercicio de visualización de datos georreferenciados: extracción, cruce y análisis de datos del DANE, IDECA-UAECD y OJD

<p align="center">
Jorge Luis González–Castellanos**


<p align="center">
**Estudiante de pregrado en sociología. Universidad Nacional de Colombia, Sede Bogotá
</p>

<p align="center">
**Participante del Observatorio Javeriano de las Desigualdades. Pontificia Universidad Javeriana, Bogotá
</p>

## Introducción
Este proyecto contiene los resultados del estudio, cruce, análisis y extracción de datos del Censo Nacional de Población y Vivienda 2018 publicado por Departamento Administrativo Nacional de Estadística y datos catastrales provistos por la Infraestructura de Datos Espaciales del Distrito Capital de la Unidad Administrativa Especial de Catastro Distrital, ambos conjuntos de naturaleza abierta, correspondientes a la Unidad de Planeción Zonal número 52 (UPZ La Flora) en la ciudad de Bogotá, capital de la República de Colombia, así como con datos obtenidos del ejercicio investigativo realizado desde el Observatorio Javeriano de Las Desigualdades en dicho territorio.  

Para el ejercicio se emplearon múltiples herramientas de software elegidas por su favorable curva de aprendizaje, el cual he pensado para ser reproducido por no-especialistas en Tecnologías de la Información, con algún interés en este tipo de técnicas, y en el análisis de datos sociales. Sólo se requiere de voluntad para aprender y un conocimiento fundamental en el software empleado, que bien se puede adquirir durante el desarrollo del proceso.

Si bien se trata de herramientas asequibles y de fácil uso, esto también implica ciertas limitaciones, las cuales espero sortear en mis próximos ejercicios de autoformación, asimismo, contemplar la posibilidad de realizar guías, en formato audiovisual, de todo el ejercicio para facilitar procesos autónomos de aprendizaje.

Es importante mencionar que los datos obtenidos del Censo **se circunscriben al área urbana de la UPZ La Flora**, ya que el nivel de desagregación de datos, en las áreas rurales contenidas en dicha delimitación territorial, no es el adecuado para segmentar las poblaciones que potencialmente habitan dichos espacios que, muy probablemente, se componen de un aproximado de 50 personas; se requiere de un riguroso proceso adicional para complementar y validar este punto.

Me enfoco en el Censo Nacional de Población y Vivienda 2018 y datos catastrales de Bogotá, con el fin de dar un primer paso orientado a proporcionar una herramienta útil para el análisis socioeconómico y territorial que pueda integrar múltiples fuentes de datos; la cual debe seguir siendo mejorada, y debe ser escalada a otras áreas geográficas, con arreglo –al menos– a las necesidades del Observatorio.

## Objetivos
- Este proyecto tiene como objetivo principal consolidar y compartir los resultados de mi proceso de aprendizaje relativo al uso de técnicas para la extracción, implementación y análisis de fuentes cuantitativas.

- Para ello, he construido un dashboard interactivo con Power BI utilizando datos georreferenciados de diversas fuentes para probar el concepto.

## Resultados
El resultado preliminar da cuenta de la viabilidad del proyecto y de las grandes posibilidades de esta propuesta para facilitar el análisis, toma de decisiones y planeación de futuras investigaciones usando datos cuantitativos, incluso cualitativos (si se quiere, bajo la lógica de las metodologías "mixtas"). Es un producto inacabado, hay que agregar los indicadores que sean necesarios y mejorar el diseño de la interfaz; en función de una experiencia de usuario óptima.

[Pulse aquí para ir al informe preliminar (Dashboard de Power BI)](https://app.powerbi.com/view?r=eyJrIjoiYjJjODVhYjYtOTNlNi00MDQzLTlhY2QtZDI1N2VkZjk3ZjFmIiwidCI6IjU3N2ZjMWQ4LTA5MjItNDU4ZS04N2JmLWVjNGY0NTVlYjYwMCIsImMiOjR9&pageName=8e7c7264545ce0d79024&navContentPaneEnabled=false)
 

## Futuros proyectos
Mi visión a mediano/largo plazo es la construcción de un Sistema de Información a nivel nacional que contará con varias funcionalidades, entre ellas la capacidad de realizar proyecciones de población, conectar distintas fuentes de datos, y un modulo para realizar muestreos estadísticos. Esto con arreglo a facilitar futuras tareas de investigación y propiciar el aprendizaje autónomo.

## Glosario
- **OJD**: Observatorio Javeriano de las Desigualdades.
- **CNPV**: Censo Nacional de Población y Vivienda.
- **DANE**: Departamento Administrativo Nacional de Estadística (República de Colombia).
- **IDECA**: Infraestructura de Datos Espaciales para el Distrito Capital.
- **UAECD**: Unidad Administrativa Especial de Catastro Distrital (Bogotá).
- **MGN**: Marco Geoestadístico Nacional.
- **UPZ**: Unidad de Planeamiento Zonal.
- **GIS**: Sistema de Información Geográfica.
- **QGIS**: Software GIS libre y de código abierto.
- **.SHP**: extensión del formato ESRI Shapefile, estándar de facto en GIS usado para almacenar datos vectoriales de orden geográfico y sus respectivos atributos.
- **GeoJSON**: Formato de codificación de datos geoespaciales basado en JSON.
- **Mapshaper**: Herramienta basada en web para simplificación y edición de datos GIS.
- **.CSV**: extensión para archivo de texto plano que contiene valores separados por comas a manera de tabla.
- **Microsoft Office**: paquete de ofimática propiedad de Microsoft Corporation.
- **Microsoft 365**: Familia de productos de Microsoft basados en la nube.
- **Microsoft Excel**: Software popular para trabajar con hojas de cálculo, distribuido como parte de Microsoft Office, por separado (standalone) y como servicio en línea.
- **.XLSX**: extensión de archivo Open XML para hojas de calculo, nativo del Software Microsoft Excel desde su versión 2007. Es un estándar de facto en la industria del Software de Ofimática.
- **Power BI**: Herramienta de análisis de datos y visualización desarrollada por Microsoft, distribuida gratuitamente como aplicación de escritorio para sistemas Microsoft Windows y como servicio en línea.
- **Power Query**: Motor de transformación y preparación de datos incluido en Excel y Power BI.
- **DAX**: Acrónimo de Data Analysis Expressions, lenguaje de expresión de fórmulas y consultas desarrollado por Microsoft.
- **UX**: Experiencia de usuario
- **UI**: Interfaz de usuario

## Software Utilizado
- [QGIS LTR (Prizren)](https://qgis.org)
- [Mapshaper](https://mapshaper.org/)
- [Power Query](https://powerquery.microsoft.com/)
- [Microsoft Excel 2021](https://www.microsoft.com/es-es/microsoft-365/excel)
- [Microsoft Power BI](https://www.microsoft.com/es/power-platform/products/power-bi) , se puede descargar la [versión de escritorio (sólo para Windows)](https://www.microsoft.com/es-es/download/details.aspx?id=58494)
- [Icon Map](https://icon-map.com/)

## Fuentes de Datos Utilizadas

### DANE:

- **Microdatos CNPV 2018 (Bogotá)**: usar los ficheros CSV; estos contienen los datos detallados sobre población y vivienda en un formato adecuado.
  - **Tablas**:
    - `CNPV2018_1MGN_A2_11` (MGN)*: Datos geoestadísticos.
    - `CNPV2018_1VIV_A2_11` (VIV)*: Datos a nivel de vivienda.
    - `CNPV2018_1HOG_A2_11` (HOG)*: Datos a nivel de hogar.
    - `CNPV2018_1FALL_A2_11` (FALL)*: Datos sobre personas fallecidas.
    - `CNPV2018_1PER_A2_11` (PER)*: Datos sobre personas vivas.

      **NOTA:** *(título abreviado sugerido)

- **Capas del Marco Geoestadístico Nacional (MGN)**:
  - Manzanas censales
  - Sectores urbanos
  - Secciones urbanas


### IDECA-UAECD:
- **Capas Requeridas**:
  - UPZ
  - Sector catastral
  - Manzana catastral

### IMPORTANTE: es imprescindible estudiar cuidadosamente los manuales y diccionarios de datos del CNPV 2018, MGN e IDECA

## Hosting
- **GitHub:** principalmente para alojar las capas GeoJSON
- **Microsoft 365:** para publicar informe de Power BI usando una cuenta profesional o educativa (imprescindible).

## Primera Parte: Descarga y preparación de los datos
### A. Preparación del Entorno de Trabajo

1. Requisitos de hardware y software:

   - **Sistema operativo (SO) recomendado:**
      - Microsoft Windows 10/11 (64 bits).

   - **Hardware mínimo recomendado:**
      - **RAM:** 8GB
      - **CPU:** Intel i5 (gen8) o AMD Ryzen 5 (gen5)
      - **Almacenamiento libre (partición del SO):** 16GB 

2. Instalación de software:

   - Microsoft Excel 2021 (64 bits)

   - QGIS-LTR

   - Power BI **(Sólo Windows)**

   - Navegador de internet compatible: recomendados Edge, Google Chrome o Mozilla Firefox en sus veriones más recientes.

3. Servicios en línea:

   - **Cuenta Microsoft profesional o educativa con licencias -mínimo- Office 365 A1 Plus y Microsoft Fabric (Free)**

   - mapshaper.org

### B. Descarga de los Datos

1. Ir a la página de [Microdatos CNPV 2018 del DANE](https://microdatos.dane.gov.co/index.php/catalog/643/study-description).

2. Descargar las guías, diccionarios, y los microdatos censales; que para este caso se corresponden a Bogotá.

3. Las capas geográficas incluidas en la dirección de microdatos pueden ser usadas; siendo fundamental la capa de manzanas censales, **sin embargo**, para facilitar el cruce de datos catastrales, se recomienda **revisar versiones más actualizadas y completas** en el [geoportal del DANE](https://geoportal.dane.gov.co/)

4. Descargar las capas de sectores catastrales, UPZ y manzanas catastrales (para contrastar) desde la página de datos abiertos del [IDECA](https://www.ideca.gov.co/).

### C. Preparar Datos GIS

1. Filtrar áreas geográficas de interés en QGIS teniendo en cuenta las diferencias en la delimitación territorial por parte de las entidades proveedoras de las fuentes de datos.

   - Identificar UPZ

   - Seleccionar manzanas censales y otros polígonos de interes dentro del área de la UPZ y filtrar
  
   - Confirmar sectores catastrales y manzanas censales dentro del área y hacer listas

   - Guardar resultados: las listas en .CSV o .XLSX, y los polígonos en formato .SHP

   - **IMPORTANTE:** 
      - **Ejercicio de contraste:** Es imprescindible, al menos en el caso de zonas urbanas, hacer una revisión exhaustiva de la unidad geográfica mínima en común (manzana) para realizar el cruce de fuentes de manera exitosa, ya que puede haber diferencias significativas –al menos– de forma entre las fuentes disponibles.

      - La capa de manzanas censales del DANE debería contener los **datos de área catastral** para poder extraer de allí los **códigos de sector catastral** y evitar procesos adicionales, orientados a relacionar la capa resultante con los datos de la UAECD. Las últimas versiones del MGN traen datos catastrales a nivel de manzana desde donde se pueden extraer los **códigos de sector catastral**.
 
2. Crear capas personalizadas (titulo e.g. BARRIOS_OJD).

   - usando las herramientas provistas en QGIS, crear la capa de polígonos que sea pertinente, incluyendo en esta los correspondientes campos de georreferenciación, debidamente codificados, que posibiliten la integración satisfactoria del recurso resultante  con el modelo de datos.

3. Construir tabla cruzada para conectar los datos censales y geoespaciales (titulo e.g. `GEOCONECTOR`):

   **IMPORTANTE**: En esta instancia, el campo fundamental es el código de manzana DANE, pues es la delimitación geográfica mínima y relacionable con las encuestas censales, así como con las fuentes catastrales.

   - establecidas las fuentes geográficas, se procede a crear la tabla que contenga los campos de las fuentes necesarias, que se extraerán de las capas resultantes; esto permitirá la conexión de distintas fuentes tanto geográficas como geoestadísticas. 
  
   - Construir tablas adicionales por fuente geográfica con los datos físicos de las delimitaciones territoriales en cuestión (titulo e.g. `geodatos-capa_x`): incluir los campos que contengan datos fundamentales como el área, además de los campos llave para conectar con su respectiva fuente; si es necesario, incluir coordenadas geográficas del centroide de los polígonos dependiendo de las necesidades y requerimientos (e.g. para crear “heatmaps” a nivel de manzana).

   - Extraer los datos de georreferenciación del área geográfica de interés en un archivo separado por comas o una hoja de cálculo (titulo e.g. filtro_CNPV). Para este caso, la lista de los códigos de manzana seleccionados para la muestra, contenidos en la capa de manzanas del DANE.

4. Convertir capas a formato GeoJSON utilizando Mapshaper. Elegí esta herramienta al ser la mejor alternativa frente a las limitaciones de QGIS al respecto.

### D. Preparar Datos del CNPV 2018

 **Con Power Query (desde Microsoft Excel)**

1. Extraer del censo los datos del área geográfica previamente delimitada: se usará como filtro el listado de códigos de área censal obtenidos en el paso anterior (filtro_CNPV); hacer una consulta combinada entre este y el conjunto de datos contenido en la tabla de georreferenciación del censo (`MGN`) con base en la intersección resultante entre ambas, teniendo como campo común el código de manzana censal para la selección (**el resultado de esta consulta será la versión filtrada de `MGN`, fundamental para el modelo de datos**).

2. Realizar el mismo proceso con las tablas censales restantes (`VIV`, `HOG`, `FALL`, `PER`) usando como filtro la consulta resultante del paso anterior (version filtrada de `MGN`), salvo que en este paso se debe usar el campo “código de encuestas” para realizar el filtrado.

3. Guardar los resultados de la consulta en una nueva hoja de cálculo o en archivos separados por comas para cada tabla.
   - se sugiere conservar los títulos sugeridos en este ejercicio para las 5 tablas resultantes del proceso de extracción desde el CNPV 2018.

**RECOMENDACIÓN:** Ver ejemplos de los resultados del proceso hasta este punto en el [directorio de fuentes para este proyecto](https://github.com/JlGonzalezK/DATA_OJD/tree/main/sources).

### E. Construir el Dashboard en Power BI

1. Incorporar en un nuevo informe las tablas obtenidas, tanto de los datos censales filtrados (`MGN`, `VIV`, `HOG`, `FALL`, `PER`) como de los datos GIS (`GEOCONECTOR`, `geodatos-capa_x`).

2. Construir el modelo relacional de los datos:

   - **Preparación de los datos:** En las tablas resultantes del CNPV 2018 se deben crear las variables llave para realizar la conexión entre estas de manera correcta, y así poder hacer los cruces de datos que sean pertinentes entre sí.

      -  Crear llaves: Conforme a lo indicado por el DANE, en las tablas `MGN`, `VIV`, `HOG`, `PER` y `FALL` se debe crear el campo LLAVEVIV, concatenando los campos COD_ENCUESTAS y U_VIVIENDA contenidos en cada tabla, asimismo, en las tablas `FALL` y `PER` se debe crear el campo LLAVEHOG concatenando COD_ENCUESTAS, U_VIVIENDA y H_NRHOG.
    
         - Ejemplo de sentencia en tabla `MGN` (DAX):
          ```
          LLAVEVIV = MGN[COD_ENCUESTAS] & MGN[U_VIVIENDA]
          ```
         
   - **Relaciones entre tablas del CNPV 2018:** Basado en las indicaciones del DANE, se pueden establecer las cardinalidades entre las tablas de la siguiente manera:
      - `MGN` – `VIV`: 1 a 1 con llave COD_ENCUESTAS

      - `VIV` – `HOG`: 1 a muchos con llave LLAVEVIV
 
      - `HOG` – `PER`: 1 a muchos con llave LLAVEHOG

      - `HOG` – `FALL`: 1 a muchos con llave LLAVEHOG
         
   - **Relaciones para conectar con datos geoespaciales:**
      - `MGN` – `GEOCONECTOR`: muchos a uno usando la variable de código de manzana como llave
      
      - `GEOCONECTOR` – `geodatos-capa_x`: muchos a uno usando como llave el nivel de agregación geográfico respectivo

   - **Etiquetado de variables censales:**
 
      - Teniendo en cuenta las limitaciones técnicas de Power BI, especialmente respecto a las visualizaciones disponibles, se pueden establecer etiquetas para los datos censales de la siguiente manera para evitar esfuerzos innecesarios de traducción de datos; lo cual resultaría inviable para aplicar en un conjunto de datos demasiado grande:

         - Usando la función Especificar datos, crear tablas relacionales (titulo e.g. `etiqueta-COD_VARIABLE`) con los respectivos valores de una determinada variable censal en combinación con sus etiquetas, las cuales se encuentran disponibles en el diccionario de datos provisto por el DANE, asimismo, crear un indice para establecer el orden en que serán visualizados los valores; estas deben relacionarse en el modelo de datos **usando como llave la etiqueta codificada en la tabla censal (e.g. COD_VARIABLE)**.

            - Ejemplo de estructura de la tabla-etiqueta:
              | COD_VARIABLE | Etiqueta de la variable | orden-COD_VARIABLE |
              |:------------:|:-----------------------:|:------------------:|
              |       1      |       Atributo uno      |         0          |
              |       2      |       Atributo dos      |         1          |
              |      99      |      Atributo tres      |         2          |
              
            - Relación:
               - `etiqueta-COD_VARIABLE` – `TABLA_CNPV`: 1 a muchos

3. Crear visualizaciones y filtros.

## Segunda Parte: Visualización de los Datos y Georreferenciación en Power BI

Para este paso, debemos asegurarnos de subir las capas ya exportadas a formato GeoJSON al servicio de hosting (GitHub), una vez hecho este paso, podemos continuar con el proceso de visualización de los datos georreferenciados.

Es importante mencionar nuevamente las limitaciones de Power BI con respecto a las capacidades y características de las visualizaciones disponibles, al menos, de manera gratuita, sin embargo, teniendo en cuenta la naturaleza didáctica de este ejercicio, esta herramienta es –por ahora– suficiente.

**Procedimiento**

1. Crear los filtros primarios para hacer las consultas detalladas del dataset censal.

2. Crear las visualizaciones respectivas: podrán funcionar, además, como filtros secundarios de selección.

3. En el informe de Power BI agregamos la visualización Icon Map, (disponible en App Source para usuarios registrados con cuenta educativa o profesional).

   - Desde las opciones de configuración de Icon Map seleccionamos la variable de georreferenciación específica para nuestro propósito, así como la variable de medida, que puede ser la que nos resulte más conveniente.

   - Agregamos la dirección URI del recurso GeoJSON adecuado para la visualización de los datos.

4. Realizamos las pruebas de selección y filtrado respectivas para realizar los ajustes que sean necesarios, que pueden (deberían) requerir la construcción de fórmulas específicas a nuestros requerimientos.

## Fórmulas para Indicadores en Power BI

Microsoft Power BI ofrece una solución para realizar los cálculos requeridos usando la función Medida, con la cual podemos ejecutar formulas directamente en lenguaje DAX según nuestras necesidades.

A continuación, algunos ejemplos de indicadores fundamentales.

  - Conteo de población de mujeres en la muestra:
```
Mujeres = CALCULATE(COUNTROWS('PER'),'PER'[P_SEXO]=2)
```

  - Indice de feminidad:
```
Indice fem. = ([Mujeres] / [Hombres] *100)
```

  - Indice de hacinamiento:
```
Indice de hacinamiento = SUM(HOG[HA_TOT_PER]) / SUM(HOG[H_NRO_DORMIT])
```

  - Hogares efectivamente censados:
```
Total hogares efectivamente censados = (COUNTROWS(DISTINCT(PER[LLAVEHOG])))
```

## Ajustes estéticos y UX
Finalmente, hacer los ajustes estéticos y funcionales necesarios en la UI, con base en –y para mejorar– la experiencia del usuario final y publicar el dashboard.
