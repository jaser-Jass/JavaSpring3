команда для получения всех пользователей:

 bash:  curl -X GET http://localhost:8080/api/users

команда для создания нового пользователя: 

 bash:  curl -X POST http://localhost:8080/api/users -H "Content-Type: application/json" -d "{\"name\": \"Иван Иванов\", \"email\": \"ivanovivan@example.com\"}"


