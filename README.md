# **Tasks API (на Django + DRF)**

### **Установка и запуск**  

**Установить зависимости:**  
```bash
pip install -r requirements.txt
```

**Сделать миграции:**  
```bash
python3 manage.py makemigrations api
python3 manage.py migrate
```

**Запустить сервер**  
```bash
python3 manage.py runserver
```

**Проверить API в браузере:**  
```
http://127.0.0.1:8000/api/tasks/
```

---

### **Доступные эндпоинты**  

| Метод  | URL            | Описание                |
|--------|----------------|-------------------------|
| `GET`  | `/api/tasks/`  | Получить список задач   |
| `POST` | `/api/tasks/`  | Создать новую задачу    |


