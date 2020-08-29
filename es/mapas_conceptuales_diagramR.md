# Este es el código en Rmd para generar los mapas conceptuales usando el paquete DiagramR

# * Español

## Curso R desde Cero
## Clase 1

## Mapa conceptual - lección 1
### Ejemplos de uso del lenguaje R 
#### con el trabajo de todas científicas de datos de latinoamérica. 

{{< diagram >}}
graph LR;
A[Lenguaje R] -->|tiene| B[multiple usos];
B -->|No solo| C[estadística];
B --> D[Análisis de texto];
B --> E[Análisis de audio];
B --> F[Informes, tableros de control, presentaciones];
B --> G[Aplicaciones web];
B --> H[Internet de las cosas];
B --> I[Modelado];
B --> J[Teledetección y mapeo];

{{< /diagram >}}

## Mapa conceptual - lección 2
### RStudio IDE

{{< diagram >}}
graph LR;
A[Lenguaje R] -->|lo usamos a través de| B[RStudio IDE];
B -->|tiene| C[consola];
B -->|tiene| D[entorno/historia];
B -->|tiene| E[scripts];
B -->|tiene| F[paneles];
F --> G[archivos];
F --> H[gráficos];
F --> I[paquetes];
F --> J[ayuda];
F --> K[visor];
F --> L[tutorial];

{{< /diagram >}}

## Mapa conceptual - lección 3
### R base, pquetes, funciones, argumentos, variables

{{< diagram >}}
graph LR;
A[Lenguaje R] -->|formado por| B[R base];
A -->|formado por| C[Paquetes];
C -->|tiene| D[funciones];
B -->|tiene| D;
D -->|puede tener| E[argumentos];
A -->|trabaja con| F[estructura de datos];
F -->|una son| G[las variables];

{{< /diagram >}}


## Mapa conceptual - lección 4
### Mensajes, errores y warnings (advertencias)

{{< diagram >}}

graph LR;

A[Consola] -->|ejecuta| B[código de R];
B -->|puede devolver| C[un mensaje];
B -->|puede devolver| D[una advertencia-warnings];
B -->|puede devolver| E[un error];
C -->|está todo bien| F[informativo. Código ejecutado];
D -->|algo pasó| G[informativo. Código ejecutado];
E -->|algo salió mal| H[código no ejecutado];

{{< /diagram >}}


## Mapa conceptual - lección 5
### Cómo obtener ayuda

{{< diagram >}}

graph LR;

A[Ayuda] -->|como preguntar| B[de manera eficiente];
A -->|usar la documentación en| C[el panel de ayuda de RStudio];
A -->|buscar en| D[Google];
A -->|consultar| E[Cheat Sheet];
A -->|consultar| F[CRAN Task Views];
A -->|buscar/preguntar| G[Comunidad R-Studio];
A -->|buscar/preguntar| H[StackOverflow];
A -->|buscar/preguntar| I[Twitter];
A -->|preguntar/unirte| J[Comunidad R];
B -->|usar| K[sessionInfo];
B -->|usar| L[dput];

{{< /diagram >}}

## Mapa conceptual - lección 6
### Comunidad R: R-Ladies

{{< diagram >}}

graph LR;

A[Comunidad R] -->|tiene| B[Usuarios de Grupos de R];
C[R-Ladies] -->|es un tipo de| B;
C -->|tiene| D[Capítulos];
D -->|uno de ellos es| E[R-Ladies Santa Rosa];
A -->|está creciendo mucho| F[en América Latina] ;
F -->|organizamos| G[LatinR];
F -->|traducimos| H[R4DS];
F -->|traducimos| J[Guías rápidas de RStudio];
F -->|llevamos adelante| I[DatosDeMiercoles];
F -->|llevamos adelante| K[Paquetes Datos/Dados];

{{< /diagram >}}

## Clase 2

## Mapa Conceptual - Lección 1
### Estructuras de datos. 


{{< diagram >}}

graph LR;

B[estructura de datos] -->|un solo dato| C[variable]; 
B -->|multiples datos| D[vector]; 
B -->|vector multidimensional| E[matríz];
C -->|del mismo tipo| F[vector atómico];
D -->|varios del mismo largo| G[data.frame];

{{< /diagram >}}

## Mapa Conceptual - Lección 2
### Estructuras de Datos

{{< diagram >}}

graph LR;

