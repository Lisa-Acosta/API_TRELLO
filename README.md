# 🧪 Trello API Testing con Postman

Este proyecto contiene una colección de pruebas para la API de Trello usando **Postman**, ideal para validar funcionalidades básicas como creación de tableros, listas, tarjetas, y operaciones CRUD.

---

## 🚀 Requisitos

- [Postman](https://www.postman.com/downloads/)
- Cuenta de [Trello](https://trello.com/)
- Clave de API (API Key)
- Token de usuario

---

## 🔐 Configuración

1. Iniciá sesión en Trello y obtené tus credenciales:
   - **API Key**: [https://trello.com/app-key](https://trello.com/app-key)
   - **Token**: Desde el mismo sitio, clic en *"Token"*

2. En Postman:
   - Creá un **Environment** con las siguientes variables:

| Variable         | Ejemplo                                      |
|------------------|----------------------------------------------|
| `key`            | tu_api_key                                   |
| `token`          | tu_token_de_usuario                          |
| `base_url`       | https://api.trello.com/1                     |
| `board_id`       | (se completa después de crear un tablero)    |
| `list_id`        | (se completa después de crear una lista)     |
| `card_id`        | (se completa después de crear una tarjeta)   |

---

## 📂 Estructura del Proyecto

