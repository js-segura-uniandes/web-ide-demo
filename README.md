# Estructura del proyecto

Lo primero que se debe hacer es ubicarse en la rama "develop" del repositorio. Las imágenes del lenguaje ubicuo y de los diagramas de context mapper se pueden encontrar en la carpeta "/src/main/cml/entregas-alpes/". Alli se encuentra 1 diagrama para el escenario TO-BE, otra del escenario AS-IS y la imagen del lenguaje ubicuo. La siguiente es la estructura del proyecto:

```console
── LICENSE
├── README.md
├── build.gradle
├── gradle
│   └── wrapper
│       ├── gradle-wrapper.jar
│       └── gradle-wrapper.properties
├── gradle.properties
├── gradlew
├── gradlew.bat
├── settings.gradle
└── src
    └── main
        ├── cml
        │   ├── demo.cml
        │   └── entregas-alpes
        │       ├── Lenguaje ubicuo.jpg
        │       ├── entregas-context-diagram-as-is to-be.cml
        │       ├── entregas-context-diagram-as-is%20to-be_ContextMap.png
        │       ├── entregas-context-diagram-as-is.cml
        │       └── entregas-context-diagram-as-is_ContextMap.png
        └── resources
            └── freemarker-templates
                └── JDL.ftl
```

# Fragmentos de código
Los fragmentos de código (.cml) de los diagramas los puede encontrar en la carpeta "/src/main/cml/entregas-alpes/".Existe 1 diagrama para el escenario As-IS y otro para el escenario TO-BE.
- Dominios y subdominios: /src/main/cml/entregas-alpes/entregas-context-diagram-as-is.cml y src/main/cml/entregas-alpes/entregas-context-diagram-as-is to-be.cml
- Contextos acotados y sus relaciones: /src/main/cml/entregas-alpes/entregas-context-diagram-as-is.cml y src/main/cml/entregas-alpes/entregas-context-diagram-as-is to-be.cml

# gitpod.yml
Este archivo lo puede encontrar en la raiz del proyecto. Adicionalmente esta es la URL del gitpod https://gitpod.io/#https://github.com/js-segura-uniandes/web-ide-demo 
