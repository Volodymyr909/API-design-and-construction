# RESTful API with Node.js & Express.js

##  Опис проєкту
Цей проєкт реалізує RESTful API для управління користувачами.

##  Запуск проєкту
1. **Встановіть залежності**  
   ```sh
   npm install
   ```
2. **Запустіть сервер**  
   ```sh
   npm start
   ```
3. **API доступний за адресою:**  
   ```
   http://localhost:5000/api/users
   ```

##  API Маршрути
| Метод | URL | Опис |
|--------|--------------------------------|-----------------------------|
| **GET** | `/api/users` | Отримати список всіх користувачів |
| **POST** | `/api/users` | Додати нового користувача |
| **PATCH** | `/api/users/:id` | Оновити користувача |
| **DELETE** | `/api/users/:id` | Видалити користувача |

##  Документація API
[Postman API Documentation](https://documenter.getpostman.com/view/41786201/2sAYX5MNkb)

##  Автор
- **Споденюк Володимир**
- **Email:** ipz232_svv@student.ztu.edu.ua
