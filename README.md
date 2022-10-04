# ISIS 4822 Visual Analytics
## 2022-2
## Laboratorio 2 - D3 Data Binding


#### Contexto
Terridata es la fuente oficial de la información territorial dispuesta por el Departamento
Nacional de Planeación (DNP) que nace por recomendación de la OCDE y dispone
indicadores estandarizados de la información territorial del país (regiones, departamentos y
municipios). Los indicadores se encuentran agrupados por dimensiones y subcategorías y
son recopilados de fuentes oficiales e institucionales.
Una de las dimensiones incluidas en esta fuente de datos del país es la de Educación que
incluye las siguientes subcategorías e indicadores:

#### Acceso a la educación

- Cobertura bruta en educación - Total
- Cobertura bruta en educación básica
- Cobertura bruta en educación media
- Cobertura bruta en educación primaria
- Cobertura bruta en educación secundaria
- Cobertura bruta en transición
- Cobertura en educación superior
- Cobertura neta en educación - Total
- Cobertura neta en educación básica
- Cobertura neta en educación media
- Cobertura neta en educación primaria
- Cobertura neta en educación secundaria
- Cobertura neta en transición
- Tasa de tránsito inmediato a la educación superior

#### Acceso a la educación desagregado por sexo
 
- Cobertura neta en educación básica  - Hombres
- Cobertura neta en educación básica  - Mujeres
- Cobertura neta en educación total - Hombres
- Cobertura neta en educación total - Mujeres

#### Calidad

- Puntaje promedio Pruebas Saber 11 - Lectura crítica
- Puntaje promedio Pruebas Saber 11 - Matemáticas

#### Logro

- Años de educación personas de 15 y más años
- Porcentaje de asistencia de 5 a 24 años (Censo)
- Porcentaje de asistencia de 5 a 24 años Rural (Censo)
- Porcentaje de asistencia de 5 a 24 años Urbana (Censo)
- Tasa de Analfabetismo (Censo)
- Tasa de analfabetismo de personas de 15 y más años
- Tasa de Analfabetismo Rural (Censo)
- Tasa de Analfabetismo Urbana (Censo)
  
#### Permanencia y rezago

- Tasa de deserción intra-anual del sector oficial en educación básica y media (Desde transición hasta once)
- Tasa de repitencia del sector oficial en educación básica y media (Desde transición hasta once)
  
El Ministerio de Educación quiere utilizar estos datos para verificar la evolución de la calidad de la educación primaria y secundaria en el país en los últimos 12 años e identificar las regiones geográficas con mayor cobertura e incidencia de la educación en estos mismos periodos.
Utilice el archivo adjunto a este laboratorio TerriData_Dim4 y los geojson
MGN_ANM_MPIOS.geojson y MGN_ANM_DPTOS.geojson para el desarrollo de este
laboratorio. El archivo TerriData_Dim4 contiene los registros de los indicadores disponibles desde el año 2005 al 2020 para cada entidad territorial según los indicadores de la tabla 1.

Los archivos MGN_ANM_MPIOS y MGN_ANM_DPTOS contienen la división geográfica político administrativa DIVIPOLA  del país en formato geojson.
Para la realización de este laboratorio, usted debe:

1.	Identifique y caracterice las variables dentro de los dataset que son necesarios para su análisis. Caracterice en términos de Tamara (WHAT) las variables que ha de tratar en la construcción de su visualización de manera tal que las variables caracterizadas permitan abordar la tarea a plantear.
2.	Exprese en términos de Tamara (WHY) la tarea principal y las tareas secundarias a abordar para cumplir el objetivo y necesidad del Ministerio de Educación.
3.	Diseñe el HOW de su visualización y gráficas especificando los modismos a utilizar, las marcas y los canales de codificación. Incluya las interacciones y transiciones que le permitan al usuario cumplir las tareas que identificó en el punto anterior.
4.	Genere un wireframe y bocetos de interfaz, ubicación y proporción de las gráficas que compondrán su visualización o tablero.
5.	Diseñe, plantee y explique las transiciones y cambios de estado que tendrán sus marcas al aplicar los filtros o selecciones que considere pertinentes.
6.	Implemente las visualizaciones usando D3 en un ambiente nativo o en un observable utilizando los métodos enter, update & exit y/o el esquema join definiendo sobre estos estados los cambios que ha diseñado para las diferentes marcas que componen la realización de su laboratorio.

Puede preprocesar los datos en otras herramientas (Excel, pandas, MatLab, etc) antes de cargarlos al ambiente web desde el que los vaya a visualizar. En cualquier caso, sea explícito con las transformaciones y limpiezas realizadas.

#### Referencia

Las siguientes referencias le pueden ser útiles para la realización de este laboratorio:

- Scott Murray. Interactive Data Visualization for the web. O’Reilly Media, Inc, 2013.
- Bostock, Mike. Learn D3: Introduction. Disponible en: https://observablehq.com/@d3/learn-d3
- Departamento Nacional de Planeación de Colombia. Terridata. Disponible en: https://terridata.dnp.gov.co/
- Glosario Ministerio de educación Nacional. https://www.mineducacion.gov.co/1621/article-82702.html

#### Posibles visualizaciones y/o tareas

- Diferenciación por sexo de educación y cobertura bruta y neta del departamento 

- Rezago de cobertura bruta vs neta en ciudad/municipios

- Tasas de desercion en la educación y repitencia ciudad/municipios