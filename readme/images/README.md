# 📘 Estudio sobre la Brecha Digital en España

Este proyecto está enfocado en analizar la **brecha digital** en España, identificando las desigualdades en el acceso, uso y consecuencias de las **Tecnologías de la Información y la Comunicación (TIC)** en distintos sectores de la población española. 

## 🚀 Objetivos

- **Obtener** las dimensiones de la brecha digital en España.

- **Identificar** los patrones de la brecha digital presentes en España, considerando variables como el acceso a internet, la disponibilidad de dispositivos y el uso de TICs en los hogares. 

- **Profundizar** en las inferencias e impacto que creemos existe entre este fenómeno y el nivel de formación/ocupación de la población y la tasa de desempleo por regiones del país. 

- **Generar visualizaciones interactivas** para facilitar la comprensión y presentación de los resultados.

## 📂 Estructura del Proyecto

### 📂 documentacion: proyecto-guia

  - resumen_ejecutivo del estudio y objetivos principales.
  - marco_teorico que fundamenta el estudio.
  - metodologia empleada para el análisis de la brecha digital.
  - conclusiones finales.

### 📂 datos:

- **/csv**: Contiene los archivos CSV con los datos extraídos para este estudio.


### 📂 transformaciones: 

  - `edaUE-python.ipynb`: Jupyter_notebook encargado de la limpieza de los datos extraídos referentes a la UE.

  - `dataset_global.ipynb`: Jupyter_notebook que realiza el estudio y limpieza de varios de los csv estraídos del INE (Instituto Nacional de Estadística) como valor central de la situación en España .

### 📂 visualizaciones: 

  - `brecha_digital.pbix`: Archivo de Power BI con las visualizaciones y gráficos interactivos para la exploración de los resultados.

## 🔍 Conclusiones derivadas del análisis:

**Cambio de enfoque en la investigación sobre brecha digital:**

**Ya no basta con medir cuántas personas tienen acceso a Internet o dispositivos. Es necesario analizar cómo usan las personas la tecnología y si lo hacen de manera efectiva y productiva.**

### Desigualdades en las competencias digitales:

Aunque muchas personas tienen acceso a tecnología, existe una gran disparidad en el nivel de competencias digitales. Grupos vulnerables (adultos mayores, personas con bajo nivel educativo o en zonas rurales) tienden a tener menores habilidades digitales.

### Productividad digital como nuevo indicador:

Se debe evaluar si las personas pueden traducir el acceso en beneficios concretos, como empleo, educación, salud o participación cívica.
**La productividad del uso digital debe convertirse en un criterio central para medir la inclusión digital real.**

### Impacto en la calidad de vida:

**El verdadero valor del acceso digital está en cómo contribuye a mejorar la calidad de vida de los usuarios.**
Esto incluye desde oportunidades laborales hasta acceso a servicios públicos, información útil y redes de apoyo.

### Necesidad de políticas públicas más específicas:

Las políticas no deben centrarse sólo en ofrecer conectividad, sino en formación en competencias digitales, adaptadas a cada grupo social.
**Programas de alfabetización digital deben ir más allá de lo básico, incorporando habilidades para el trabajo, seguridad digital, pensamiento crítico y resolución de problemas.**


## 🪜 Próximos pasos

A partir de las conclusiones obtenidas, se plantea la necesidad de continuar el análisis con una perspectiva más focalizada y contextual. En particular, se identifican líneas clave de acción para avanzar en la comprensión y reducción de la brecha digital:

---

## 1. Estudio específico de Ceuta y Melilla

![Mapa Ceuta y Melilla](images/ceuta_melilla.png)

Ceuta y Melilla presentan **características estructurales particulares**, tanto por su evolución histórica como por sus **elevadas tasas de desempleo**, que justifican una investigación diferenciada. Se propone:

