# Alpine-Docker

## En la página web de Alpine nos descargamos la versión que queremos. En este caso usaremos la versión Virtual.
![imagen](https://user-images.githubusercontent.com/91874629/172137017-6eb4775f-0ac0-4ff5-ab21-968e2aec648e.png)

![imagen](https://user-images.githubusercontent.com/91874629/172137076-c804e3bf-b712-4ba5-8720-5629105613c0.png)

## Empezamos el setup de Alpine. Primero proporcionamos login con root y después el comando setup-alpine
![imagen](https://user-images.githubusercontent.com/91874629/172137176-c6caed40-3727-472d-a3c1-31756f00e22f.png)


## Para empezar el setup nos pide el teclado que queremos usar. Elegimos el nuestro (en este caso es-cat). En localhost ponemos node1
![imagen](https://user-images.githubusercontent.com/91874629/172137284-3e662b39-1cf4-4566-95bc-830d7a7231f2.png)

##  Realizamos algunos pasos más de configuración
![imagen](https://user-images.githubusercontent.com/91874629/172137379-0bc9705d-b1e8-4d48-a7ba-f1f997505ad5.png)

## Más pasos de configuración
![imagen](https://user-images.githubusercontent.com/91874629/172137469-c0fda0ac-f94f-43e7-aaab-d298e3377a4a.png)

## Realizamos más pasos de configuración
![imagen](https://user-images.githubusercontent.com/91874629/172137553-f7bef83e-724a-4e30-849d-0367eddbdb2c.png)

## Al terminar la configuración reiniciamos el sistema
![imagen](https://user-images.githubusercontent.com/91874629/172137626-e80d8b57-a4d6-49df-b322-3b9d8065e63a.png)

## En la configuración de virtual box cambiamos a Adaptador puente para tener conexión a internet.
![imagen](https://user-images.githubusercontent.com/91874629/172137696-9c9c370c-d921-40ef-b2e5-6150944a53b8.png)

## Iniciamos de nuevo Alpine e instalamos Docker con el comando apk add docker
## luego iniciamos docker con service docker start. Utilizaremos una imagen de Docker Hub para eso ponemos docker pull hello-world
![imagen](https://user-images.githubusercontent.com/91874629/172137795-03f3b663-bb9b-4891-bc04-212e7aae74a8.png)

## $ docker run hello-world nos indica que Docker se ha instalado correctamente
![imagen](https://user-images.githubusercontent.com/91874629/172137845-5cb51bcd-f591-424a-8d2d-b672b849eae7.png)
