# Semana 3 – MLFlow

## Objetivos



✍   Familiarizarse con la herramienta MLflow para el manejo y administración de los experimentos realizados con diferentes estimadores y parámetros.

✍   Entrenar un modelo propio

## Prerrequisitos

✍   Conocimientos intermedios de programación en Python y habilidades de uso de notebooks. Esto es, uso de librerías, lectura y seguimiento de código ejemplo, desarrollo de código propio, depuración de programas, generación de resultados.

✍   Saber descargar e instalar programas en su máquina local personal.

✍   Saber seguir rutas de localización de archivos y carpetas.

✍   Saber descargar documentos y subir entregables en la infraestructura de Coursera.

## Metodología

✍   Se realiza en los grupos de trabajo.

✍   Deben utilizarse la infraestructura, datos y *notebooks* entregados para el desarrollo de los retos propuestos.

✍   Las instrucciones de cada reto se encuentran descritas en el enunciado a continuación.

✍    No se reciben trabajos desarrollados en otras infraestructuras ni con otros conjuntos de datos.

✍   Se entrega en la infraestructura de Coursera, en el enlace previsto para tal fin.

# Enunciado

Los trabajos prácticos del curso se realizan en una infraestructura virtual, que debe ser instalada en su máquina personal. Esto le permite trabajar en un entorno computacional que ya está configurado, de manera que su esfuerzo y tiempo se concentren en el desarrollo de los retos. A continuación, encuentra la descripción de cada una de las actividades que debe lograr.

**[1]**  **Descargue la imagen de docker**

✍   Para esta actividad necesita dos imágenes que se encuentra en los repositorios de docker hub:

 `mineuniandes/dsa_s3` y `mineuniandes/dsa_mlflow_s3`

✍   Descargue el archivo `docker-compsoe.yaml`

✍   Para descargar la imagen corra alguno de estos comandos en una terminal o shell de windows dentro de la carpeta que contiene el archivo docker-compose.yaml:

```bash
  docker-compose pull
```

o 

```bash
docker pull mineuniandes/dsa_s2
docker pull mineuniandes/dsa_mlflow_s3

```



✍   Para correr el contenedor corra el siguiente comando en una terminal o shell de windows:

```bash
docker-compose up
```



En la terminal encontrará una URL de este estilo:

  ‘’http://127.0.0.1:8888/lab?token=0f5dabcdcf9fd9941ade8ce267c9a61327c0ed4db82c1a0c”

 Esta URL le da acceso al cuaderno de Jupyter para que pueda realizar la actividad, siga la guía del *notebook*.

  

**[2]**  **ETL**

¿Qué es MLFLOW?

 

Mlflow es una plataforma open source que nos ayuda a manejar el ciclo de vida de los modelos en inteligencia artificial (ML lifecycle); para esto contamos con experimentos, reproducibilidad, despliegues y un registro central de los modelos entrenados que podemos comparar.

 

Recordemos que el ciclo de vida de los modelos en inteligencia artificial está compuesto en cuatro pasos.

 

- Preparación de los datos

- Construcción del modelo

-  Análisis del modelo

- Despliegue del modelo

 

En esta actividad **debe utilizar los datos procesados en la actividad ETL de la semana 2**, con estos datos deberá entrenar su modelo y generar el informe con el uso de la herramienta de MLFlow. El contenedor Docker cuenta con unos datos que ya se encuentran mapeados los puntos más cercanos (la estación de clima y el punto de interés) a la estación de bicicleta inicial, los cuales se utilizan como ejemplo para el uso de la herramienta, sin embargo, están lejos de ser óptimos o estar completamente limpios.


 Usted debe entrenar su propio modelo y realizar un informe del proceso con MLFlow. si desea trabajar con otras librerías para el entrenamiento como *Tensorflow* o *Dask* puede hacerlo con total libertad.

 En caso de tener dudas sobre los ejemplos, los *notebooks* o la manera de subir sus resultados a Coursera, utilice el canal general de Slack.

Ubicación del notebook de trabajo: En la raíz del contenedor, lo verá cuando ejecute el contenedor.

Se debe incluir el usuario Uniandes de todos los participantes del grupo y el título de la actividad. Ejemplo:
`jp.gonzales10_la.rodriguez_informe_s4.pdf`

**Entrega**

Realice la entrega del PDF utilizando el enlace previsto en Coursera.

**Fecha y hora límite de entrega**: **domingo** de la **semana 3** del curso a las **10 PM hora COLOMBIA**

☝   Es la única forma válida de entrega.

☝   Asegúrese de entregar el documento correspondiente.

☝   No se reciben entregas tardías o incompletas.