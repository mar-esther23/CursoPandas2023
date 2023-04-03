# Análisis y visualización de datos con python
# 0. Instalación e inicio con Anaconda

* 0.a Instalación de anaconda
* 0.b Entornos (environments)
* 0.c Instalación de librerias

---

Anaconda es una distribución de software libre y de código abierto para el manejo de paquetes y dependencias en Python. Incluye más de 1,500 paquetes de ciencia de datos, ingeniería y análisis y se utiliza ampliamente en la comunidad de ciencia de datos para administrar y compartir entornos de desarrollo y proyectos. Anaconda también incluye herramientas para el manejo de entornos virtuales, lo que permite a los usuarios trabajar con diferentes versiones de paquetes y dependencias de manera eficiente y sin afectar otros proyectos.



## 0.a Instalación de anaconda

Instalación con el instalador descargado:

1. Descargar el instalador de Anaconda desde el sitio web oficial de Anaconda (https://www.anaconda.com/products/distribution). Asegúrese de descargar la última versión estable y compatible con su sistema operativo (Windows, macOS o Linux).
2. Ejecutar el instalador descargado y seguir las instrucciones en pantalla para instalar Anaconda.
3. Verificar la instalación de Anaconda. Para hacer esto, abra una terminal o línea de comandos y escriba conda list. Si la instalación se ha realizado correctamente, verá una lista de paquetes que se incluyen con Anaconda.
4. Actualizar Anaconda. Para hacer esto, abra una terminal o línea de comandos y escriba conda update conda. Esto actualizará Anaconda a la última versión disponible.

Instalación con el navegador de Anaconda:
1. Descargar e instalar el navegador de Anaconda desde el sitio web oficial de Anaconda (https://www.anaconda.com/products/navigator).
2. Verificar la instalación de Anaconda. Para hacer esto, abra el navegador de Anaconda y verifique si se ha iniciado correctamente.
3. Actualizar Anaconda. Para hacer esto, abra el navegador de Anaconda y busque la opción de actualización. Esto actualizará Anaconda a la última versión disponible.

Nota: Si tiene problemas durante la instalación, consulte la documentación oficial de Anaconda para obtener ayuda adicional.



## 0.b Entornos (environments)

Un entorno de Anaconda es un lugar separado en el computador que te permite tener diferentes versiones de paquetes de Python y usarlas de manera independiente. Esto es útil para evitar conflictos entre proyectos y asegurar que los resultados sean consistentes y reproducibles. Con entornos de Anaconda, puedes tener más control y flexibilidad sobre la configuración de tus proyectos de Python.

Generación de un entorno de Anaconda en terminal:
1. Abra una terminal o línea de comandos.
2. Escriba conda create --name nombre_del_entorno para crear un nuevo entorno. Reemplace nombre_del_entorno con el nombre que desea darle al entorno.
3. Seleccione y cuando se le solicite confirmación para crear el entorno.
4. Escriba conda activate nombre_del_entorno para activar el entorno recién creado. Reemplace nombre_del_entorno con el nombre que le dio al entorno.
5. Verifique que el entorno está activo escribiendo conda info en la terminal. El nombre del entorno activo se mostrará en la línea "active environment".

Generación de un entorno de Anaconda con el navegador:
1. Abra el navegador de Anaconda.
2. Haga clic en la opción "Environments" en la barra de navegación de la izquierda.
3. Haga clic en el botón "Create" en la parte superior derecha de la pantalla.
4. Escriba un nombre para el entorno en el campo "Name" y seleccione una versión de Python en el campo "Python".
5. Haga clic en el botón "Create" para crear el entorno.
6. Verifique que el entorno está seleccionado en la sección "Environments" del navegador de Anaconda.


## 0.c Instalación de librerias

Un paquete o librería de Python es un conjunto de módulos o funciones pre-escritas que pueden ser usadas en un programa para realizar tareas específicas. Por ejemplo, la librería NumPy es útil para trabajar con arrays numéricos en Python, mientras que la librería Pandas es útil para manipular y analizar datos. Los paquetes y librerías son una parte fundamental de la comunidad de Python y permiten a los desarrolladores ahorrar tiempo y esfuerzo al reutilizar código existente.

Instalación a través de la terminal:

1. Abre la terminal o línea de comandos.
2. Escribe el comando "conda install" seguido del nombre del paquete que deseas instalar. Por ejemplo, para instalar la librería NumPy, escribe "conda install numpy".
3. Presiona Enter.
4. Sigue las instrucciones en la terminal para completar la instalación.

Instalación a través del navegador Anaconda Navigator:

1. Abre Anaconda Navigator.
2. Haz clic en "Environments" en la barra lateral.
3. Selecciona el entorno en el que deseas instalar el paquete.
4. Haz clic en el botón "Not Installed" en la parte superior de la pantalla.
5. Busca el paquete que deseas instalar y haz clic en él.
6. Haz clic en el botón "Apply" para instalar el paquete.
7. Sigue las instrucciones en la pantalla para completar la instalación.

En ambos casos, es posible que sea necesario actualizar Anaconda o el entorno antes de poder instalar un paquete nuevo.



