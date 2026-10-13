## Запуск копии на своём компьютере
1. git clone https://github.com/YekaterinaDol/Trevel_Match.git
2. cd Trevel_Match
3. python -m venv .venv
4. .venv\Scripts\activate        (Mac/Linux: source .venv/bin/activate)
5. pip install -r requirements.txt
6. python manage.py migrate
7. python manage.py runserver
8. Откройте http://127.0.0.1:8000 и http://127.0.0.1:8000/health/
