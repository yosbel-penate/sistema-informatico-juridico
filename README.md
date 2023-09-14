Cada miembro del equipo debe completar tareas que demuestren la implementación y el dominio de los objetivos de la asignatura. No se permiten clases implementadas por más de un miembro del equipo, y las clases relacionadas mediante herencia deben ser implementadas por el mismo programador. No se permiten exposiciones compartidas de dichas clases. El profesor evaluará la complejidad del proyecto realizado por el equipo y decidirá si alcanza el nivel suficiente para ser aceptado. El profesor revisará el diagrama UML del proyecto y la contribución de cada estudiante. El proyecto solo será aceptado si todos los diagramas UML de los miembros son aprobados por el profesor, los estudiantes deben tener sus diagramas UML listos antes de codificar y lo más rápido posible.

Los estudiantes deberán entregar de manera individual una documentación en la Wiki del repositorio que explique de manera detallada la implementación de su trabajo, incluyendo un diagrama de clases que muestre su parte del proyecto, así como una explicación de cada método y variable de cada clase, junto con una explicación de cada relación utilizada. En dicha documentacion se debe ver reflejado el cumplimiento de todos los objetivos de la asignatura(estos se encuentran al principio de cada conferencia) por parte del estudiante, así como la esplicación de como utilizar las interfaces gráficas del proceso que implementó. De faltar algun objetivo durante la primera exposición se enviará al estudiante a segunda vuelta. La presentacion del proyecto es de manera individual, por tanto todo estudiante debe tener conocimiento del negocio en general. La parte que implemente un programador debe cumplir un con un flujo completo de al menos una actividad, un CRUD completo. La aplicación debe ser de ventanas gráficas, con menús que utilicen elementos visuales de java. El profesor evaluará a cada miembro del equipo de acuerdo a la frecuencia, calidad y cantidad de pullrequest aceptados, con lo cual verificará que lo que el estudiante expone realmete lo implementó él, no se aceptará ningún códico que no fue previamente aceptado mediante un pullrequest. El proyecto que será aceptado será aquel que está registrado en este repositorio y no se aceptará otra version fuera de este.

Para la realización del diagrama UML se utilizará la extension de Vscode: PlantUML v2.17.5, el lenguaje de desarrollo será java 17.0.5 y el IDE de desarrollo Vscode v 1.81.1 con las extensiones:

Project Manager for Java v0.23.1

Debugger for Java v0.54.0

Language Support for Java(TM) by Red Hat v1.13.0

Se instalará el java:

java 17.0.5 2022-10-18 LTS

Java(TM) SE Runtime Environment (build 17.0.5+9-LTS-191)

Java HotSpot(TM) 64-Bit Server VM (build 17.0.5+9-LTS-191, mixed mode, sharing)

# sistema-informatico-juridico
Es un sistema informático jurídico que tiene por  objeto asistir a los operadores de la justicia –jueces, fiscales y defensores- del fuero  penal en el proceso de individualización de la pena.

Sistema Informático Jurídico para la Individualización y Acuerdos sobre la Pena 

Legal Advisor, en adelante LEAD, es un sistema informático jurídico que tiene por 
objeto asistir a los operadores de la justicia –jueces, fiscales y defensores- del fuero 
penal en el proceso de individualización de la pena. 
A partir de las circunstancias objetivas y subjetivas consideradas relevantes 
dentro de un caso, LEAD produce una recomendación de la pena, que puede tomarse 
como base para lograr un acuerdo previo entre las partes. Adicionalmente, LEAD 
provee explicaciones basadas en la jurisprudencia que pueden ser utilizados por los 
jueces como parte de la fundamentación de la pena. 
LEAD ha sido implementado para actuar sobre tres delitos diferentes. Sin 
embargo, la generalidad del modelo propuesto permite fácilmente ser extendido a otras 
figuras penales, así como también alterar o utilizar un nuevo conjunto de circunstancias 
objetivas y subjetivas para la individualización de la pena. 
El sistema fue evaluado con casos reales, logrando predecir con efectividad las 
decisiones de un tribunal. LEAD demuestra que es viable utilizar sistemas de 
información legales para contribuir a lograr que el proceso de graduación de pena pueda 
ser más predecible, consistente y fundado en base a las pautas de valoración que fija el 
Código Penal

Motivación 
La determinación de la pena puede ser definida como el acto mediante el cual el 
juez fija las consecuencias de un delito. Se trata de un acto complejo en el cual, 
según las disposiciones legales, se debe dar cumplimiento a las diferentes 
funciones de la reacción penal estatal frente a la comisión de un hecho punible. 
Los procedimientos de decisión destinados a la determinación de la pena 
suelen ser demasiado amplios y difíciles de conciliar entre sí. Esto se relaciona 
con la necesidad de que la pena satisfaga intereses que no siempre se orientan en 
la misma dirección. Ello implica convertir a la determinación de la pena en un 
proceso en el que deben ser clasificados y ponderados distintos tipos de 
información acerca del hecho y del autor, a fin de lograr la respuesta más 
equilibrada posible frente al hecho del autor, en sistemas jurídicos que no admiten 
–al menos, no expresamente- que el castigo por sí solo, sea la respuesta adecuada 
como reacción frente al delito


Definición del sistema 
Esta actividad (ASI-1), especificada en la metodología METRICA Versión 3, 
tiene como objetivo efectuar una descripción del sistema, delimitando su alcance, 
estableciendo las interfaces con otros sistemas e identificando a los usuarios 
representativos. 
De común acuerdo con el cliente, se ha desarrollado una descripción 
general del problema a resolver y el motivo de usar el enfoque de sistemas 
informáticos jurídicos, siendo el producto resultante el Documento para la 
Descripción del Sistema, que además contiene los resultados de algunas 
actividades propias de la Gestión de Proyectos (GPI-1 y GPI-2) presentados en el 
Anexo A del presente trabajo. 

