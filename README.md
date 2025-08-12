# prueba-tecnica-hubpago

# Archivos .zip incluidos 

1- Solución Frontend ANGULAR "OrdenesWebApp.zip"

2- Solución Backend ASP.NET "WebApiOrdenes.zip"

3- Solución Procesar Ordenes de Compra Spring Boot "pago-api.zip"

4- Solución proceso APACHE CAMEL "camel-demo.zip"
  
5- Se adjunta "Capturas demo.zip" con la evidencia


# Api .NET backend:
Descomprimir, abrir con VisualStudio 2022 community Edition
Compilar, arrancar y probar con 
GET Method https://localhost:44322/ordenes para listar
POST Method https://localhost:44322/ordenes para crear 


# Angular frontend: 
Descargar, descomprimir 
npm install
ng serve -o (ya viene proxy solucionado en package.json) 
navegar en http://localhost:4200 
consumira API .NET


# Proceso de Ordenes de compra Spring Boot

Descargar, descomprimir, compilar y ejecutar como proyecto springboot 
mvn clean install
mvn spring-boot:run
probar con postman POST Method http://localhost:8080/procesar-orden
Body request 
{
  "cliente": "Felipe Diaz",
  "fecha": "2025-08-12T10:30:00",
  "productos": [
    { "nombre": "Teclado", "cantidad": 2, "precioUnitario": 19990 },
    { "nombre": "Teclado", "cantidad": 2, "precioUnitario": 19990 },
    { "nombre": "Teclado", "cantidad": 2, "precioUnitario": 19990 },
    { "nombre": "Teclado", "cantidad": 2, "precioUnitario": 19990 },
    { "nombre": "Teclado", "cantidad": 2, "precioUnitario": 19990 },
    { "nombre": "Mouse", "cantidad": 1, "precioUnitario": 12990 }
  ]
}


# Integracion con APACHE CAMEL

Descar y descomprimir camel-demo.zip, compilar ejecutar y probar con POSTMAN
link simple http://127.0.0.1:8082/hola


# Todos los fuentes de esta tarea 

 - FRONT  https://github.com/zaidepilef/OrdenesWebApp.git
 - BACK  https://github.com/zaidepilef/WebApiOrdenes.git
 - PROCESO ORDEN  https://github.com/zaidepilef/pago-api.git
 - INTEGRACION APACHE CAMEL  https://github.com/zaidepilef/camel-demo.git

















