## CLASE 03
En esta clase estuvimos trabajando con el sistema git y sus principales comandos a usar en la terminal. 

En relación al sistema GIT:

### ¿Qué es el control de versiones?
Básicamente es el sistema que registra los cambios realizados por los colaboradores en los archivos de un proyecto. Ver el historial ordenado y detallado de todas las modificaciones hechas en un repositorio, esto faicilita la colaboración, poder hacer un seguimiento de los cambios-->mejora la gestión del desarrollo del proyecto.

### ¿Qué es la “cloning” en Git?
Crea un copia exacta de un respositorio Git existente en tu propia máquina. Por ejemplo, si encuentras un proyecto que te interese en GitHub y quieres contribuir o trabajar en él localmente, puedes justamente clonar ese repositorio en tu computadora por medio del comando 'git clone <url del repositorio>'.
Es realmente útil.

### ¿Cuál es el comando para rastrear y preparar archivos?
El comando "git add". Este comando es clave para preparar archivos y directorios para el próximo commit, los prepara para "salir al stage". Sean archivos nuevos o modificados este comando los prepara para ser incluidos en el área de preparación: "staging area" de Git.
Por ejemplo, cuando agregas un nuevo archivo a tu directorio de trabajo y deseas que Git comience a rastrearlo, usas "git add" para agregarlo al área de preparación por primera vez--->Git deberá comenzar a realizar un seguimiento de los cambios en este archivo para futuros commits.
Y en el caso de que realices modificaciones en un archivo que Git YA está rastreando(ref. el ejemplo anterior o como editar un archivo existente) necesitzs usar el "git add" para preparar esas modificaciones para el próximo commit. Esto agrega las versiones modificadas de esos archivos al área de preparación para que puedan ser incluidas en el commit.

El comando git add es fundamental para organizar y preparar tus cambios antes de crear un commit, lo que te permite tener un control preciso sobre qué modificaciones serán incluidas en tu historial de versiones.

### ¿Cuál es el comando para tomar una instantánea de los archivos modificados?
Es "git commit". Después de haber utilizado "git add" para preparar los archivos en el área de preparación, el comando "git commit" toma esos archivos preparados y crea una instantánea (snapshot) que representa un conjunto de cambios en el repositorio.

### ¿Cuál es el comando para enviar los archivos modificados a Github?
Para ese acción se usa el comando "git push". 

Después de haber realizado un commit con los cambios deseados, "git push" se usa para enviar esos commits al repositorio remoto especificado, como en google docs que puedes colaborar en simultáneo, git es más estructurado por ello fomenta el uso de ramas para desarrollar nuevas características o cambios sin afectar la rama principal. Así también esta acción brinda más control, permite revisar los cambios antes de fusionarlos en la rama principal = qué cambios se incluyen en la versión final del proyecto.

Info adicional: Git utiliza un sistema de control de versiones distribuido que permite a cada colaborador tener una copia completa del repositorio, incluyendo todo el historial de versiones. Esto significa que los cambios se realizan localmente y luego se pueden enviar al repositorio remoto, lo que ofrece más flexibilidad y control sobre los cambios que se realizan. 

˗ˏˋ ★ ˎˊ˗ Es como estar trabajando en un proyecto de equipo donde todos pueden editar un documento al mismo tiempo, como Google Docs. En este caso, todos están viendo y trabajando directamente en el mismo documento en la nube. Cada cambio que haces se actualiza instantáneamente para todos los demás.

Git es algo similar, pero con una pequeña diferencia. En lugar de trabajar directamente en el mismo documento en la nube, cada persona tiene su copia completa del documento en su computadora (una copia local). Así, es posible hacer todos los cambios que quieras en tu copia local sin preocuparte por afectar la versión principal que todos comparten.

Luego, cuando ya estés lista y quieras que todos vean tus cambios, puedes enviar esos cambios al documento principal (repositorio remoto). Esto se hace de manera organizada para evitar que los cambios de diferentes personas se mezclen de forma confusa. ˗ˏˋ ★ ˎˊ˗

## git add git commit git push - ACP

