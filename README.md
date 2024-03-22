# FNK0031_FreenoveHexapodV3
## Proyecto inconcluso en espera indefinida

Este proyecto consiste en la creación de una API en python para controlar-
un robot FNK0031 Hexapod V3 a través de arduino con un set de instrucciones
ingresadas directamente desde python.

Este proyecto trata de hacer un set de instrucciónes python que se ingresan-
directamente en la placa Mega or Mega 2560 del Hexapod para funcionar de-
forma nativa en la memoria del robot.

Es necesario instalar arduino-cli, la versión es libre de elegirse-
unicamente se debe de tomar en cuenta los pasos de referencia de los siguientes links:

https://www.tinkerassist.com/blog/compile-upload-arduino-code-from-the-command-line
https://www.tinkerassist.com/blog/compile-upload-arduino-code-with-python

Estos links sirven de referencia para convertir el codigo de python a codigo binario-
utilizable por arduino para su posterior subida a la placa del robot.


[LIBRERIAS](https://github.com/julie9630/FNK0031_FreenoveHexapodV3/tree/main/Librerias):

Las librerias utilizadas para el funcionamiento del robot vienen adjuntas en el repositorio de github, en total son 4 librerias en formato zip.

Códigos:

[Prueba_1](LINK) arduino sirve como manejador de casos enviados desde python para ejercer las acciones del hexapod.
[Prueba_2](LINK) es una prueba inconclusa de arduino donde se intentó hacer un ciclo para inicializar python a través de arduino de tal modo que arduino fuera quien iniciara toda la interacción.

[RobotSemanaTec](LINK) es un codigo de python que se encarga de crear las instrucciones que se van a mandar al robot-
en una lista con parámetros, y también se realizó la conexión con arduino a través de la libreria "pyserial"
[RobotSemanaTec2 funcional](LINK) es un código que se iba a encargar de convertir el codigo "RobotSemanaTec" en un set-
de instruccines binarias que pudieran ser interpretadas por arduino para su posterior subida a la placa del FNK0031 Hexapod.

[Documentación Robot Python.pdf](LINK) es la documentación de la funcionalidad de los modos del FNK0031 Hexapod donde se detallan las funciones de cada una de las funcionalidades implementadas en python con sus ID's de llamada en la Lista de acciones encontrada en python (NOTA: la lista se llama "USER_INPUT" en python) seguida con una breve descripción de lo que hace cada función, después se encuentra la lista de parámetros de cada función para su correcto funcionamiento (NOTA: en la Lista "USER_INPUT" es necesario que en caso de ingresar una acción que no tenga parámetros, los parametros deben de ser reemplazados con el valor "0"), el ultimo componente de la tabla es un ejemplo de uso, donde se detalla una forma de llenar la Lista con la accion especificada.

La documentación del robot está incluida en un archivo pdf llamado [Documentación Robot Python.pdf](LINK).
