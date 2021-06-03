# webpack
herramienta para desplegar proyectos

al iniciar un nuevo repositorio para webpack
npm init -y

entrar a la carpeta del proyecto

instalar webpack 
npm install webpack webpack-cli -D

instalar de forma global
npx webpack

activar modo de desarrollo
npx webpack --mode development

activar modo de produccion
npx webpack --mode production

-----------------------------------------------------------------------

luego de configurar el webpack.config.js hay que ejecutar para preparar el codigo de configuracion:
npx webpack --mode production --config webpack.config.js

o podemos incluir "build": "webpack --mode production" en el escript que esta en package.json para hacerlo automaticamente y lo ejecutamos con npm run build