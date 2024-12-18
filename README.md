# PoCAks 
![Static Badge](https://img.shields.io/badge/status-develop-green) 
![Static Badge](https://img.shields.io/badge/dev-.NET%208%20C%23-%23512BD4?logo=dotnet)
![Static Badge](https://img.shields.io/badge/platform-AKS-%23326CE5?logo=kubernetes)

Proyectos de prueba de concepto para desplegar en AKS de Azure

## Índice

- [Estado del proyecto](#estado-del-proyecto)
- [Instalación y Uso](#instalación-y-uso)
- [TecnologÍas Aplicadas](#tecnologías-aplicadas)
- [Créditos](#créditos)
- [Licencia](#licencia)
- [Funcionalidad](#funcionalidad)
- [Estructura de Carpetas](#estructura-de-carpetas)

## Estado del proyecto
🚧 Proyecto en construcción 🚧

## Instalación y Uso
A continuación se indica lo necesario para instalar el proyecto (pre-requisitos) en el entorno de desarrollo y poder utilizarlo adecuadamente.

Inicialmente se necesita Visual Studio 2022 y una suscripción de Azure habilitada.

El proyecto está diseñado para que el código sea almacenado en GitHub y se asocie con una pipeline de Azure.

## TecnologÍas Aplicadas
Los proyecetos principales son WebAPIs simulando microservicios que se comunicarán mediante HTTP REST y AMQP.

Este proyecto intenta aprender e interiorizar las recomendaciones y buenas prÁcticas expuestas en el libro [".NET Microservices: Arqchitecture for Containerized .NET Applications"](https://learn.microsoft.com/es-es/dotnet/architecture/microservices/).
Existe un proyecto ejemplo creado por los autores del libro en [GitHub](https://github.com/dotnet/eShop).

### CodeFirst
Esta soluciÓn aplica el acercamiento de 'CodeFirst' para la creaciÓn y gestiÓn de base de datos, cuando sea necesario el almacenamiento de datos.


## Créditos
No se preveen colaboraciones activas, pero si que está el proyecto abierto a ello, si estáis interesados podeís poneros en contacto con el propietario del repositorio.
Las librerías de terceros se irán publicando a medida que se utilicen.

## Licencia
No tiene licencia por el momento

## Funcionalidad
Por definir

## Estructura de Carpetas
Un ejemplo:

```
/PoCAks
    /src
        /ProyectoWebApi1
            ProyectoWebApi1.csproj
        /ProyectoWebApi1.Tests
            UnitTests/
            IntegrationTests/
            ProyectoWebApi1.Tests.csproj
    /docs
    /tools
    /build
    .gitignore
    README.md
```

- **docs/**: Documentación del proyecto.
- **tools/**: Scripts y herramientas útiles. Por ejemplo, colecciones Postman.
- **build/**: Archivos y configuraciones relacionadas con el proceso de construcción.