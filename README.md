# Proyecto CRUD Simple Serverless con VUEJS

Proyecto que utiliza VUEJS 3, como aplicación SPA (Single Page Application), donde 
se utiliza un framework en la vista para aprovechar los recursos del cliente y en combinación 
con el endpoint ubicado en un serverless podemos tener una aplicación donde paguemos por los recursos consumidos.

Para utilizar el cliente, debe configurar la variable ```API_URL``` ubicada en el LocalStorage e indicar
la URL del servicio serverless. Dicha implementación requiere una estructura de Estudiante, con las siguientes propiedades:

```
{
    "matricula" : 1,
    "nombre" : "Carlos Camacho",
    "carrera" : "ITT"
}
```

El ejemplo del serverless en AWS para el siguiente ejemplo está dsponible en el siguiente enlace:
[Aqui](https://github.com/vacax/demo-serverless-aws/blob/master/demo-serveless/src/main/java/edu/pucmm/ia/ds/funciones/FuncionCRUDEstudiante.java )

### Tecnologías utilizadas:

* Vuejs 3.
* Github pages
