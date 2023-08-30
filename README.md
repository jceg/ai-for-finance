# Taller sobre AI en el sector financiero [30.08.2023]

En este repositorio encontrarán los materiales y recursos necesarios para seguir la charla y realizar los casos prácticos.

## Descripción de la Charla

El objetivo principal de esta charla es proporcionarles una comprensión básica de cómo se puede aplicar la Inteligencia Artificial en el sector financiero. 

Tambien, aprenderán sobre algunas de las principales técnicas de IA utilizadas en el sector financiero y cómo aplicarlas para tomar decisiones informadas y mejorar la eficiencia de los procesos financieros.

## Duración

La duración de la charla es de 2 horas.

## Contenido

1.	Introducción a la Inteligencia Artificial en el sector financiero
2.	Ejemplos de técnicas de IA utilizadas en el sector financiero
3.	Casos de uso de IA en el sector financiero
4.	Implementación de soluciones en el sector financiero


## Instrucciones para los asistentes

### 1. Preparación Inicial

Antes de comenzar, asegúrate de tener los siguientes requisitos en orden:

- **Cuenta de Google:** Asegúrate de tener una cuenta de Google, ya que utilizaremos Google Colab para interactuar con los notebooks.


### 2. Acceder a Google Colab

1. Abre tu navegador y ve a [Google Colab](https://colab.research.google.com/).
2. Si no has iniciado sesión en tu cuenta de Google, inicia sesión.
3. Una vez que hayas iniciado sesión, estarás en la página de inicio de Google Colab.

### 3. Clonar el Repositorio

Vamos a clonar este repositorio en tu Google Drive. Esto te permitirá acceder y ejecutar los notebooks desde tu cuenta de Google Colab.

1. En Google Colab, abre un nuevo cuaderno y ejecuta la siguiente celda para montar tu Google Drive:

   ```python
   from google.colab import drive
   drive.mount('/content/drive')
    ```
2. Después de montar tu Google Drive, cambia el directorio actual al directorio principal de tu unidad Google Drive con la siguiente celda:

   ```python
   %cd /content/drive/MyDrive/
   ```

3. Clona el repositorio en tu Google Drive con la siguiente celda:

   ```python
   !git clone https://github.com/jceg/ai-for-finance.git
   ```

Una vez que hayas clonado el repositorio, podrás acceder a los notebooks y otros recursos desde tu Google Drive.

### 4. Explorar los Notebooks

Los notebooks son la parte central de este taller. Contienen breves explicaciones, código y ejercicios. Sigue estos pasos para abrir y explorar los notebooks:

1. Navega a la carpeta "notebooks" en el repositorio clonado en tu Google Drive.
2. Abre uno de los archivos `.ipynb` haciendo clic en él.
3. El notebook se abrirá en una nueva pestaña de Google Colab. ¡Ahora estás listo para empezar a aprender y experimentar!

### 5. Acceder a los Datasets

Los datasets son conjuntos de datos que utilizaremos en los casos prácticos. Para acceder a ellos, navega a la carpeta "datasets" en el repositorio clonado en tu Google Drive.

Dentro de los notebooks, cuando sea necesario cargar un dataset, utilizaremos su ubicación relativa en tu Google Drive.

¡Esperamos que disfrutes del taller!