Objetivos del Proyecto 
_______________________________________________________________________________ 

 Finalidad: Introducir la tecnología de sistemas informáticos jurídicos 
para asistir a los operadores de la justicia penal –jueces, fiscales y 
defensores- en el proceso de individualización y acuerdos sobre la 
pena. El sistema informático jurídico intenta que proceso de 
graduación de pena pueda ser más predecible, consistente y fundado en 
base a las pautas de valoración que fija el Código Penal. 

 Fines: Se pretende que los fiscales y defensores cuenten con 
información relevante acerca de la pena, sobre los casos que trabajen, 
que les permita lograr acuerdos, así como también servir a los jueces 
en la determinación de la pena y su fundamentación. 
 Metas: 
a) Lograr que el sistema informático jurídico pueda realizar una 
predicción acerca de la pena asociada a un caso particular, 
ajustando su recomendación a un conjunto de valores -pena 
mínima, un tercio, dos tercios y pena máxima- para acotar la 
decisión de la pena a intervalo más reducido. Esto permitirá a 
los operadores de la justicia penal contar con una herramienta 
útil para poder reducir el marco de discrecionalidad que existe 
en la actualidad, para los delitos tratados. 
b) Poder obtener información asociada a la recomendación, que 
sirva como base para la fundamentación de la decisión que 
produzcan los jueces. La justificación de la recomendación 
producida, estará integrada por la jurisprudencia asociada al 
caso en cuestión. El uso de jurisprudencia producida en el 
ámbito local tiene un beneficio adicional, ya permite que los 
jueces tengan presente argumentaciones propias que produjeron 
en casos anteriores. De este modo, las justificaciones provistas 
por el sistema pueden ayudar a los jueces a mantener la 
consistencia en sus decisiones. 

Problema Principal 
El problema principal consiste en poder ponderar los factores agravantes y 
atenuantes para un determinado caso, y emitir una recomendación 
consistente en una predicción de la pena y una fundamentación compuesta 
por toda aquella jurisprudencia que contemple los factores especificados. 

División en Subproblemas 
De la descripción del problema principal, se desprenden los siguientes 
subproblemas: 
 Análisis de los factores objetivos y subjetivos para la individualización 
de la pena. Se requiere conocer cuáles son los factores objetivos y 
subjetivos que conformarán el núcleo de parámetros que utilizará el 
sistema para producir una recomendación. 
 Ponderación de los factores objetivos y subjetivos. Para cada delito que 
sea tratado se debe contar con una valoración diferente, que permita 
dotar de precisión a la recomendación del sistema. 
 Análisis de los valores lingüísticos de cada uno de los factores 
objetivos y subjetivos. Se necesita reducir el conjunto de valores 
posibles que puede tomar cada factor a un conjunto manejable, para 
poder generar la explicación de la recomendación en base a la 
jurisprudencia.

Datos 
Los datos necesarios para resolver el problema son la determinación de la 
figura delictiva de un caso, y la especificación de los factores agravantes y 
atenuantes, junto con sus valores lingüísticos asociados. 
La precisión en las predicciones del sistema será mejorada basándose en la 
incorporación de casos históricos en los cuales se conozca el resultado de 
la sentencia. 
La jurisprudencia local, que conforma la base de argumentaciones del 
sistema, se incorporará a través del sistema o mediante un procesador de 
textos independiente. 

Casos de Prueba 
Los casos de prueba se tomarán de los protocolos de sentencias de las 
Cámaras Criminales de la provincia del Neuquén, dado que es de interés 

del usuario poder verificar el comportamiento del sistema con casos 
locales. 
F) Recursos 
a) Humanos. Se dispone un especialista, quien será el encargado de 
especificar los factores objetivos y subjetivos para la individualización 
de la pena y la determinación de los valores lingüísticos de cada uno de 
ellos. La ponderación de los factores se obtendrá de la evaluación 
realizada por un grupo de especialistas -jueces, fiscales y defensoresen materia penal. Para la etapa final de validación, se podrá utilizar un 
conjunto de casos de prueba obtenido de los protocolos de sentencia de 
las Cámaras Criminales de la provincia del Neuquén. 
b) Materiales. Los recursos que se utilizarán para el desarrollo del sistema 
son: 
 Hardware: Una PC. 
 Software: Como sistema operativo, se utilizará Windows y para el 
desarrollo, una herramienta de desarrollo de sistemas que funcione 
bajo Windows, debiendo ser integrable con un procesador de 
textos. Esta herramienta se elegirá más adelante. 

Alcance 
 El sistema dará como resultado una recomendación para la 
determinación de la pena de un caso particular. Las funciones que 
realizará el sistema informático jurídico son las siguientes: 
a) Recibir los datos de los factores atenuantes y agravantes, con sus 
correspondientes valores lingüísticos, los que serán introducidos 
por el usuario. 
b) Interpretar esos datos, teniendo en cuenta las ponderaciones de los 
factores involucrados, de acuerdo a la figura delictiva del caso a 
resolver.

) Inferir una recomendación, consistente en una predicción de la 
pena y una fundamentación de la misma en base a la jurisprudencia 
asociada. 
d) Mostrar la recomendación al usuario.

Fundamentación de la pena 
Una de las dificultades dentro del área del razonamiento legal es la proliferación 
de términos y la forma en que diferentes términos son usados como sinónimos. 
Los conceptos “razonamiento analógico” y “razonamiento precedencial o basado 
en precedentes” son utilizados indistintamente. Sin embargo, existen diferencias 
notorias que es necesario aclarar antes de especificar el uso del razonamiento 
basado en precedentes para la justificación de la pena

