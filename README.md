# Curso Optativo de Python - CUJAE

## Menú

- [Introducción](#introducción)
- [Contexto del Curso](#contexto-del-curso)
- [Contenido del Curso por Semanas](#contenido-del-curso-por-semanas)
- [Cómo Usar este Repositorio](#cómo-usar-este-repositorio)
- [Contribuciones y Feedback](#contribuciones-y-feedback)
- [Bibliografía](#bibliografía)

## Introducción

##### ¡Bienvenidos al curso optativo de Python!
~~Este curso es optativo pero aprender Python no debería serlo~~

Si estás leyendo esto es porque has escogido el camino del bien y quieres aprender Python, uno de los lenguajes de programación más poderosos y demandados en el mundo actual.

### Lo primero es... Por qué Python

Python es un lenguaje de programación versátil y de alto nivel que se distingue por su simplicidad y legibilidad del código, haciendo que sea especialmente atractivo para principiantes y expertos por igual. Este curso tiene como objetivo proporcionar una comprensión de los fundamentos de Python y su aplicación en diferentes áreas. Aprender Python no solo enriquecerá tu kit de herramientas tecnológicas, sino que podrás mejorar significativamente tu capacidad para analizar información compleja, automatizar tareas y desarrollar soluciones software efectivas, habilidades altamente valoradas en el mercado laboral actual.

### Pasos previos a la primera clase:

#### 1. Instalar Python

##### Si estás en Windows :(

1. Visita el sitio web oficial de Python en [python.org](https://python.org/).
2. Descarga el instalador de Python para Windows.
3. Ejecuta el instalador. Asegúrate de marcar la opción "Add Python to PATH" al inicio de la instalación.
4. Sigue las instrucciones del instalador hasta completar la instalación.
5. Abre la CMD y escribe `python --version` para verificar que la instalación fue exitosa.

##### Si estás en Linux :)

1. Abre una terminal.
2. Dependiendo de tu distribución, utiliza uno de estos comandos:
    - Para Debian, Ubuntu, y derivados: `sudo apt install python3`
    - Para Fedora y derivados: `sudo dnf install python3`
    - Para Arch y derivados: `sudo pacman -S python`
3. Verifica la instalación con `python3 --version`.

##### Si estás en Mac :|

1. Instala Homebrew si aún no lo tienes: `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
2. Abre una terminal y escribe `brew install python3`.
3. Verifica la instalación con `python3 --version`.

#### 2. Instalar VS Code

##### Para todos los sistemas operativos

1. Visita [code.visualstudio.com](https://code.visualstudio.com/) y descarga Visual Studio Code para tu sistema operativo.
2. Ejecuta el instalador descargado y sigue las instrucciones.
3. Una vez instalado, abre VS Code para asegurarte que se ejecuta correctamente.

#### 3. Instalar Jupyter Notebooks

##### Para todos los sistemas operativos

1. Asegúrate de que Python esté correctamente instalado.
2. Abre una terminal o CMD y escribe `pip install notebook`.
3. Verifica la instalación ejecutando `jupyter notebook`. Esto debería abrir Jupyter en tu navegador predeterminado.

#### 4. Instalar la extensión de VS Code para Jupyter (opcional)

1. Abre VS Code.
2. Ve a la sección de extensiones buscando o pulsando `Ctrl+Shift+X`.
3. Busca "Jupyter" y selecciona la extensión oficial de Microsoft.
4. Haz clic en instalar.

## Contexto del Curso

El curso se desarrolló como una opción electiva para estudiantes interesados en profundizar en la programación y en particular en el uso de Python para diversos fines como análisis de datos, desarrollo web y ciencia de datos. El objetivo principal del curso fue proporcionar una base sólida en Python, explorando desde conceptos básicos hasta aplicaciones más complejas utilizando diversas bibliotecas.

## Contenido del Curso por Semanas

**Semana 1: Introducción a Python**

**Semana 2: Sintaxis y Estructuras Básicas**

**Semana 3: Programación Orientada a Objetos (OOP)**

**Semana 4: Elementos extra de sintaxis en Python. Ejercitación del contenido**

**Semana 5: Introducción a Numpy**

(El README se irá actualizando todas las semanas hasta el final del curso)

## Cómo Usar este Repositorio

### Clonar el Repositorio

Para hacer uso de los notebooks, se recomienda clonar todo el repositorio y luego ejecutar los notebooks localmente utilizando las herramientas antes instaladas.

### Subir Ejercicios Semanales

Cada estudiante puede subir sus ejercicios por semana utilizando la funcionalidad de 'Issues' en este repositorio. Aquí te explicamos cómo hacerlo:

1. **Subir el Archivo del Ejercicio a tu Repositorio de GitHub**
   - Crea un repositorio en tu cuenta de GitHub para subir tus ejercicios.
   - Organízalo como creas conveniente, yo recomiendo separar los ejercicios por semana o tipo
   - Sube los archivos con tus ejercicios (.ipynb, .py, etc.)

2. **Crear un Issue para Notificar la Entrega**
   - Ve a la pestaña 'Issues' del repositorio del curso.
   - Haz clic en 'New Issue'.
   - Selecciona la plantilla 'Entrega de Ejercicio Semanal'.

3. **Completa la Plantilla de Issue**
   - **Semana**: Indica la semana del curso correspondiente al ejercicio.
   - **Descripción del Ejercicio**: Detalla lo que se ha trabajado en el ejercicio.
   - **Enlace al Archivo del Ejercicio**: Proporciona un enlace al archivo que has subido a tu repositorio (Abre tu archivo en github y copia y pega el link). Quedará algo como:
     ```
     (https://github.com/tu_usuario/tu_repositorio/blob/main/ejercicios1/tu_archivo.ipynb)
     ```
   - **Dudas o Problemas Encontrados**: Menciona cualquier pregunta o problema que hayas tenido durante el ejercicio.

4. **Etiquetar Correctamente el Issue**
   - Una vez que hayas creado el issue, selecciona la etiqueta correspondiente a la semana (e.g., `semana 1`, `semana 2`, etc.).

5. **Envía el Issue**
   - Una vez completado, haz clic en 'Submit new issue'.


## Contribuciones y Feedback

Se anima a los estudiantes a contribuir al repositorio mediante pull requests si desean agregar algo a los ejercicios o mejorar los ejemplos existentes. También agradezco cualquier feedback para mejorar el contenido y la entrega del curso.

## Bibliografía

- [Documentación oficial de Python](https://docs.python.org/3/)
