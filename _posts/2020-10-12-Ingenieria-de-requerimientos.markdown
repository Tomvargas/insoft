---
layout: default
title:  "La ingeniería de requerimientos"
date:   2020-10-12 10:56:33 -0500
author: Tomas Vargas
permalink: /posts/idr
---
<script src="https://kit.fontawesome.com/7316530f41.js" crossorigin="anonymous"></script>
<p>Publicado por: <a class="aa" href="https://github.com/tomvargas">Tomas Vargas</a></p>

<h1>LA INGENIERÍA DE REQUERIMIENTOS</h1>
<hr>
<p>La <strong>ingeniería de requerimientos</strong> se basa en la recolección de las funciones o parámetros que el sistema debe de cumplir además, se debe <strong>especificar</strong> los limites y restricciones que el proyecto tendrá, de esta manera se puede prevenir los errores para tomar las medidas necesarias.</p>
<p>Esto se logra gracias a que todo los requerimientos planteados incluyendo las <strong>restricciones</strong> o los <strong>limites</strong> son debidamente documentados y por este medio existen varias maneras de representar esta <strong>documentación</strong>, el lenguaje informal donde se detalla los requerimientos de manera muy fácil de entender, lenguaje semi formal donde se representa la documentación de manera entendible sin dejar a un lado detalles técnicos y por ultimo el lenguaje formal donde se detalla la documentación con exposiciones técnicas que talvez para un cliente sea difícil de entender.</p>
<hr>
<h2>Atajos</h2>

* <p> <a class="aa" href="#l1"> Documentos de la IDR</a></p>

* <p> <a class="aa" href="#l2"> Formas de escritura para la IDR</a  ></p>

<hr>

<img src="https://mk0wwwrtologicc4ia7m.kinstacdn.com/wp-content/uploads/2020/01/web-it-isometric.png" alt="Ingeniería de software - Rtologic">


<h2 id="l1">Documentos de la IDR</h2>
<hr>
<p>Existen muchas formas de determinar los requerimientos de un proyecto, sin embargo, es esencial saber filtrar por orden de importancia y de esta manera tener un buen mapa que permita ver el panorama de la situación inicial.</p>
<p>La ingeniería de requerimientos cuenta con una serie de herramientas o técnicas que permiten ir documentando los requisitos del sistema, estos requisitos según indica se pueden presentar de distintas formas</p>

<h3>Entrevistas</h3>
<p>Este método de recolección de información sirve en gran medida para recaudar algunos requisitos para el sistema, son prácticamente esenciales para cualquier desarrollo y se pueden identificar en tres fases:</p>

* <p> <strong>Prepración:</strong>  en este punto se estudia el dominio del problema, se selecciona el publico al que va orientado el software para determinar el objetivo y contenido de la entrevista y posteriormente la planificación de esta.</p>

* <p> <strong>Realización de la entrevista:</strong>  se da paso a la fase de apertura donde el entrevistador debe de presentarse al entrevistado e informar la razón de la entrevista, luego se procede a la entrevista en cuestión en la fase de desarrollo, por último, en la fase de terminación se debe recapitular sobre la entrevista para confirmar que no haya habido confusiones durante el desarrollo de la entrevista.</p>

* <p> <strong>Análisis:</strong>  en este punto es necesario la verificación de los datos, pasarlas a limpio y reorganizar la información para ser contrastada con las demás entrevistas tomadas.</p>

<h3>Brainstorming</h3>
<p>Esta técnica conocida también como lluvia de ideas se caracteriza por ser llevada a cabo en reuniones donde en grupo se presente el objetivo de generar ideas por medio de un ambiente libre de criticas y juicios, general mente estas sesiones de lluvia de ideas suelen ser llevadas a cabo por grupos de cuatro a diez participantes donde uno de ellos es el que esté a cargo es decir el jefe.</p>
<p>Aunque parezca una técnica de carácter libre esta tiene 4 fases las cuales son:</p>

* <p> <strong>Preparación:</strong> para esta fase se prepara la sala donde se hará la sesión y los participantes de esta serán el jefe del proyecto y generalmente pueden ser clientes, usuarios, ingenieros de requerimientos, desarrolladores y de ser necesario algún experto en cuanto el objetivo del sistema.</p>

* <p> <strong>Generación:</strong> el jefe debe abrir la sesión donde expondrá un enunciado general sobre el problema a tratar, de esta forma los participantes de la sesión empezaran a debatir y exponer sus propuestas, sin embargo, se debe tener en cuenta que existen reglas, por ejemplo, no se permiten críticas, las ideas más avanzadas se fomentan, se debe de proponer cuantas ideas surjan y alentar a los participantes a combinar o complementar ideas de otros.</p>