La experiencia puede ser referida como el conjunto de todas las instancias 
–es decir, casos- que han ocurrido en el pasado y pueden formar la base para 
predecir la salida de un nuevo caso. Se entiende por precedente a una decisión 
legal realizada en un caso previo. Los precedentes son un subconjunto de casos, 
los cuales son un subconjunto de la experiencia. En base a lo establecido, el 
término “razonamiento precedencial o basado en precedentes” indica una forma 
de razonamiento legal explícita, donde el resultado de un caso es determinado por 
el precedente. 
Levi estableció que el proceso de razonamiento basado en precedentes 
involucra tres pasos: establecer la similaridad entre algún caso previo y el caso 
concreto, localizar la regla asociada al primero y aplicarla al segundo caso. Esto 
transforma al razonamiento precedencial en un proceso estático determinado por: 
matching o ligadura de patrones similares y clasificación, formación de reglas en 
base a esta clasificación y aplicación deductiva de las mismas [Levi, 1949]. 
Respecto a la similaridad, es importante reconocer que un juez puede 
encontrar irrelevante la existencia o ausencia de un factor, el cual podría ser 
relevante para otros jueces. La clasificación de los factores en base a atenuantes y 
agravantes es una cuestión fundamental, pero debe tenerse en cuenta que la 
clasificación de los factores puede variar con el tiempo, pudiendo ocurrir que 
algún factor que fue considerado como atenuante pase a ser agravante y viceversa. 
Levi y otros han demostrado que las categorizaciones de los factores en una 
estructura estática han fallado al no tener en cuenta los cambios en la clasificación 
de los mismos.

Golding, ha propuesto varios modelos de razonamiento precedencial, y ha 
establecido que el mismo no es un simple proceso deductivo. Es sabido que la 
deducción es un proceso descriptivo inadecuado para el razonamiento legal. A 
diferencia de la deducción, esta forma de razonamiento no es formalmente sana –
en inglés, sound- (ya que una teoría formal sana, sólo permite probar hipótesis 
verdaderas), lo cual libera al mismo de algunos problemas que se presentan en el 
razonamiento legal. Golding no solo utiliza clasificación de similaridades y 


diferencias, sino que también incorpora a la misma la relevancia de cada factor 
[Golding, 1984]. 
Es posible interpretar el razonamiento precedencial como la inducción y 
aplicación de reglas. Desde este punto de vista, no se realiza ningún razonamiento 
analógico, ya que una vez que la generalización ha sido hecha y la regla ha sido 
generada, la deducción hace el resto del trabajo. 
La analogía, como “generalización y deducción” falla al no tener en cuenta 
la dinámica del proceso, que ocurre cuando hay cambios en las interpretaciones de 
los factores. Por otra parte, el razonamiento analógico involucra la transferencia 
de información entre dominios diferentes. 
Golding sugiere que el razonamiento analógico es una clasificación de 
instancias sin generalización. Este punto de vista, captura la flexibilidad del 
razonamiento precedencial, que no requiere contar con un número de casos para 
poder ser utilizado, ya que no realiza una generalización. 
Otra crítica al razonamiento precedencial es que la clasificación de los 
casos en base a factores o hechos materiales caracterizados superficialmente y las 
conclusiones realizadas, es una descripción inadecuada del ratio decidendi (razón 
de la decisión) de un caso y por lo tanto, una vista inadecuada del proceso de 
utilizar precedentes. 
En síntesis, existen tres críticas principales a tener en cuenta al utilizar 
razonamiento basado en precedentes: la dinámica de los factores expuesta por 
Levi, la perspectiva no-deductiva de analogía propuesta por Golding y la 
descripción inadecuada de un caso a través de sus precedentes. Para cada una de 
ella, se han elaborado las siguientes respuestas: 
 Durante el diseño del sistema informático jurídico, se considerará la 
dinámica de los factores dejando sin especificar la direccionalidad de cada 
uno de los mismos. Esta flexibilidad en la estructura permite que en cada 
caso se pueda utilizar a un factor como agravante o atenuante, según el 
criterio evaluativo que se considere apropiado. 
 Teniendo en cuenta la sugerencia propuesta por Golding, el sistema 
informático jurídico se aproximará al razonamiento analógico al no utilizar

el mecanismo de generalización, no necesitando contar con un gran 
número de casos para poder ser utilizado. Por otra parte, se considera al 
razonamiento precedencial únicamente a los fines de proveer una 
justificación de los casos. 
 El uso de circunstancias objetivas y subjetivas como representación de los 
factores de individualización de un caso, se ha sustentado en la explicación 
de Popple, quien construyó un sistema llamado Shyster para su doctorado. 
Popple indicó que los factores que representan las características 
importantes del dominio no necesitan ser derivados de un análisis 
doctrinal. Por otra parte, aclaró que un sistema informático jurídico 
predictivo podría llegar a utilizar atributos subjetivos como parte del 
proceso de decisión judicial

