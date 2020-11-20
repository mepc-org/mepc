<img src="https://camo.githubusercontent.com/af41a9d160332897feb22f75ecfc78bd6dd2a42b25be6c7ff72aeccd117bdde8/68747470733a2f2f6170692e6e65746c6966792e636f6d2f6170692f76312f6261646765732f36383436346338382d333663362d346265382d626338622d3839366262643237626636392f6465706c6f792d737461747573" alt="Netlify Status" data-canonical-src="https://api.netlify.com/api/v1/badges/68464c88-36c6-4be8-bc8b-896bbd27bf69/deploy-status" style="max-width:100%;">

## Sitio web de MEPC en GitHub

[![Website Thumbnail](thumbnail.png)](http://mepc.netlify.app)

Este es el sitio web para el Movimiento Estudiantil por la Psicología Científica (MEPC), construido con Hugo y hosteado con Netlify. Podés editarlo directamente en un navegador a través de GitHub (no recomendado) o tenés dos opciones para editar y ver lo que editas localmente antes de actualizar el master branch: 

Si sos un usuario de R y te gusta trabajar con RStudio (la mejor opción para usuarios de Windows), necesitás:

1. Instalar R y R Studio + el paquete blogdown
2. Abrir R Studio, luego ir al Menu > New Project... > Version Control > Git
- URL del repositorio: git clone https://github.com/mepc-website/mepc.git
- Nombre de directorio del proyecto: MEPC (o el que quieras).
- Crear proyecto como un subdirectorio de: clickeá Browse y decidí donde querés ponerlo.
3. Antes de editar, intentá correrlo localmente usando el Addins blogdown en RStudio.

Para editarlo localmente, necesitarás:

1. Clone/fork este GitHub repo: git clone https://github.com/mepc-website/mepc.git en una ventana de terminal
2. Asegurarte de que estás adentro de MEPC/dir (cd MEPC), luego clonar el submodulo para el tema: git submodule update --init --recursive --remote
3. Si Hugo no está instalado, seguí los siguientes pasos en su documentación para instalarlo: https://gohugo.io/getting-started/installing/
4. Para correr el sitio web localmente, asegurate que aún estás en MEPC/dir y tipeá hugo serve -D en tu terminal.
- La opción -D es para servir el sitio web incluyendo draft .md files.

## Agradecimientos

Esta página web fue resultado de la inspiración producto de dos organizaciones construidas con Hugo y blogdown: [MetaDocencia](https://metadocencia.netlify.app/) y [FORRT](https://forrt.org/).


