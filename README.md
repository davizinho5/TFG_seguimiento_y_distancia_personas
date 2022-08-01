# TFG_segumiento_y_distancia_personas

El TFG se engloba dentro del proyecto [RoboGait](https://blogs.upm.es/robogait/), en el que se trata de medir la "forma" de andar y de correr a través de parámetros extraídos de imágenes de personas andando o corriendo. Estas imágenes se obtienen usando [robots](https://blogs.upm.es/robogait/prototypes/).

Para el correcto funcionamiento de los robots es necesario conocer la distancia que hay entre el robot y la persona a la que se graba. En términos muy generales, en este TFG se van a plantear soluciones para el cálculo de esta distancia. En principio, se va a contar con una cámara binocular (2 cámaras que trabajan juntas como nuestros ojos), por lo que se podrá tener información visual de color (como cualquier cámara de un móvil) y distancia a los objetos que aparecen en las imágenes (profundidad). 

Para empezar a trabajar, hasta que nos veamos en septiembre, hay algunos temas que puedes ir mirando/aprendiendo para que luego sea más sencillo comenzar. 

- Ubuntu 20.04. Es el sistema operativo que hay instalado en los robot y, por tanto, sobre el que tienen que funcionar las soluciones que se desarrollen. 

- Visión artificial. Es un campo de la ingeniería que emplea técnicas basadas en matemáticas para analizar una imagen usando un ordenador. Para facilitar el desarrollo de soluciones, existe una librería llamada [OpenCV](https://opencv.org/) que permite, de una manera sencilla, usar esas herramientas matemáticas sobre imágenes. 

- Detección y seguimiento de personas (person detection and tracking) en imágenes a color, de profundidad, o en ambas a la vez. 