Adaptación a los cambios en los criterios de decisión 
Para poder crear un sistema informático jurídico adaptativo a los posibles cambios 
en la ponderación de los factores atenuantes y agravantes, así como también en la 
especificación de las circunstancias relevantes de cada caso, es necesario 
mantener un cuerpo de conocimientos capaz de auto-modificarse en función de los 
criterios valorativos aplicados en los casos y de las penas reales otorgadas. 
Para lograr este propósito, el sistema puede utilizar un mecanismo de 
aprendizaje por refuerzo que castigue a los factores que intervienen en un caso, ya 
sea con un aumento o una disminución de sus ponderaciones, cuando la 
recomendación de la pena no coincida con la pena real. 
En la conceptualización de casos, existe una clasificación a considerar: los 
casos relevantes -conocidos como “leading cases”-, y los casos comunes. Los 
primeros son aquellos que tienen un efecto profundo sobre las decisiones de todos 
los casos subsecuentes. El diseño del sistema tendrá en cuenta las variaciones en 
los criterios decisorios, utilizando intervalos de decisión dinámicos, que son 
ajustados en función de los resultados reales del caso para dotar de mayor 
precisión a las recomendaciones que provea el sistema. Si el criterio de decisión

humana mantiene consistencia, el mecanismo logrará agrupar a la mayoría de los 
casos de acuerdo a la pena que les haya sido otorgada.

Desarrollo de una entrevista estructurada 
A continuación se expone una entrevista estructurada que permite comprender el 
alcance que tendrá el sistema informático jurídico, así como también la 
adquisición del vocabulario jurídico adecuado para abordar el tema. 
Preparación de la sesión
Luego de haber profundizado en el material bibliográfico propuesto por el 
especialista, se han elaborado un conjunto de preguntas orientadas a obtener 
conocimiento específico sobre la individualización de la pena. La entrevista 
estructurada realizada, tiene como objetivo poder obtener un panorama general del 
proceso de individualización de la pena, así como también algunas definiciones de 
la terminología jurídica necesaria para el desarrollo del sistema. 
Sesión
Se ha realizado una entrevista en el despacho del especialista, explicándole 
los objetivos de la misma y el tiempo de duración estimado. A fin de minimizar 
los tiempos, se ha convenido en grabar la misma. 
Transcripción
Segunda Sesión 
Fecha: 15/02/2001 
Duración: 1 hora 
Soporte: Cinta 
Especialista (E): Dr. Ricardo Mendaña 
Lugar: Despacho del especialista 
Ing. de Software (IS): Lic. Sebastián Gómez 
Técnica: Entrevista Estructurada 
Objetivo: 
a) Obtener un panorama general del proceso de individualización 
de la pena.

b) Obtener definiciones de la terminología jurídica necesaria para 
el desarrollo del sistema. 
1. IS: Qué es un delito? 
E: “El delito… una primera definición con sentido vulgar podría ser: un hecho 
que viola la ley penal, una infracción a la ley penal. Una definición más 
técnica es: un hecho típicamente antijurídico y culpable. Típicamente quiere 
decir, que está previsto en un tipo penal, antijurídico que contradice el 
ordenamiento jurídico y culpable porque la ley exige además que no cualquier 
acto violatorio de la ley penal, sino solamente aquellos en los que el autor es 
además declarado culpable de acuerdo a ciertos parámetros que también 
define la ley penal.” 
2. IS: Cuáles son los principales delitos que suceden en el ámbito local? 
E: “Yo diría que hay delincuencia convencional, dentro de la delincuencia 
convencional hay dos grandes segmentos: por un lado, los atentados contra las 
personas, homicidios, lesiones, violaciones; y por otro lado, delitos 
patrimoniales: robos, hurtos, estafas. Y además de la delincuencia, o 
criminalidad convencional, está la criminalidad especial, por llamarla de 
alguna manera. Tenemos grandes delitos económicos, los delitos de 
corrupción administrativa, los delitos que se cometen desde la función pública, 
y algunos otros delitos que cometen grandes organizaciones delictivas o 
delitos complejos. Estos serían los dos grandes segmentos.” 
3. IS: Qué es la tipicidad? 

E: “La tipicidad es uno de los requisitos que debe cumplir una conducta para 
ser considerada delito. Y en qué consiste? Consiste en su adecuación a un tipo 
penal. Qué es el tipo penal? Es una fórmula prevista en una ley penal que 
describe una conducta en sus circunstancias de modo y en las calidades del 
sujeto. Por ejemplo, un tipo penal es del tipo del homicidio. En qué consiste?
El artículo 79 del Código Penal dice: al que matare a otra persona será 
reprimido con pena de tal a tal. El tipo penal es matar a otra persona. Matar a 
otra persona es privar de la vida. Privar de la vida tiene algunas significancias, 
por ejemplo, qué pasa con la muerte cerebral, con la muerte clínica, qué es una 

persona; una persona es una persona por nacer, una persona es una persona 
que ya nació… Es decir, cualquiera de estas expresiones en realidad tiene un 
significado jurídico.” 
4. IS: Qué son los protocolos de sentencia? Para que se usan?
E: “Son los registros de las decisiones de los jueces y son una especie de 
copia, se integra con las copias de las decisiones que van en original a los 
respectivos expedientes.” 
5. IS: Cómo se identifica un expediente en un protocolo de sentencia?
E: “Los sistemas varían, pero como mínimo deben contener una 
individualización del tribunal que dictó la resolución, la identificación de las 
actuaciones por número de expediente, y por lo general, la fecha en que se 
dictó la resolución. Estos suelen ser los tres elementos para que uno pueda 
ubicar la resolución de un tribunal. En lo cotidiano, para localizar un 
expediente basta conocer el número y el año.” 
6. IS: Qué significa la jurisprudencia?
E: “Se denomina de esta manera al conjunto de decisiones de los jueces a 
partir de un juicio o de un expediente según el caso. Si los juicios son orales, 
se trata de juicios, si se trata de procedimientos escritos, simplemente una 
decisión que se introduce o se registra en un expediente.” 
7. IS: Cómo se pueden clasificar las penas en cuanto a su modalidad y a su 
duración?
E: “El Código Penal define una primera división de acuerdo a su naturaleza y 
penas de naturaleza pecuniaria como es la pena de multa, otras penas como es 
la inhabilitación y también las penas privativas de su libertad. Dentro de las 
penas privativas de su libertad, hay dos modalidades que es la prisión de 
reclusión, aunque en la práctica se ejecutan de la misma manera; no hay 
diferencias en su ejecución concreta sino mas bien en el momento a partir del 
cual se puede pedir la libertad condicional. A su vez, dentro del sistema del 
Código, hay penas que son, como el caso de la prisión perpetua o reclusión 
perpetua, que son indivisibles, y hay otras penas que se pueden dividir, porque


