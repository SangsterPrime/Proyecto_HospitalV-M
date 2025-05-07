<img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="300"> 

# 🚀 Proyecto Spring Boot + MySQL + JPA
Este proyecto es una API REST construida con Java + Spring Boot, conectada a una base de datos MySQL usando JPA (Java Persistence API) e Hibernate para la persistencia de datos.

Permite manejar operaciones básicas de un servicio web:
GET, POST, PUT y DELETE, ideales para ser probadas con Postman.
Permite manejar operaciones básicas de un servicio web:

- GET (obtener datos)

- POST (crear registros)

- PUT (actualizar registros)

- DELETE (eliminar registros)

Todo esto puede ser probado fácilmente con Postman.

## 💻 Entorno de desarrollo
🛠️ Editor: Visual Studio Code
Con extensiones como:

- Extension Pack for Java

- Spring Boot Tools

- Maven for Java

🐬 Base de Datos: MySQL mediante Laragon

☕ JDK: Java 17 (o tu versión actual)

🌱 Framework: Spring Boot

📦 ORM: Hibernate + JPA

##  📦 Instalación
1. Clona el repositorio:

```bash
git clone https://github.com/SangsterPrime/Proyecto_Hospitalv-M.git
```
2. Asegúrate de tener MySQL corriendo en Laragon.
3. Configura ``application.properties`` en ``src/main/resources:``
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/tu_base_de_datos
spring.datasource.username=root
spring.datasource.password=
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
 ```
4. Abre el proyecto en VS Code y ejecuta con el botón "Run" o desde terminal con:
```bash
./mvnw spring-boot:run
```
## 🧪 Pruebas con Postman
Puedes probar los endpoints fácilmente. Algunos ejemplos genéricos:

- ``GET /api/entidades``

- ``POST /api/entidades``

- ``PUT /api/entidades/{id}``

- ``DELETE /api/entidades/{id}``

## 📁 Estructura del proyecto

```css
src
|
+---main
|   +---java
|   |   \---com
|   |       \---hospital_vm
|   |           \---cl
|   |               \---hospital_vm
|   |                   +---controller
|   |                   +---model
|   |                   +---repository
|   |                   \---service
|   \---resources
|       +---static
|       \---templates
\---test
    \---java
        \---com
            \---hospital_vm
                \---cl
                    \---hospital_vm
```
## ✍️ Autor
Joel Sangster
Estudiante de Ingeniería en Informática
Apasionado por el backend y el desarrollo con Java y Spring Boot.