* <p> <strong>Consolidación:</strong> ahora de deben organizar y evaluar cada una de las ideas generadas en la fase de generación y se sugiere siempre tres pasos para la evaluación que son: la revisión de ideas, descartar ideas que son excesivamente avanzadas y priorizar ideas que restan.</p>

* <p> <strong>Documentación:</strong> luego de todos los procesos el jefe produce la documentación con el contenido de las ideas filtradas y los comentarios de cada una.</p>

<h3>Caso de uso</h3>
<p>Esta técnica es muy utilizada por cualquier profesional, ya que se puede especificar los requerimientos funcionales propuestos inicialmente. Los casos de uso son descripciones de la secuencia de interacciones entre el sistema y uno o mas actores en la que se considera sistema como una caja negra.</p>
<p>Presentan varias ventajas porque facilitan la elicitación de requerimientos y son muy fáciles de comprender por los clientes o usuarios, además de eso pueden servir de base a las pruebas del sistema y a la documentación para los usuarios.</p>


<h2 id="l2">Formas de escritura para la IDR</h2>
<hr>

<h3>Lenguajes informales</h3>

<h4>Lenguaje natural</h4>
<p>El leguaje natural es el más simple y debe poder entenderse por cualquier persona de cualquier ámbito ya sea en negocios, análisis, equipos de desarrollo, etc. El contenido de entendimiento común hce que esta manera de documentar requerimientos sea la más idonea, sin embargo, aunque este lenguaje este dotado de excelentes características, al escribir los requisitos es muy probable que se encuentren ambigüedades y variablidad estructural.</p>

<h4>Lenguaje natural estructurado</h4>
<p>Este enfoque depende de la definición de formas estándar o plantillas para expresar la especificación de requerimientos.</p>

<h4>Lenguajes de descripción de diseño</h4>
<p>En este leguaje predominan características abstractas que especifican los requerimeibtos a travéz de las definiciones de un modelo operacional del sistema.</p>

<h4>Notaciones graficas</h4>
<p>Para definir los requerimientos funcionales del sistema se utiliza un lenguaje gráfico, complementado con anotaciones de texto.</p>

<h4>Especificaciones matemáticas</h4>
<p>Son notaciones que se basan en conceptos matemáticos como el de las máquinas de estado finito o los conjuntos. Estas especificaciones no ambiguas reducen los argumentos sobre la funcionalidad del sistema entre el cliente y el contratista.</p>

<h3>Lenguajes semiformales</h3>

<h4>Lenguaje de Especificación</h4>
<p>Un lenguaje de especificación o lenguaje de descripción es un lenguaje formal o semiformal cuya función es construir modelos de los sistemas que se desea elaborar. A diferencia de los lenguajes de programación, que son lenguajes interpretables o traducibles por una computadora hacia una representación ejecutable.</p>
<p>Los lenguajes de especificación no son por lo general utilizados para implementar el sistema, sino para especificarlo, conceptualizarlo o incluso validarlo, aunque también suelen ser legibles para un programa de computadora, que puede asistir en el proceso de validación.</p>

<h3>Lenguajes Formales</h3>

<p>El lenguaje formal es un conjunto de signos lingüísticos de uso exclusivo en situaciones donde el lenguaje natural no es adecuado. En el ámbito de las ciencias formales, un lenguaje formal es un conjunto de cadenas de símbolos que pueden ser reguladas por leyes que son específicas para cada una de estas ciencias.</p>

<p>Así pues, es un lenguaje ad hoc, creado con un objetivo determinado y para funcionar bajo contextos muy específicos. Además, no se utiliza en forma masiva. Por el contrario, su uso es restringido a los conocedores tanto del objetivo del lenguaje como de su contexto particular.</p>
<p>Por ejemplo, en el lenguaje de programación, el fin es la comunicación entre humanos y computadoras o entre dispositivos computarizados. No es una comunicación entre humanos.</p>

<hr>
<h3>Fuentes</h3>

* <p>Plaza, J. (2015) <a class="aa" href="http://www.mtpinternational.com.mx/noticias/56-el-lenguaje-natural-en-la-especificacion-de-requisitos-de-calidad">Lenguaje natural.</a></p>

* <p>Ramírez, S. (2017) Ingenieria de requerimientos.</p>

<hr>
<h4>Sigueme en <a class="aa" href="https://github.com/tomvargas" target="_blank"><i class="fab fa-github"></i> Ghithub</a></h4>