la ley establece un tope entre el mínimo y el máximo. En esta es donde se nota 
más el ámbito de discrecionalidad del Juez para individualizar la pena.” 
8. IS: Qué significa la individualización de la pena? 
E: “Es cumplir un poco el mandato de la ley, que establece una pena en 
abstracto; llevarla a una situación concreta, reconociendo como límites el 
mínimo y el máximo previsto en la ley penal.” 
9. IS: Considera que los artículos 40 y 41 del Código Penal, proveen un marco 
preciso para la determinación de la pena? Por qué?
E: “No aportan un marco preciso, porque hay expresiones que son muy 
ambiguas; porque además, el Código tiene casi noventa años, y porque en 
aquella época, el tema de la individualización de la pena por ahí no se 
consideró con la misma importancia que hoy se le asigna. Es una fórmula, 
digamos, que tiene algunos defectos técnicos, pero de cualquier forma es un 
marco de referencia sobre el cual se puede trabajar, si los tribunales se toman 
la cuestión de la individualización de la pena en serio.” 
10. IS: Qué significan circunstancias atenuantes y agravantes?
E: “Justamente, en estas penas que tienen un mínimo y un máximo, los jueces 
tienen que individualizar en concreto la pena que corresponde aplicar. Es 
decir, hay una primera individualización que es la ley, que establece un 
parámetro, pero la forma en que se concreta esto es a través de la sentencia. 
Para esto tienen que contar, computar o considerar el juez, aspectos que 
aumentan el disvalor de la conducta o reducen el disvalor de la conducta. Esta 
es una cuestión que depende de los tiempos, depende de las épocas, depende 
de los lugares… Es decir, durante mucho tiempo, por ejemplo, la ebriedad, la 
calidad de ebriedad crónica era un agravante, porque se consideraba la 
ebriedad como un vicio. Sin embargo, hoy que la ebriedad se considera como
una enfermedad, por lo general uno va a encontrar que muchas veces se 
considera la ebriedad como un atenuante, porque hay un menor disvalor en la 
conducta porque uno explica que llegó al delito como consecuencia de esta 
enfermedad.”

11. IS: Cómo pueden ponderarse los factores atenuantes y agravantes de manera 
que se pueda arribar a una determinación sobre la pena?
E: “Tampoco hay… La ley, por lo menos no establece fórmulas, pero lo cierto 
es que cuando concurren circunstancias atenuantes y agravantes, puede ocurrir 
que las atenuantes, de alguna forma neutralicen algunos de los agravantes, 
pero también puede ocurrir que la suma o la acumulación de mas de una 
agravante, en realidad potencie el criterio o la vara con la cual se va a medir la 
conducta del imputado.” 
12. IS: Por qué es necesario considerar las circunstancias objetivas y las subjetivas 
para la individualización de la pena? 
E: “Porque para el derecho penal importan los dos aspectos. Todas las 
conductas que son de alguna forma consideradas por la ley penal, tienen una 
objetividad. Es decir, significan una mutación en el mundo exterior. El robo 
implica el traslado, o el desapoderamiento de una cosa, con lo cual alguien 
deja de tenerla, otra persona la ejerce esa tenencia, pero además de eso exige 
por lo menos un elemento subjetivo. No alcanza con llevar una cosa de un 
lado a otro, sino requiere, por lo menos el conocimiento de que esa cosa no es 
propia. Si yo me llevo algo que en realidad creo que es mío, en realidad tengo 
objetivamente la conducta prohibida, pero subjetiva no la tengo satisfecha. 
Esta es una, por ejemplo, una idea. El delito es objetividad, pero también es 
dolo.” 
13. IS: Cómo puede dividirse el intervalo de la pena para acotar la decisión?
E: “Hay algunas escalas penales, que entre el mínimo y el máximo, establecen 
una brecha muy grande y realmente lleva en muchos casos a decisiones que 
exceden lo discrecional para transformarse en decisiones que son arbitrarias. 
Entonces, sería interesante que hubiera una división de esta franja para 
permitir que estas decisiones sean mas previsibles.” 
14. IS: Cuál podría ser la división, en intervalos? Cómo podría hacerse?
E: “Esto siempre es difícil, especialmente porque hay escalas penales que 
permitirían quizás muchos, varios rangos, y hay otras donde los rangos serían

