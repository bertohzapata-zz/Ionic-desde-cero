

# Instalación de Ionic desde cero
Este es un proyecto de ejemplo que sirve como guía para la configuración de nuestro entorno para desarrollar aplicaciones con Ionic

## Instalat Nodejs

- revisar que la ruta PATH
```
npm --version
```

```
npm -v
```

En caso de problemas
- Habilitar ejecución de scripts
https://stackoverflow.com/questions/27864040/fixing-npm-path-in-windows-8-and-10
- Agregar npm a la variable PATH 
https://protegermipc.net/2018/11/22/permitir-la-ejecucion-de-scripts-powershell-en-windows-10/

## Instalar Angular
```
npm install -g @angular/cli 
```


Validar si la instalación fue correcta
```
ng --version
```

```
ng -v
```
En caso de problemas:

- Agregar ng a la variable PATH
https://living-sun.com/es/angular/62197-39ng39-is-not-recognized-as-an-internal-or-external-command-angular-angular-cli.html


## Instalar Ionic

```
npm install -g @ionic/cli
```

Validar la instalación
```
ionic --version
```

```
ng -v
```


En caso de problemas con instalaciones o actualizaciones corruptas, desinstalar y volver a instalar la herramienta.

Ejemplo:
```
npm uninstall -g @angular/cli
npm install -g @angular/cli
```
- En caso de limpiar caché
```
npm cache clear --force
```


## Primera app con Ionic
```
ionic start myApp tabs
```
Entrar al proyecto y arrancar la aplicación
```
cd myApp 
ionic serve
```

En caso de problemas
```
npm install --global --production windows-build-tools
```
```
npm install --global node-gyp
```
