![Captura](https://user-images.githubusercontent.com/68760595/130308789-57a431ea-94d7-4cdb-896d-473e94b135bf.PNG)

# Pasos:

*en caso de problemas CORS, desde terminal: 

```
npm install cors
```

1. instalar node modules 

```
npm install
```

2. tener instalado node 

```
npm install node
```

3. consultar version node 

```
node --v
```

4. levantar servidor node index.js (dejar escuchando en el puerto)

5. descargar postman desktop 

:link:  https://www.postman.com/

6. en postman acceder al endpoint configurado 

:link:  http://localhost:3000/api/login

7. opciones Postman método POST, en body opción raw y formato JSON

8. Escribir en Body 

```
{ 
	"email" : "Sincere@april.biz", 
	"password" : "secret" 
}
```
   - Estos datos de usuarios los obtenemos de la carpeta db, archivo user.json la contraseña es: secret
     - Obtenemos un JWT

9. revisar información JWT 

:link:  https://jwt.io/

10. Una vez obtenido el JWT ingresar email y password en el servidor local 

:link:  htttp://localhost:3000/desafio-instafake

```
email : "Sincere@april.biz", 
password : "secret"
```

11. aparecerán fotos con su autor, al final de la página aparece un botón para cargar más fotos

12. detener servidor, desde terminal

```
ctrl + c
y
```
![Captura](https://user-images.githubusercontent.com/68760595/130308839-f5130cc1-04fc-4487-9bae-18643dc0b00a.PNG)