demasiado estrechos, pero creo que se podría comenzar por una división, por 
lo menos en cuatro grandes segmentos.” 
15. IS: Cómo podrían establecerse ciertos conceptos o características relevantes 
que permitan al leer una sentencia poder conocer los motivos que 
fundamentan la pena?
E: “Bueno, en esto hay que reconocer que por lo general no hay un método de 
lo mas claro, o por lo menos que no pueda merecer algunas críticas en este 
tema, porque el tema de la individualización de la pena es una de las 
cuestiones olvidadas, o asignaturas pendientes que hay en este tema. Entonces, 
lo ideal sería que surjan con claridad todos los elementos objetivos o 
subjetivos, o de otra naturaleza, pero no siempre es fácil encontrarlas en todas 
las decisiones judiciales.” 
16. IS: Cómo puede justificarse o fundamentarse la decisión sobre la pena?
E: “La decisión, en primer lugar, se debe fundamentar o apoyar en aspectos 
concretos de cada caso. Cuando uno dice aspectos concretos, me refiero a 
condiciones objetivas, pero también a calidades personales del imputado. En 
esta tarea, suele ser un auxilio interesante los criterios que se hayan recogido 
en otros precedentes judiciales, o la opinión de la doctrina.” 
Análisis de la sesión
En base la información obtenida, se ve reflejada la necesidad de cuantificar 
los factores atenuantes y agravantes y poder contar con un método que permita 
arribar a una recomendación de la pena para un determinado caso. 
El especialista manifestó: “…cuando concurren circunstancias atenuantes 
y agravantes, puede ocurrir que las atenuantes, de alguna forma neutralicen 
algunos de los agravantes, pero también puede ocurrir que la suma o la 
acumulación de más de una agravante, en realidad potencie el criterio o la vara 
con la cual se va a medir la conducta del imputado.” Esto conlleva a plantear un 
mecanismo para la realizar una estimación, en el cual intervengan las 
circunstancias atenuantes y agravantes. 
Por otro lado, el intervalo de la pena debe acotarse para poder reducir el 
margen de discrecionalidad en la determinación de la misma. Durante la

Análisis estructural de textos jurídicos 
El estudio de la documentación escrita, permite obtener parte de los 
conocimientos relevantes en la construcción del sistema. Dentro de la 
documentación, son especialmente interesantes los libros de texto introductorios o 
manuales de formación que definan los términos básicos usados en el dominio. 
En las reuniones previas al inicio del proyecto, se le consultó al 
especialista sobre la bibliografía sugerida para profundizar en el tema de la 
individualización de la pena. La recomendación dada fue la siguiente: 
 Código Penal argentino. 
 “Lineamientos de la Determinación de la Pena”, de Patricia S. Ziffer, 
Primera edición, Konrad-Adenauer Stifung, 1996. 
 “El deber de fundamentación de las decisiones judiciales y la 
determinación de la pena”, de Patricia S. Ziffer, Contribuciones 3/1996, 
Konrad-Adenauer Stifung, 1996. 
Los resultados del estudio de la documentación citada han sido detallados 
en el capítulo II. Además de este material, fueron utilizadas otras fuentes de 
conocimientos, como protocolos de sentencias proporcionados por el especialista, 
y códigos penales con jurisprudencia, que ayudaron a comprender la estructura de 
las sentencias y a visualizar los conceptos que se consideran atenuantes o 
agravantes para la determinación de la pena. 
El especialista propuso un conjunto de conceptos que conforman las 
características más relevantes de los casos delictivos. A partir de ellos, se realizó 
un análisis estructural de textos sobre algunas sentencias condenatorias de uno de 
los delitos mas frecuentes que suceden en el ámbito local: los homicidios simples 
(incluyendo tentativas de homicidio). Se analizaron casos comprendidos entre el 
año 1999 y el primer semestre del año 2000. 
Aplicación de la técnica
Se documentó el análisis de textos en una matriz de cinco filas y dos 
columnas, con el siguiente formato:

Preparación de la sesión
La entrevista estructurada realizada, tiene por objeto poder validar los 
resultados obtenidos. Se han elaborado una serie de preguntas a fin de corroborar 
el modelo mental del especialista. 
Sesión
Se ha realizado una entrevista en el despacho del especialista, explicándole 
los objetivos de la misma y el tiempo de duración estimado de la sesión. Se 
introduce al especialista en el tema a tratar mediante una breve síntesis de la 
técnica que se ha utilizado para clasificar a los elementos. 
Transcripción
Segunda Sesión 
Fecha: 16/02/2001 
Duración: 1 hora 
Soporte: Papel 
Especialista (E): Dr. Ricardo Mendaña 
Lugar: Despacho del especialista 
Ing. de Software (IS): Lic. Sebastián Gómez 
Técnica: Entrevista Estructurada 
Objetivo: 
a) Corroborar los resultados obtenidos. 
1. IS: Cómo podrían compararse los delitos de acuerdo a sus características en 
común?
E: “Existen diferentes comparaciones entre los delitos pueden segmentarse 
aplicando diferentes criterios…de acuerdo al bien jurídico afectado, de 
acuerdo a la gravedad de los mismos, de acuerdo a la escala penal. En este 
último caso, pueden agruparse delitos que afecten a diferentes bienes 
jurídicos, por ejemplo, el caso del robo simple y las lesiones graves. Estos 
delitos tienen escalas parecidas pero bienes jurídicos distintos, pero además 
existen otras características como la violencia en las personas y otros factores 
comunes a ambos, por ejemplo…el impacto emocional que puede sufrir una 
persona en un robo es comparable al de las lesiones. Los robos con

