# Documentación U1 Lenguajes de Marcas

## Introducción a Lenguajes de Marcas

### Definición

Un lenguaje de marcas organiza info. mediante una sintaxis basada en marcas o tags.

### Clasificación de Lenguajes de Marcas
| Tipo de Lenguaje | Uso | Ejemplos |
|------------------|-----|----------|
| Presentación | Dar formatoa docs | HTML, CSS |
| Intercambio de Información | Almacenar info de forma ordenada | XML, RSS |
| Documentación | Documentar proyectos | Markdown, WikiTex |


## Instalación y config del entorno

1. Instalamos [VSCode](https://code.visualstudio.com/) 
2. Instalamos Plugins
  - [Live Preview](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server)
  - [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
  - [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
  - [XML By Red Hat](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml)

### Tabla Descripción de Plugins

| Plugin | Uso | Logo |
|------------------|-----|----------|
| Live Preview | Visualizar y acutualizar tus páginas a tiempo real. | ![LogoLivePreview](/U1/imagenes/Captura%20desde%202026-09-18%2011-10-10.png) |
| HTML CSS Support | Proporciona ayudas y autocompletados inteligentes mientras escribes el código. | ![LogoHTMLCSSSupport](/U1/imagenes/Captura%20desde%202026-09-18%2011-10-35.png)|
| Markdown All in One | Simplifica la creación y edición de documentos | ![MarkdownAllInOne](/U1/imagenes/Captura%20desde%202026-09-18%2011-11-54.png)
|XML By Red Hat| Autocompletado de XML | ![LogoXMLByRedHat](/U1/imagenes/Captura%20desde%202026-09-18%2011-12-21.png) |

1. Instalar Git
```bash
sudo apt install git
```

2. Iniciar repositorio Git
```bash
git init
git add.
git commit -m "Inicializar repositorio // README básico UD1"
```
3. Conectar VSCODE + GitHub
```bash
git remote add origin https://github.com/samueldanisc-code/LM-SAMU.git
git branch -M main
git push -u origin main 
```
4. En caso de fallo:
```bash
git pull origin main --rebase
git push origin main
```
5. Conectar repositorios de una máquina a otra
```bash
git clone https://github.com/samueldanisc-code/LM-SAMUEL.git
git pull
```

6. Actualizar contenidos
```bash
git add.
git commit -m "Continuamos con el README UD1"
git push -u origin main
```
