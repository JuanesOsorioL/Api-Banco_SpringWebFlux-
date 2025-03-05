# Api-Banco_SpringWebFlux-
# Estructura del Proyecto en Spring Boot Reactivo con Clean Architecture

📂 Proyecto

┣ 📂 domain → (Capa de Dominio)
┃ ┣ 📂 model → Entidades del dominio
┃ ┣ 📂 usecase → Casos de uso

┃

┣ 📂 application → (Casos de Uso)
┃ ┣ 📂 service → Implementaciones de lógica de negocio

┃

┣ 📂 infrastructure → (Infraestructura y Adaptadores)
┃ ┣ 📂 repository → Implementación de acceso a datos (MongoDB)
┃ ┣ 📂 rest → Controladores REST
┃ ┣ 📂 exception → Manejador de excepciones

┃

┣ 📂 config → (Configuraciones generales como MongoDB, seguridad, etc.)