- Analizar cómo estas tasas de desempleo **afectan el uso y la productividad del acceso a Internet**.
- Estudiar el papel que juega la brecha digital en el **acceso al empleo, la educación y los servicios públicos digitales** en ambas ciudades.
- Comparar estos resultados con otras regiones con desafíos similares para establecer patrones o singularidades.

---

## 2. Profundizar en la relación entre uso de Internet y desempleo

![Icono conexión y trabajo](images/empleo_internet.png)

Es fundamental **comprender mejor cómo el nivel de uso digital incide en la empleabilidad** y viceversa. Para ello:

- Explorar correlaciones entre **niveles de uso de Internet, competencias digitales y tasas de desempleo** por territorios.
- Identificar si existen **barreras específicas que impiden a personas desempleadas aprovechar las herramientas digitales** para la búsqueda de empleo o el autoempleo.

---

## 3. Análisis sociodemográfico detallado por Comunidades Autónomas

![Mapa sociodemográfico España](images/mapa_ccaa.png)

Para adaptar políticas públicas eficaces, es necesario un conocimiento profundo de las realidades sociales en cada territorio. Se propone:

- **Segmentar los datos por CCAA**, analizando variables como edad, nivel educativo, entorno urbano/rural, renta media y situación laboral.
- Estudiar las **necesidades digitales específicas** de cada grupo sociodemográfico y su potencial impacto en la calidad de vida.
- Diseñar estrategias de intervención **territorializadas y basadas en evidencia**.

---

**Objetivo final:**  
Desarrollar un modelo de análisis territorial y sociodemográfico que permita identificar con mayor precisión las **brechas de uso y productividad digital** en función de contextos sociales, económicos y geográficos, contribuyendo a una **inclusión digital equitativa y efectiva** en todas las regiones de España.


## 💡 Contribuciones

Si deseas contribuir al proyecto, sigue estos pasos:

- **Haz un fork del repositorio.**

- **Crea una nueva rama (git checkout -b feature-nueva-funcionalidad).**

- **Realiza tus cambios y haz un commit.**

- **Envía un pull request con tus cambios.**



## 📚 Fuetes Principales

- **INE (Instituto Nacional de Estadística): https://www.ine.es**:
  Evolución de datos de Viviendas (2006-2024) por Comunidades y Ciudades Autónomas, tipo de equipamiento y periodo: 
  [Fuente](https://www.ine.es/jaxi/Tabla.htm?tpx=70470&L=0)

  Nivel y condiciones de vida: 
  [Fuente](https://www.ine.es/jaxi/Datos.htm?tpx=70388#_tabs-grafico)

  Datos de Viviendas por Comunidades y Ciudades Autónomas, tamaño del hogar, tipo de hogar, hábitat, ingresos mensuales netos del hogar y tipo de equipamiento.:
  [Fuente](https://www.ine.es/jaxi/Datos.htm?tpx=70466)

- **UNESCO (2021): Reimagining our futures together: A new social contract for education.**
    **[Fuente](https://unesdoc.unesco.org/ark:/48223/pf0000379381_spa)**

- **OCDE (2020): The Digital Transformation of Education: Connecting Schools and Communities.**
    [Fuente](https://www.oecd-events.org/smart-data-and-digital-technology-in-education/session/05a01636-3dfd-ec11-b47a-a04a5e7cf9da/the-digital-transformation-of-education-connecting-schools-empowering-learners)

- **Digital economy and society statistics - households and individuals**
  [Fuente](https://ec.europa.eu/eurostat/statistics-explained/index.php?title=Digital_economy_and_society_statistics_-_households_and_individuals)
  [Fuente](https://ec.europa.eu/eurostat/databrowser/view/isoc_ci_ac_i__custom_16380599/default/table?lang=en)

- **Otras fuentes:**
  Obtención del mapa de formas de España: [Mapa](https://github.com/FMullor/TopoJson/blob/master/Espa%C3%B1aAgrupada.json)



**¡Gracias por tu interés en este estudio sobre la brecha digital en España!**
