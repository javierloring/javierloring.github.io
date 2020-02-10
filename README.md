<p align = "center">
    <a href="https://github.com/yiisoft" target=" _blank">
        <img src = "https://avatars0.githubusercontent.com/u/993323" height = "100px">
    </a>
    <h1 align = "center"> Plantilla de proyecto avanzado Yii 2 </h1>
    <br>
</p>
Yii 2 Advanced Project Template es una aplicación esqueleto [Yii 2] (http://www.yiiframework.com/) mejor para
desarrollando aplicaciones web complejas con múltiples niveles.
La plantilla incluye tres niveles: front end, back end y consola, cada uno de los cuales
es una aplicación separada de Yii.
La plantilla está diseñada para funcionar en un entorno de desarrollo de equipo. Es compatible
desplegar la aplicación en diferentes entornos.
La documentación está en [docs / guide / README.md] (docs / guide / README.md).
[! [Última versión estable] (https://img.shields.io/packagist/v/yiisoft/yii2-app-advanced.svg)] (https://packagist.org/packages/yiisoft/yii2-app- avanzado)
[! [Descargas totales] (https://img.shields.io/packagist/dt/yiisoft/yii2-app-advanced.svg)] (https://packagist.org/packages/yiisoft/yii2-app-advanced )
[! [Estado de compilación] (https://travis-ci.org/yiisoft/yii2-app-advanced.svg?branch=master)] (https://travis-ci.org/yiisoft/yii2-app-advanced )
ESTRUCTURA DE DIRECTORIOS
-------------------
`` `
común
    config / contiene configuraciones compartidas
    mail / contiene ver archivos para correos electrónicos
    modelos / contiene clases de modelos utilizados tanto en backend como en frontend
    pruebas / contiene pruebas para clases comunes    
consola
    config / contiene configuraciones de consola
    controladores / contiene controladores de consola (comandos)
    migraciones / contiene migraciones de bases de datos
    modelos / contiene clases de modelos específicos de la consola
    tiempo de ejecución / contiene archivos generados durante el tiempo de ejecución
backend
    activos / contiene activos de aplicaciones como JavaScript y CSS
    config / contiene configuraciones de backend
    controladores / contiene clases de controladores web
    modelos / contiene clases de modelos específicos de backend
    tiempo de ejecución / contiene archivos generados durante el tiempo de ejecución
    pruebas / contiene pruebas para la aplicación de fondo    
    vistas / contiene archivos de vista para la aplicación web
    web / contiene el script de entrada y los recursos web
Interfaz
    activos / contiene activos de aplicaciones como JavaScript y CSS
    config / contiene configuraciones frontend
    controladores / contiene clases de controladores web
    modelos / contiene clases de modelos específicos de frontend
    tiempo de ejecución / contiene archivos generados durante el tiempo de ejecución
    pruebas / contiene pruebas para la aplicación frontend
    vistas / contiene archivos de vista para la aplicación web
    web / contiene el script de entrada y los recursos web
    widgets / contiene widgets frontend
proveedor / contiene paquetes de terceros dependientes
entornos / contiene anulaciones basadas en el entorno
`` `
