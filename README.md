# back_clase_12

En el archivo package.json/scripts/ se ha añadido: "start": "node app.js" para arrancar el servidor con la declaración en la terminal "npm start".

Para ejecutar declaraciones en package.json/scripts/ de palabras no reservadas (ej:"otratarea"), se usa la declaración "npm run otratarea".

En package.json/scripts/ la declaración "dev" lo usan los desarrolladores para hacer pruebas. Por ejemplo, para que se reinicie automáticamente (nodemon).

Se instala nodemon con la declaración "npm i --save-dev nodemon". La parte "--save-dev" aplica para cuando se quieren instalar dependencias de desarrollo.

En packaje.json se crea "devDependencies" donde iran todas las dependencias que se usen como desarrollador. Por ejemplo, nodemon para que se levante el servidor cada vez que haya un cambio, o para tests...

En package.json/scripts/dev se cambia la declaración "node app.js" por "nodemon app.js"



Conforme avanzamos, es recomendable comprobar las cosas que se van instalando. Para ello se usa la declaración "npm list".

Para arrancar el servidor se usa la declaración "npm run dev".

Es recomendable diferenciar en la documentación que para producción arrancar con "npm start" y para desarrollo "npm run dev".

Para trabajar se suele abrir una segunda terminal, de tal modo que en la primera se deja arrancada con nodemon y si se quieren instalar cosas te vas a la segunda.

En el ejemplo de clase, se ha instalado un módulo para que aparezcan los mensajes dentro de un gráfico compuesto por caracteres. Mirar en npmjs.com documentación.
