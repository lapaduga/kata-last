1. Регистрация пользователя
POST https://blog.kata.academy/api/users

Body: 
{
  "user": {
    "username": "lapaduga",
    "email": "email@mail.com",
    "password": "password"
  }
}

2. Аутентификация
POST https://blog.kata.academy/api/users/login

Body:
{
  "user": {
    "email": "email@mail.com",
    "password": "password"
  }
}

3. Получение информации о пользователе
GET https://blog.kata.academy/api/user

В блоке Headers отправляю
Authorization: Token eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYyZTdjMGEyM2NmNzA1MWIwMDgyOTBlYSIsInVzZXJuYW1lIjoibGFwYWR1Z2EiLCJleHAiOjE2NjQ1NDA3NTksImlhdCI6MTY1OTM1Njc1OX0.QRIB8gy93IL_XvEJ8GrbWkmIerndOcJ4y46_hlOAQPY