<p align="center">
  <a href="https://www.postman.com/"><img src="https://assets.getpostman.com/common-share/postman-logo-horizontal-320x132.png" /></a>
</p>

<br/>

<p align="center">
  <img src="https://img.shields.io/badge/Postman_CLI-orange?style=plastic&logo=Postman&labelColor=black">  
  <a href="https://www.linkedin.com/in/ajvsubotich/"><img src="https://img.shields.io/badge/LinkedIn-%230073b2?style=plastic&logo=LinkedIn&label=Alejandro%20Valdez&labelColor=black"></a></p>

# Requisitos

### Clonar el repositorio 

Este repositorio contiene los archivos .json que poseen las pruebas que se correran en la línea de comando y el archivo con variable de ambiente para la colección.

```bash
 git clone https://github.com/subotich331990/POSTMAN_TEST_API_DOLAR.git
```
### Instalar Postman CLI global en el sistema

  ```bash
  npm install -g @postman/postman-cli
  ```

# Ejecutar las pruebas

Para ejecutar las pruebas de manera local debe abrir la consola (Simbolo del sistema)

<a href=""><img src="https://geekysplace.com/wp-content/uploads/2022/03/cmd1.png" /></a>

Puede posicionarse en el directorio donde se encuentra el archivo DOLAR_API.postman_collection.json:

```bash
cd C:\User\MyLocalFolder\src
```

<strong>ejemplo:</strong> 

<a href=""><img src="https://media.geeksforgeeks.org/wp-content/uploads/20230927124259/Root-Directory.png" /></a>

## Ejecutar el comando para correr las pruebas

```bash
postman collection run ${path}\DOLAR_API.postman_collection.json -e ${path}\API_TEST.postman_environment.json
```

### Resultado de la ejecución

<a href=""><img src="https://media.geeksforgeeks.org/wp-content/uploads/20220519223530/Screenshot20220519213656.png" /></a>




# Créditos

Imagenes utilizadas:

<a src="https://www.geeksforgeeks.org/">https://www.geeksforgeeks.org/</a>


