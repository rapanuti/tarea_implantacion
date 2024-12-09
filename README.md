
[![Open Source Love](https://firstcontributions.github.io/open-source-badges/badges/open-source-v1/open-source.svg)](https://github.com/firstcontributions/open-source-badges)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Open Source Helpers](https://www.codetriage.com/roshanjossey/first-contributions/badges/users.svg)](https://www.codetriage.com/roshanjossey/first-contributions)

<!-- This is my contribution -->
#### _Read this in [other languages](translations/Translations.md)._

# Primeras contribuciones

Este proyecto tiene como objetivo simplificar y guiar la forma en que los principiantes realizan su primera contribución. Si desea realizar su primera contribución, siga los pasos a continuación.

Si no se siente cómodo con la línea de comandos, [aquí encontrará tutoriales que utilizan herramientas GUI.](#tutorials-using-other-tools)_

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/fork.png" alt="fork this repository" />

#### Si no tienes git en tu máquina, [instálalo](https://docs.github.com/en/get-started/quickstart/set-up-git).

## Bifurcar este repositorio

Bifurque este repositorio haciendo clic en el botón de bifurcación que se encuentra en la parte superior de esta página. Esto creará una copia de este repositorio en su cuenta.

## Clonar el repositorio

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/clone.png" alt="clone this repository" />

Ahora clona el repositorio bifurcado en tu máquina. Ve a tu cuenta de GitHub, abre el repositorio bifurcado, haz clic en el botón de código y luego en el ícono de copiar al portapapeles .

Abra una terminal y ejecute el siguiente comando git:

```bash
git clone "url you just copied"
```

donde "url que acabas de copiar" (sin las comillas) es la url de este repositorio (tu bifurcación de este proyecto). Consulta los pasos anteriores para obtener la url.

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/copy-to-clipboard.png" alt="copy URL to clipboard" />

Por ejemplo:

```bash
git clone git@github.com:this-is-you/first-contributions.git
```

¿Dónde this-is-you está tu nombre de usuario de GitHub? Aquí estás copiando el contenido del repositorio first-contributions de GitHub a tu computadora.

## Crear una rama

Cambie al directorio del repositorio en su computadora (si aún no está allí):

```bash
cd first-contributions
```
Ahora crea una rama usando  una rama usando el  `git switch` commando:

```bash
git switch -c your-new-branch-name
```

Por ejemplo:

```bash
git switch -c add-alonzo-church
```

## Realizar los cambios necesarios y confirmar dichos cambios.

Ahora abre `Contributors.md` el archivo en un editor de texto y agrégale tu nombre. No lo coloques al principio ni al final del archivo, colócalo en cualquier lugar intermedio. Ahora, guarda el archivo.

<img align="right" width="450" src="https://firstcontributions.github.io/assets/Readme/git-status.png" alt="git status" />

Si vas al directorio del proyecto y ejecutas el comando `git status`,verás que hay cambios.

Añade esos cambios a la rama que acabas de crear usando el  `git add` commando:

```bash
git add Contributors.md
```

Ahora confirme esos cambios usando el `git commit` commando:

```bash
git commit -m "Add your-name to Contributors list"
```

Reemplazando `your-name` con tu nombre.

## Enviar cambios a GitHub

Envíe sus cambios usando el comando `git push`:

```bash
git push -u origin your-branch-name
```

Reemplazando `your-branch-name` con el nombre de la rama que creaste anteriormente.

<details>
<summary> <strong>If you get any errors while pushing, click here:</strong> </summary>

- ### Si recibe algún error al presionar, haga clic aquí:
     <pre>remote: Support for password authentication was removed on Octubre 20, 2024. Please use a personal access token instead.
  remote: Please see https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/ for more information.
  fatal: Authentication failed for 'https://github.com/<your-username>/first-contributions.git/'</pre>
 Vaya al[ tutorial de GitHub](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account) sobre cómo generar y configurar una clave SSH para su cuenta.

</details>

## Envíe sus cambios para revisión

Si accedes a tu repositorio en GitHub, verás un `Compare & pull request` botón. Haz clic en él.



<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/compare-and-pull.png" alt="create a pull request" />

Ahora envíe la solicitud de extracción.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/submit-pull-request.png" alt="submit pull request" />

Pronto fusionaré todos los cambios en la rama principal de este proyecto. Recibirás un correo electrónico de notificación una vez que se hayan fusionado los cambios.

## ¿Hacia dónde ir desde aquí?

¡Felicitaciones! ¡Acabas de completar el flujo de trabajo estándar de bifurcación -> clonación -> edición -> solicitud de incorporación de cambios que encontrarás a menudo como colaborador!




Ahora, comencemos a contribuir a otros proyectos.

### [Material adicional](additional-material/git_workflow_scenarios/additional-material.md)

## Tutoriales sobre el uso de otras herramientas

| <a href="gui-tool-tutorials/github-desktop-tutorial.md"><img alt="GitHub Desktop" src="https://desktop.github.com/images/desktop-icon.svg" width="100"></a> | <a href="gui-tool-tutorials/github-windows-vs2017-tutorial.md"><img alt="Visual Studio 2017" src="https://upload.wikimedia.org/wikipedia/commons/c/cd/Visual_Studio_2017_Logo.svg" width="100"></a> | <a href="gui-tool-tutorials/gitkraken-tutorial.md"><img alt="GitKraken" src="https://firstcontributions.github.io/assets/gui-tool-tutorials/gitkraken-tutorial/gk-icon.png" width="100"></a> | <a href="gui-tool-tutorials/github-windows-vs-code-tutorial.md"><img alt="VS Code" src="https://upload.wikimedia.org/wikipedia/commons/2/2d/Visual_Studio_Code_1.18_icon.svg" width=100></a> | <a href="gui-tool-tutorials/sourcetree-macos-tutorial.md"><img alt="Sourcetree App" src="https://wac-cdn.atlassian.com/dam/jcr:81b15cde-be2e-4f4a-8af7-9436f4a1b431/Sourcetree-icon-blue.svg" width=100></a> | <a href="gui-tool-tutorials/github-windows-intellij-tutorial.md"><img alt="IntelliJ IDEA" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9c/IntelliJ_IDEA_Icon.svg/512px-IntelliJ_IDEA_Icon.svg.png" width=100></a> |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [GitHub Desktop](gui-tool-tutorials/github-desktop-tutorial.md)                                                                                             | [Visual Studio 2017](gui-tool-tutorials/github-windows-vs2017-tutorial.md)                                                                                                                          | [GitKraken](gui-tool-tutorials/gitkraken-tutorial.md)                                                                                                                                        | [Visual Studio Code](gui-tool-tutorials/github-windows-vs-code-tutorial.md)                                                                                                                  | [Atlassian Sourcetree](gui-tool-tutorials/sourcetree-macos-tutorial.md)                                                                                                                                      | [IntelliJ IDEA](gui-tool-tutorials/github-windows-intellij-tutorial.md)                                                                                                                                                          
