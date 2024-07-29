# API REST | Lambda + DynamoDB 

![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge&logo=amazon-dynamodb&logoColor=white)
![API Gateway](https://img.shields.io/badge/API_Gateway-FF4F8B?style=for-the-badge&logo=amazon-api-gateway&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=for-the-badge&logo=aws-lambda&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)


## Descripción

LambdaDynamoAPI es un proyecto que implementa una REST API utilizando AWS Lambda y API Gateway. La API permite realizar operaciones CRUD en una tabla de DynamoDB, proporcionando una solución backend escalable y rentable.

## Arquitectura

![image](https://github.com/user-attachments/assets/6df68431-08a7-431e-a022-9be4429be809)


- **AWS Lambda**: Función que maneja las solicitudes HTTP.
- **API Gateway**: Expone los endpoints REST.
- **DynamoDB**: Base de datos NoSQL para almacenar los datos.


## Endpoints
https://izr4mrkrg4.execute-api.us-east-2.amazonaws.com/items

| Método | Endpoint        | Descripción                 |
|--------|-----------------|-----------------------------|
| GET    | /items          | Obtiene todos los ítems     |
| GET    | /items/{id}     | Obtiene un ítem por ID      |
| POST   | /items          | Crea un nuevo ítem          |
| PUT    | /items/{id}     | Actualiza un ítem existente |
| DELETE | /items/{id}     | Elimina un ítem por ID      |

