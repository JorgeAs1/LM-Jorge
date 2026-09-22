# Documentación UD1 Lenguajes de Marcas 16/9/26

## Introducción a Lenguajes de marcas

### Definición

Un lenguaje de marcacs organiza infomación medante una sintaxis basada en marcas o etiquetas.

### Clasificación de Lenguajes de marcas

|Tipo|Uso|Ejemplos|
|:----:|:---:|:--------:|
|Presentación|Dar forma a docmentos de texto|HTML, CSS|
|Intercambio|Almacenar información de forma ordenada|XML, RSS|
|Documentacion|Documentar proyectos|Markdown, WikiTex |

## Instalación y configuración del entorno

1. Instalar [VS Code](https://code.visualstudio.com/)
2. Instalar Plugins

## Descripcion de plugins


| Extensión | Descripción | Icono |
| :---: | :---: | :---: |
| [Live Preview](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server) | Previsualizar como queda el código que vamos creando. | ![Live Preview](img/livepre.png) |
| [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css) | Ayuda para crear y editar CSS y HTML. | ![HTML CSS](img/htmlcss.png) |
| [XML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml) | Ayuda con el lenguaje XML. | ![XML](img/xml.png) |
| [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) | Ayuda a crear y editar de forma eficiente Markdown. | ![Markdown](img/md.png) |
3. Instalar git
```bash
sudo apt install git
```
4. Inicializar repositorio git (en la carpeta del proyecto)
```bash
git init
git add .
git commit -m "Comentario descriptivo"
```
5. Conectar con github
```bash
git remote add origin url -repo
git branch -M main 
git push -u origin main
```
6. En caso de fallo 
```bash
git pull origin main --rebase
git push origin main
```
7. Antes de commitear y despues de añadir cambios
```bash
git add "nombre del archivo"
```
8. Para bajarnos nuestro trabajo a local
```bash
git clone "url de lo que nos queramos bajar"

git pull 
```



