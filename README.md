## Запуск копии на своём компьютере

1. git clone https://github.com/JasmineStp/test-site
2. cd test-site
3. python -m venv .venv
4. .venv\Scripts\activate
   *(для Mac/Linux: source .venv/bin/activate)*
5. pip install -r requirements.txt
6. python manage.py migrate
7. python manage.py runserver
8. Откройте в браузере: http://127.0.0.1:8000 и http://127.0.0.1:8000/health/