intimidación o fuerza en las personas, en muchos casos tienen puntos de 
contacto muy directo con las lesiones.” 
2. IS: Qué diferencias tiene el homicidio simple respecto del robo simple y las 
lesiones graves?
E: “El resultado previsto en el delito tiene un reconocimiento o una valoración 
tan fuerte en el sistema penal, que define una escala penal mucho mas alta y le 
resta valor a las otras circunstancias que si tienen incidencia en los otros dos 
delitos, por ejemplo, los daños físicos a la víctima.” 
3. IS: Cómo podrían asociarse las características del autor, del hecho y de la 
víctima, de acuerdo a la relevancia de sus componentes?
E: “El sistema penal, en los artículos 40 y 41, destina mucho mas a las 
condiciones que se vinculan con el hecho y el autor. La víctima es el sujeto 
pasivo en el delito. Si no interviene, su situación no es definitoria en las 
escalas penales. Si bien en los últimos cincuenta años esto se ha ido 
modificando, los operadores judiciales siguen poniendo el acento en el autor. 
El derecho penal ha tenido un desarrollo unidireccional, es decir, se le ha 
puesto mas el acento a la situación del autor que a la de la víctima. Al hecho se 
lo asume como la obra del autor. La victimología ha tratado de romper esto, 
intentando explicar que los hechos no se pueden entender si se prescinde de la 
víctima. Con esto quiero decir, que existe una fuerte vinculación entre las 
características del autor y la víctima, que deberían considerarse para la 
individualización de la pena.” 
4. IS: Qué puede decirse del grupo de características de la víctima, respecto 
de las del autor y las del hecho?
E: “Puede haber, a los efectos de la determinación de la pena, 
circunstancias de la víctima que puedan prescindirse, mientras que nunca 
puede prescindirse de las del hecho y las del autor.” 
Análisis de la sesión
Los resultados de la entrevista corroboran, en base a la ponderación de las 
características evaluadas, la asociación entre el agrupamiento de las características 
del autor y de la víctima respecto del grupo de características del hecho.

A pesar todavía no se tiene demasiado en cuenta durante la 
individualización de la pena a las características de la víctima, en los últimos 
tiempos la victimología ha enfatizado en la necesidad de tener presente estos 
aspectos para la comprensión del hecho. Esta situación ayuda a explicar las 
ponderaciones que el especialista ha otorgado al agrupamiento de características 
de la víctima, similar al del autor, poniendo de manifiesto que existe una 
vinculación entre ellos basada en la relevancia que ambos tienen para la 
individualización de la pena. Por otro lado, el especialista ha explicado que bajo 
los lineamientos del Código Penal, puede suceder que en algunos casos se 
prescinda de las características de la víctima. 
Asimismo, se ha puesto de manifiesto mediante la valoración de las 
características, la vinculación de los delitos de robo simple y lesiones graves, 
justificadas por el especialista por la similaridad de las escalas penales y la 
relevancia que cobran las características evaluadas pertenecientes a la víctima. 
Evaluación
Las preguntas formuladas fueron respondidas en forma satisfactoria. Los 
objetivos han sido cumplidos, ya que se ha corroborado la consistencia de los 
agrupamientos de características realizados, que serán considerados durante la 
conceptualización de conocimientos para la modelización del sistema

Conclusiones de la educción de requisitos 
Los resultados obtenidos durante el proceso de adquisición de requisitos son 
suficientes para poder documentar la etapa de análisis. Dado que la adquisición de 
requisitos se realiza en paralelo en todas las etapas del ciclo de vida del proyecto, 
se continuaron realizando encuentros informales con el especialista a fin de 
obtener información adicional y validar los resultados producidos, necesarios para 
el desarrollo del sistema.

Análisis de Requisitos

Análisis de sistemas de información 
Siguiendo con el proceso de Análisis del Sistema de Información (ASI) de la 
metodología METRICA Versión 3, se ha realizado una actividad del perteneciente 
al Análisis Orientado a Objetos, conocida como Análisis de Clases (ASI-5). 
Asimismo, se ha desarrollado una actividad propia del Análisis 
Estructurado para la construcción del sistema, la Elaboración del Modelo de 
Procesos (ASI-7). Posteriormente, tuvieron lugar las actividades de comprobación 
de los procesos y datos del sistema, especificadas dentro del Análisis de 
Consistencia y Especificación de Requisitos (ASI-9). 
El análisis consiste básicamente en el entendimiento del dominio del 
problema y de la terminología usada. Esta etapa permite al ingeniero de software 
formar un marco inicial o mapa mental del dominio de la aplicación. 
El análisis conlleva un proceso de estructuración de la información y se 
desarrolla en una doble etapa. La primera etapa se corresponde con una actividad 
de análisis y la segunda con un trabajo de síntesis.

Modelo de datos del sistema 
En lugar de realizar un Diagrama de Entidad-Relación para la identificación de las 
relaciones entre conceptos, se ha optado por utilizar como representación 
intermedia un Modelo de Clases de Análisis, o Diagrama de Clase. 
El Diagrama de Clase se realiza como parte de las actividades de Análisis 
de Clases (ASI-5) especificadas en METRICA Versión 3, ya que este tipo de 
representación es más apropiada si se desea dar al modelo un enfoque orientado a 
objetos, y ayuda a establecer una relación más directa para la transformación del 
modelo conceptual al modelo formal.

Para realizar el Diagrama de Clase, se utiliza el Lenguaje Unificado de 
Modelado (en inglés, UML), creado en 1996 por Booch, Jacobson y Rumbaugh, 
como sucesor de los métodos de análisis y diseño orientado a objetos. El 
Diagrama de Clase, además de ser de uso extendido, también está sujeto a la más 
amplia gama de conceptos de modelado. [Fowler, 1997] 
El diagrama de clase representado describe los tipos de objetos que hay en el 
sistema y las diversas clases de relaciones estáticas que existen entre ellos. (Ver 
Figura 5-1) En el mismo, se han utilizado tres tipos de relaciones: 
 Asociación: representa la relación entre instancias de clases. Cada 
asociación tiene dos papeles; cada papel es una dirección en la asociación. 
Un papel tiene también una multiplicidad, la cual es una indicación de la 
cantidad de objetos que participarán en la relación dada. En general, la 
multiplicidad indica los límites inferior y superior de los objetos 


participantes. En el diagrama de clase existe una asociación Expediente y 
Delitos. Las flechas especificadas en las relaciones indican la 
navegabilidad, que determina que existen responsabilidades de un solo 
lado. La clase Expediente tiene la responsabilidad de decir a qué delito 
corresponde el caso, así como también de establecer qué limites de penas 
utilizará para la estimación de la pena, en función del delito. 
 Composición: mediante esta relación –representada por un rombo negro-, 