A[tibble] -->|un tipo de| B[data.frame];
A -->|tiene| C[columnas];
A -->|tiene| D[filas];
C -->|debe tener el mismo| E[tipo de dato];
E -->|cuantitativo| F[doble/double, entero/integer];
E -->|cualitativo| G[lógico/logical, caracter/character];

{{< /diagram >}}

## Mapa Conceptual - Lección 3
### Como ver la estructura de los datos

{{< diagram >}}

graph LR;

A[función] -->|muestra| B[la estructura de los datos];
A -->|muestra| B;
B --> C[view];
A -->|muestra| B;
B -->D[glimpse];
A -->|muestra| B;
B -->E[kable];

{{< /diagram >}}

# * English

## First Class
## Concept Map - Lesson 1
### R Languaje, examples of use. 
#### with the work of all latin american data scientists women.

{{< diagram >}}
graph LR;
A[R Languaje] -->|Has| B[Multiple uses];
B -->|Not only| C[Statistics];
B --> D[Text analysis];
B --> E[Audio analysis];
B --> F[Reporting, Dash boards, presentations];
B --> G[Web apps];
B --> H[Internet of Thing];
B --> I[Modeling];
B --> J[Remote Sensing, mapping];

{{< /diagram >}}

## Concept Map - Lesson 2
### RStudio IDE

{{< diagram >}}
graph LR;
A[R Languaje] -->|we use it through| B[RStudio IDE];
B -->|has| C[console];
B -->|has| D[enviroment/history];
B -->|has| E[scripts];
B -->|has| F[panels];
F --> G[files];
F --> H[plots];
F --> I[packages];
F --> J[help];
F --> K[viewer];

{{< /diagram >}}

## Concept Map - Lesson 3
### R base, packages, function, parameters, variables

{{< diagram >}}
graph LR;
A[R Languaje] -->|formed by| B[R base];
A -->|formed by| C[Packages];
C -->|has| D[Functions];
B -->|has| D;
D -->|can have| E[parameters];
A -->|work with| F[data estructures];
F -->|one is| G[variables] ;

{{< /diagram >}}


## Concept Map - Lesson 4
### Messages, errors, warnings

{{< diagram >}}
graph LR;
A[Console] -->|executed| B[R code];
B -->|can give| C[mensages];
B -->|can give| D[warnings];
B -->|can give| E[errors];
C -->|all ok| F[informative/code executed];
D -->|something happened| G[informative/code executed];
E -->|something went wrong| H[code not executed];

{{< /diagram >}}


## Concept Map - Lesson 5
### How to get help

{{< diagram >}}
graph LR;
A[Help] -->|how to ask| B[efficiently];
A -->|use R documentation in| C[RStudio help panel];
A -->|search in| D[Google];
A -->|consult| E[Cheat Sheet];
A -->|consult| F[CRAN Task Views];
A -->|search/ask| G[R-Studio Community];
A -->|search/ask| H[StackOverflow];
A -->|search/ask| I[Twitter];
A -->|ask/join| J[R Community];
B -->|using| K[sessionInfo];
B -->|using| L[dput];
{{< /diagram >}}

## Concept Map - Lesson 6
### R Community: R-Ladies

{{< diagram >}}
graph LR;
A[R Community] -->|has| B[R User Groups];
C[R-Ladies] -->|are a type of| B;
C -->|has| D[Chapters];
D -->|one of them| E[R-Ladies Santa Rosa];
A -->|grow in| F[LatAm] ;
F -->|organize| G[LatinR];
F -->|translate| H[R4DS]
F -->|carry on| I[DatosDeMiercoles];
{{< /diagram >}}

## Second Class

## Concept Map - Lesson 1
### Data structures. 


{{< diagram >}}

graph LR;

B[data estructures] -->|a single data| C[variables]; 
B -->|multiple data| D[vector]; 
B -->|multidimentional vector| E[matrix];
C -->|same type| F[atomic vector];
D -->|same length| G[data.frame];

{{< /diagram >}}

## Concept Map - Lesson 2
### Data structures

{{< diagram >}}
graph LR;
A[tibble] -->|a type of| B[data.frame];
A -->|has| C[columns];
A -->|has| D[rows];
C -->|must be the same| E[type of data];
E -->|cuantitative| F[double, integer];
E -->|cualitative| G[logical, character];
{{< /diagram >}}

## Concept Map - Lesson 3
### Function to see data set structure

{{< diagram >}}
graph LR;
A[function] -->|show data structure| B[type name of data];
A -->|show data structure| C[view];
A -->|show data structure| D[glimpse];
A -->|show data structure| D[kable];
{{< /diagram >}}


