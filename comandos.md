# La línea de comandos
Existen muchas formas de usar Git. Por un lado tenemos las herramientas originales de línea de comandos, y por otro lado tenemos una gran variedad de interfaces de usuario con distintas capacidades. En este libro vamos a utilizar Git desde la línea de comandos. La línea de comandos es el único lugar en donde puedes ejecutar todos los
comandos de Git - la mayoría de interfaces gráficas de usuario solo implementan una parte de las características de Git por motivos de simplicidad. 

Nosotros esperamos que sepas cómo abrir el **Terminal en Mac**, o el ["Command Prompt"](https://tutorialesyayudas.com/como-abrir-el-command-prompt-en-windows-10/) o ["Powershell"](https://learn.microsoft.com/es-es/powershell/scripting/overview?view=powershell-7.2) en Windows.

## Comandos de GIT básicos
Aquí hay algunos comandos básicos de GIT que debes conocer:

-**git init** creará un nuevo repositorio local GIT. El siguiente comando de Git creará un repositorio en el directorio actual.

`git init`

-**git clone** se usa para copiar un repositorio. Si el repositorio está en un servidor remoto, usa:

`git clone nombrede usuario@host:/path/to/repository`

-**git add** se usa para agregar archivos al área de preparación. Por ejemplo, el siguiente comando de Git básico indexará el archivo temp.txt:

`git add <temp.txt>`

-**git commit** creará una instantánea de los cambios y la guardará en el directorio git.

`git commit –m “El mensaje que acompaña al commit va aquí”`

-**git push** se usa para enviar confirmaciones locales a la rama maestra del repositorio remoto. Aquí está la estructura básica del código:

´git push  origin <master>´

-**git pull** fusiona todos los cambios que se han hecho en el repositorio remoto con el directorio de trabajo local.

`git pull`


[Ir a Git](./git.md)

[Ir a GitHub](./github.md)