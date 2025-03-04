# ¿Qué es la visualización de datos?

Autoria: Celia Millán
Etiquetas: Diseño, IA, Visualización, estadística
Hora de creación: 31 de agosto de 2024 10:23

> *Es un proceso que **facilita la comprensión de la información***
> 

La visualización de datos consiste en representar información (tanto numérica como categórica) de manera visual, a través de gráficas, mapas, diagramas u otros formatos visuales. 

Esta disciplina forma parte del **análisis de datos**. **Facilita la comprensión** de la información y permite interpretar los datos **detectando** patrones, tendencias o cosas que no encajan (anomalías) **de manera visual.**

El primer paso antes de hacer una visualización de datos es preguntarse :

<aside>

    🗣

    ☝**¿Qué datos tengo?**

    ☝**¿Los entiendo bien?**

    ☝**¿Qué quiero obtener de ellos?**

</aside>

### **Respondamos la primera pregunta: ¿Qué datos tengo?**

Generalmente, los datos se encuentran en formato **CSV***, es decir, en tablas formadas por filas y columnas. Cada fila representa un registro donde se almacena la información.

- ** aclaración*
    
    CSV *en realidad es **un archivo de texto** donde los valores están separados por comas (o a veces por punto y coma o tabulaciones). Luego, cuando se abre en programas como Excel, Google Sheets o Python, se visualiza como una tabla.*
    

Bien, ahora que sabemos qué tipo de archivo tenemos, necesitamos poder consultarlo. Podríamos hacerlo a través de Excel, pero si nuestra idea es realizar un análisis de datos con visualización, lo mejor es tirarse directamente a la piscina…

*¡Vamos a programar!😋*

El lenguaje más utilizado para el análisis de datos hoy en día es **Python**, que cuenta con una librería llamada **pandas**, la cual tiene todos los métodos (es decir, funciones) necesarios para llevar a cabo un buen análisis de datos.

Continuemos. Python no es tan 'majo' como JavaScript y no viene por defecto en nuestros ordenadores personales, así que es necesario instalarlo. Además, también deberemos instalar Jupyter Notebook.

**Jupyter Notebook** es una aplicación que nos e permite crear documentos que intercalan código con texto en Markdown, lo que facilita la escritura de explicaciones y comentarios mientras trabajamos.

Pues bien, ya han aparecido los 4 amiguitos del análisis de datos.

> Los CSV, Python, pandas y los Jupyter Notebooks
> 

> 📄 + 🐍 + 🐼 + 📔
> 

*“la cuchi panda del análisis de datos”🥳*

Un archivo con datos, un lenguaje de programación, una librería de ese mismo lenguaje y un cuaderno para poder documentar nuestro análisis.

¿Entendemos para que queremos cada cosa? si la es respuesta es no, te recomiendo que te tomes un momento y le preguntes a tu amigo Geppetto ( chatgpt).

Bien ahora teniendo todo un poco más claro, tus objetivos son: instalar Pyhton e instalar Júpiter notebook, de nuevo ayúdate de Geppetto para conseguirlo

- instalación
    
    1️⃣instalas Python
    
    https://www.python.org/downloads/
    
    2️⃣ instalas Jupyter notebook
    
    ```jsx
    pip install notebook
    ```