### Sobre la lectura
#### ¿Qué es un editor de texto?
Un editor de texto es una herramienta de software que se puede descargar e instalar en tu computadora, o a la que puedes acceder en línea a través de tu navegador web. Este software te permite escribir y gestionar texto, especialmente el texto que creas para construir un sitio web.

#### ¿Cuáles son las cuatro características importantes que se deben buscar en un editor de texto?
Así, las cuatro y más importantes características en un editor de texto son las siguientes: 
1. **Autocompletar código**
2. **Resaltado de sintaxis**
3. **Una buena variedad de temas** (para reducir la fatiga visual)
4. **La posibilidad de elegir entre una amplia selección de extensiones** disponibles cuando las necesite.

#### ¿Qué hacen los siguientes comandos?
- **pwd (Print Working Directory):** Este comando muestra el directorio actual en el que te encuentras trabajando. Es como ver la ubicación exacta en la que te encuentras dentro del sistema de archivos de tu computadora.

- **ls (List):** Este comando muestra una lista de todos los archivos y carpetas que están dentro del directorio en el que te encuentras. Si se usa sin argumentos adicionales, simplemente mostrará una lista de los nombres de los archivos y directorios en el directorio actual. Es como ver qué hay dentro de la carpeta en la que estás.

- **cd (Change Directory):** Se usa para cambiar el directorio actual. Es como abrir una carpeta dentro de otra para acceder a su contenido. Puedes usar cd seguido del nombre del directorio al que deseas moverte. Por ejemplo, `cd docs` te llevará al directorio llamado "docs" si existe en el directorio actual.

- **mkdir (Make Directory):** Permite crear una nueva carpeta. Por ejemplo, usar `mkdir` seguido del nombre que deseas darle al nuevo directorio. Así: `mkdir proyecto` creará un directorio llamado "proyecto" en el directorio actual.

- **touch:** Con este comando podrás crear nuevos archivo vacíos. Es como crear un documento nuevo en blanco. Puedes usar `touch` seguido del nombre que deseas darle al archivo. Por ejemplo, `touch archivo.txt` creará un archivo llamado "archivo.txt" en el directorio actual.

#### ¿Qué sucede en el siguiente escenario si ingresas estos comandos y argumentos en la línea de comandos? 

- **cd projects:**
  - Se ejecuta: Cambias al directorio "projects".
  - Se muestra: Si el comando se ejecuta correctamente, no se mostrará ninguna salida en la terminal. Simplemente te moverás al directorio "projects".

- **mkdir new-project:**
  - Se ejecuta: Crea un nuevo directorio llamado "new-project" dentro del directorio "projects".
  - Se muestra: Si se ejecuta correctamente, no se mostrará ninguna salida en la terminal. El directorio "new-project" será creado.

- **touch new-project/newfile.md:** 
  - Se ejecuta: Crea un nuevo archivo llamado "newfile.md" dentro del directorio "new-project".
  - Se muestra: Si se ejecuta correctamente, no se mostrará ninguna salida en la terminal. El archivo "newfile.md" será creado dentro de "new-project".

- **cd ..:**
  - Se ejecuta: Retrocedes al directorio padre del directorio actual, es decir, al directorio que contiene al directorio "projects".
  - Se muestra: Si se ejecuta correctamente, no se mostrará ninguna salida en la terminal. Simplemente cambiarás al directorio padre.

- **ls projects/new-project:** 
  - Al ejecutar este comando en la línea de comandos, se mostrará una lista de todos los archivos y carpetas que se encuentran dentro del directorio "new-project", el cual está dentro del directorio "projects". Si hay archivos o carpetas dentro de "new-project", verás sus nombres listados en la pantalla de la terminal.
