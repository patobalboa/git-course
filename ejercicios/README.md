# Ejercicios Prácticos de Git y GitHub

A continuación se presentan una serie de ejercicios prácticos para que puedas aplicar lo aprendido sobre Git y GitHub. Cada ejercicio está diseñado para reforzar tus habilidades en el uso de estas herramientas.

## Ejercicio 1: Creando mi portafolio en GitHub

1. Crea un nuevo repositorio en GitHub llamado `tu-nombre-de-usuario`. (Reemplaza `tu-nombre-de-usuario` con tu nombre de usuario de GitHub).
2. No selecciones nada más y dale a **Create repository**
3. Abre una carpeta donde puedas trabajar en tu proyecto y ábrela con `Git Bash` o tu terminal preferida.
4. Inicializa un nuevo repositorio local con el siguiente comando:
   ```bash
   echo "# tu nombre y apellido" >> README.md
   git init
   ```
5. Agrega el archivo `README.md` al repositorio local:
   ```bash
   git add README.md
   ```
6. Realiza un commit inicial:
   ```bash
    git commit -m "Primer commit: README inicial"
    ```
7. Conecta tu repositorio local con el remoto en GitHub:
     ```bash
   git remote add origin <url-del-repositorio>
   ```
9. Sube los cambios al repositorio remoto:
   ```bash
    git push -u origin main
    ```
10. Verifica en GitHub que el archivo `README.md` se haya subido correctamente.
11. **Entrega**: Captura de pantalla en la carpeta de ejercicios mostrando su `https://www.github.com/tu-nombre-de-usuario` y el archivo `README.md` con tu nombre y apellido. (El nombre de la imagen debe ser `ejercicio1.png`).
12. **Bonus**: Agrega una breve descripción de ti mismo/a en el archivo `README.md` y súbelo nuevamente al repositorio remoto.

[Guía Markdown](https://www.markdownguide.org/basic-syntax/) para formatear tu archivo `README.md`.

