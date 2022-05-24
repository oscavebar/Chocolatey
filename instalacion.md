# Instalación de chocolatey

Instalar chocolatey es realmente sencillo, solo tendremos que abrir la PowerShell de nuestro equipo Windows como administrador y copiar el siguiente comando:
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))

Esto información se ha sacado de la página oficial de Chocolatey, dejaré su web oficial en las referencias.
