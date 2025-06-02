# Тестування працездатності системи



## Передумови 

### 1 - Встановити залежності проекту:

```bash
pip install -r requirements.txt
```

### 2 - Запустити сервер:
```bash
uvicorn app.main:app --reload 
```

## Тестування функціонування сервісів

### GET: Отримує конкретну роль із бази даних за її ID
<img src="./test/TestGet.png" alt="GET: Отримує конкретну роль із бази даних за її ID" width="100%"/>

### GET: Отримує один дозвіл з бази даних за його ID
<img src="./test/TestGet1.png" alt="Отримує один дозвіл з бази даних за його ID" width="100%"/>

### POST: Створює нову роль у базі даних
<img src="./test/TestPost.png" alt="POST: Створює нову роль у базі даних" width="100%"/>

### PUT: Оновлює існуючу роль у базі даних за її ID
<img src="./test/TestPut.png" alt="Оновлює існуючу роль у базі даних за її ID" width="100%"/>

### PUT: Оновлює існуючий дозвіл у базі за його ID
<img src="./test/TestPut1.png" alt="Оновлює існуючий дозвіл у базі за його ID" width="100%"/>

### DELETE: Видаляє роль із бази даних за її унікальним ID
<img src="./test/TestDelete.png" alt="Видаляє роль із бази даних за її унікальним ID" width="100%"/>

### DELETE: Видаляє дозвіл з системи за його ID
<img src="./test/TestDelete1.png" alt="DELETE: Видаляє дозвіл з системи за його ID" width="100%"/>

### POST: Створює новий дозвіл у системі
<img src="./test/TestPost1.png" alt="POST: Створює новий дозвіл у системі" width="100%"/>
