# NewsPepper - Aplikacja do zarządzania artykułami

### Opis projektu
**NewsPepper** to aplikacja webowa stworzona w **Django**, umożliwiająca zarządzanie artykułami. Każdy zalogowany użytkownik może:
- Dodawać artykuły
- Edytować swoje artykuły
- Usuwać swoje artykuły
- Przeglądać artykuły innych użytkowników
- Komentować artykuły

Aplikacja powstała w celu przetrenowania **Class-Based Views (CBV) w Django**.

### Technologie
- Python
- Django
- SQLite
- Bootstrap

### Instalacja

1. Sklonuj repozytorium:
```
git clone --branch deploy https://github.com/dmurawski/djangoCBV.git
```
2. Stwórz i aktywuj wirtualne środowisko:
```
python -m venv venv
pip install -r requirements.txt
```
3. Wykonaj migracje i uruchom server developerski
```
python manage.py migrate
python manage.py runserver
```
