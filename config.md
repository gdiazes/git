# Manual: Configuración Inicial de Git

**Introducción:**

Este manual te guiará a través de los primeros pasos para configurar Git en tu sistema. Aprenderás cómo instalar Git (si aún no lo tienes) y cómo establecer tu identidad para que tus contribuciones sean correctamente atribuidas en tus proyectos. Esta configuración inicial es fundamental para comenzar a utilizar Git de manera efectiva.

**Tabla de Contenidos:**

* [Instalación de Git](#instalacion-de-git)
* [Configuración de tu Identidad en Git](#configuracion-de-tu-identidad-en-git)
    * [Establecer tu Nombre de Usuario](#establecer-tu-nombre-de-usuario)
    * [Establecer tu Dirección de Correo Electrónico](#establecer-tu-direccion-de-correo-electronico)
    * [Verificar tu Configuración](#verificar-tu-configuracion)
* [Configuración Opcional: Editor de Texto Predeterminado](#configuracion-opcional-editor-de-texto-predeterminado)
* [Resumen](#resumen)
* [Palabras Clave](#palabras-clave)

## Instalación de Git

Si aún no tienes Git instalado en tu computadora, sigue las instrucciones correspondientes a tu sistema operativo:

* **Windows:**
    * Ve a la página de descarga de Git para Windows: [https://git-scm.com/download/win](https://git-scm.com/download/win)
    * La descarga debería comenzar automáticamente.
    * Una vez descargado, ejecuta el instalador (`.exe`) y sigue las instrucciones en pantalla. Generalmente, las opciones predeterminadas son adecuadas para la mayoría de los usuarios.

* **macOS:**
    * **Opción 1 (Recomendada): Utilizando Homebrew:** Si tienes Homebrew instalado, abre tu Terminal y ejecuta el siguiente comando:
        ```bash
        brew install git
        ```
    * **Opción 2: Instalador:** Ve a la página de descarga de Git para macOS: [https://git-scm.com/download/mac](https://git-scm.com/download/mac)
        * Descarga el instalador y sigue las instrucciones.
    * **Opción 3: Xcode Command Line Tools:** Si tienes Xcode instalado, Git podría ya estar presente. Abre tu Terminal y prueba ejecutar `git --version`. Si no está instalado, se te ofrecerá instalar las Command Line Tools, que incluyen Git.

* **Linux (Debian/Ubuntu):**
    * Abre tu Terminal y ejecuta el siguiente comando:
        ```bash
        sudo apt update
        sudo apt install git
        ```

* **Linux (Fedora/CentOS/RHEL):**
    * Abre tu Terminal y ejecuta el siguiente comando:
        ```bash
        sudo dnf install git
        ```

    * O para CentOS/RHEL:
        ```bash
        sudo yum install git
        ```

Una vez instalado, puedes verificar la instalación abriendo tu terminal o símbolo del sistema y ejecutando:

```bash
git --version