el concepto parte puede pertenecer a un todo único. Por lo general, se 
espera que las partes vivan y mueran con el todo. Cualquier borrado del 
todo se extiende a las partes. En el diagrama de clase, cada Expediente 
perteneciente a alguna de las subcategorías de Delitos -Homicidio Simple, 
Lesiones Graves y Robo Simple- está compuesto por sus elementos 
Atenuantes y Agravantes. La asociación es unidireccional, ya que interesa 
conocer cuáles son los atenuantes y agravantes de un determinado caso, 
pero no a la inversa. La cardinalidad de los agravantes, representada por m, 
va de 0 a 35, siendo este último número la totalidad de circunstancias 
definidas por el especialista. La cardinalidad de los atenuantes, 
representada por n, va de 0 a 35, debiendo ser n + m menor o igual a 35. 
 Clasificación Simple: se refiere a la relación entre un elemento y su tipo. 
En este tipo de relación –representada por un triángulo-, un elemento 
pertenece a un solo tipo, que puede haber heredado de supertipos. En el 
diagrama de clase, se utiliza la clasificación simple entre el concepto 
Delitos y las subclases Homicidio Simple, Lesiones Graves y Robo 
Simple. De esta forma, un elemento sólo podrá pertenecer a uno de los 
subtipos definidos por los conceptos anteriores. De la misma manera, 
existe una clasificación simple entre el concepto Circunstancias y los 
subtipos Hecho, Autor, Víctima, Atenuantes y Agravantes

Identificación de las clases y subclases primarias del sistema 
El objeto de esta tarea ha sido identificar las clases, o subconjuntos funcionales 
del más alto nivel, así como la terminología clave. Para cada clase primaria del 
sistema -entendiendo por clase primaria a aquella que es esencial al dominio de la 
aplicación- se especifica su utilidad o función, sinónimos y acrónimos, los 
atributos que lo definen, sus valores y de dónde pueden derivarse los datos. 
Clase: Circunstancias. 
 Función: Especifica todas las circunstancias objetivas y subjetivas que 
pueden ser tenidas en cuenta para individualizar un caso. 
 Sinónimos/Acrónimos: Factores (Hecho, Autor, Víctima, Atenuantes y 
Agravantes son consideradas subclases de esta clase). 
 Atributos: Descripción, Ponderación del Homicidio Simple, Ponderación 
de Lesiones Graves, Ponderación de Robo Simple, Valor de la 
Circunstancia. 
 Derivado de: Conocimiento educido del especialista. 
Clase: Delitos. 
 Función: Permite mantener una clasificación de los casos que han sido 
tratados, dividiéndolos en Homicidios Simples, Lesiones Graves y Robos 
Simples. 
 Sinónimos/Acrónimos: Figuras Delictivas (Homicidio Simple, Lesiones 
Graves y Robo Simple son consideradas subclases de esta clase). 
 Atributos: Descripción de los Agravantes, Valores de los Agravantes, 
Descripción de los Atenuantes, Valores de los Atenuantes, Valor de la 
Pena Estimada, Resultado de la Pena Estimada, Pena Real, Justificación 
del Caso. 
 Derivado de: Conocimiento educido del especialista y valores generados 
por el sistema.

Clase: Expediente. 
 Función: Permite almacenar los datos concernientes al caso que está 
siendo estudiado, así como también la información necesaria para la 
individualización de la pena. 
 Sinónimos/Acrónimos: Caso. 
 Atributos: Número, Año, Delito, Caratula, Agravantes, Valores de los 
Agravantes, Atenuantes, Valores de los Atenuantes, Estimación, 
Fundamentación, Pena, Límite de Un Tercio de la Pena, Límite de Dos 
Tercios de la Pena, Límite de Un Tercio de la Pena para Homicidio 
Simple, Límite de Dos Tercios de la Pena para Homicidio Simple, Límite 
de Un Tercio de la Pena para Lesiones Graves, Límite de Dos Tercios de 
la Pena para Lesiones Graves, Límite de Un Tercio de la Pena para Robo 
Simple, Límite de Dos Tercios de la Pena para Robo Simple, Reglas de 
Estimación, Reglas de Justificación, Reglas de Aprendizaje, Tasa de 
Aprendizaje. 
 Derivado de: Valores indicados por el usuario y resultados generados por 
el sistema.

Descripción de las clases del sistema 
A partir de la clase Delitos, se realiza una clasificación de los casos de acuerdo a 
su tipificación como: Homicidios Simples, Lesiones Graves y Robos Simples. 
Estas subclases serán las encargadas de contener los expedientes que sean 
incorporados al sistema. Debido a que cada elemento que se incorpore a las 
subclases previstas registrará los valores de los atributos de acuerdo a lo que 
especifique el usuario y los resultados que genere el sistema, no es necesario 
proveer de un valor a los de los atributos para las clases Delitos, Homicidio 
Simple, Lesiones Graves y Robos Simples. 
La clase Circunstancias permite una clasificación de los factores que 
pueden ser tomados en cuenta para la individualización de la pena en tres 
categorías: Hecho, Autor y Víctima. No es necesario indicar el valor de los
atributos de los conceptos previos debido a que se han especificado para cada uno 
de los elementos que pertenecen a las subclases, durante la adquisición de 
requisitos. Asimismo, no se requiere definir los valores de las clases Atenuantes y 
Agravantes, ya que únicamente contendrán los elementos ya definidos para las 
subclases Hecho, Autor y Víctima.


