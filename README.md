# Visual Analytics

Esta página hace parte de un trabajo asignado en la materia Visual Analytics de la [Universidad de los Andes](www.uniandes.edu.co) para el semestre 2017_20.

## Programa Ciudadanía Digital

El Ministerio ha establecido como parte del Plan Vive Digital, una estrategia nacional de apropiación en TIC enfocada hacia el desarrollo de capacidades y competencias para el uso de TIC dirigida a estudiantes, profesionales, trabajadores de todos los sectores de la economía, y la comunidad en general. Para tal fin, se utilizan los estándares de la OCDE para diagnosticar y monitorear las habilidades TIC de la población, buscando ser más competitivos a nivel nacional y estar a la vanguardia en los estándares internacionales.

"Ciudadanía Digital" es una estrategia orientada al desarrollo de capacidades y competencias digitales en los usuarios que cuentan con un nivel básico, intermedio y avanzado de conocimientos en el uso de las TIC.

En "Ciudadanía Digital" las capacidades y competencias digitales se certifican una vez se comprueba el entendimiento y la apropiación de las mismas, mediante pruebas de análisis que permiten establecer el ortorgamiento por parte del Ministerio TIC de dicha certitifcación.

Para más iformación puede dirigirse a la página del programa [aquí](http://www.ciudadaniadigital.gov.co/627/w3-propertyvalue-12324.html)

# Análisis

Se propone presentar un análisis demográfico de los perfiles de personas que acceden a los diferentes cursos ofrecidos en el programa **Ciudadanía digital** a partir de datos adquiridos en la página de [Datos abiertos](https://www.datos.gov.co/) del gobierno colombiano.

## Datos (What)

El set de datos se puede encontrar [aquí](https://www.datos.gov.co/Ciencia-Tecnolog-a-e-Innovaci-n/Indicadores-A-o-2016-2017-Ciudadan-a-Digital/d2v8-vpdg). Cada fila tiene la información sobre una persona que toma un curso; sus datos demográficos y los datos de su participación.

- **Tipo:** Tabla
- **Items:** 12700
- **Atributos:**
    - Año (Ordinales, secuencial)
    - Meses(Ordinales, cíclico)
    - ID Kiosco VD (Ordinales, secuenciales)
    - Departamento (Categórico)
    - Municipio (Categórico)
    - Edad (Ordinales ordenados)
    - Grupo étnico (Categórico)
    - Nivel de estudios (Categórico)
    - Género (Categórico)
    - Estrato (Ordinal, secuencial)
    - Habita en sector (Categórico)
    - Ocupacion (Categórico)
    - Situación Particular (Categórico)
    - Nota Final Examen (Ordinal, secuencial)
    - Curso (Categórico)
    - Certificado    (Categórico)
    - Fecha Inscripción (Ordinales, secuencial)
    - Fecha Certificado (Ordinales, secuencial)

## Why

- Identificar el perfil de personas que más acceden a cursos en línea y que aprueban, basado en localización geográfica, edad, genero y ocupación.
- Comparar el desempeño de las personas de diferentes ocupaciones y niveles de estudio en los exámenes finales.
    
## How

Se propone utilizar un gráfico de barras agrupado. Vada grupo comprenderá un programa. Cada barra será un subgrupo del atibuto seleccionado, ya sea estrato, ocupación, nivel de edades etc.


