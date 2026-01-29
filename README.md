Task Manager Web Application (Flask + PostgreSQL + Docker)

👨‍💻 Autor projektu
Imię i nazwisko: [Anton Roehan]
Numer indeksu: [58827]

Opis projektu:
Projekt polega na stworzeniu webowej aplikacji do zarządzania zadaniami oraz użytkownikami.
Aplikacja posiada interfejs webowy (HTML, CSS, JavaScript), backend napisany w Python Flask oraz bazę danych PostgreSQL.
Całe środowisko uruchamiane jest przy pomocy Docker Compose.

Wykorzystane technologie
Python 3.11
Flask (backend API)
PostgreSQL (baza danych)
HTML, CSS, JavaScript (frontend)
Docker
Docker Compose

✅ Funkcjonalności projektu
1️⃣ Zarządzanie zadaniami (Tasks)
Dodawanie zadań
Wyświetlanie listy zadań
Edytowanie zadań
Usuwanie zadań

2️⃣ Zarządzanie użytkownikami (Users)
Dodawanie użytkowników
Wyświetlanie listy użytkowników
Edytowanie użytkowników
Usuwanie użytkowników

🐳 Kontenery Docker
Projekt uruchamia się w dwóch kontenerach:
backend – aplikacja Flask
db – PostgreSQL

📁 Struktura projektu
task-manager-cloud/
│
├── backend/
│   ├── app.py
│   ├── requirements.txt
│   ├── Dockerfile
│   ├── templates/
│   │   └── index.html
│   └── static/
│       └── style.css
│
├── docker-compose.yml
└── README.md
▶️ Instrukcja uruchomienia projektu

1️⃣ Wymagania
Zainstalowany Docker
Zainstalowany Docker Compose

2️⃣ Klonowanie repozytorium
git clone <URL_REPOZYTORIUM>
cd task-manager-cloud

3️⃣ Uruchomienie aplikacji
docker compose up --build

4️⃣ Otwórz aplikację w przeglądarce
http://localhost:5000

🧪 Testowanie funkcjonalności
📌 Zadania (Tasks)
Wpisz nazwę zadania w polu tekstowym
Kliknij przycisk Add Task
Aby edytować zadanie kliknij Edit
Aby usunąć zadanie kliknij Delete

👤 Użytkownicy (Users)
Wpisz nazwę użytkownika w formularzu
Kliknij Add User
Aby edytować użytkownika kliknij Edit
Aby usunoć użytkownika kliknij Delete

📊 Spełnienie wymagań zaliczeniowych
Wymaganie	Status
Minimum 2 kontenery Docker	✅ Backend + PostgreSQL
Baza danych	PostgreSQL
Minimum 2 funkcjonalności	✅ Tasks + Users
CRUD	✅
Uruchomienie przez docker compose up	✅
README.md	✅

📈 Możliwe rozszerzenia projektu
Status zadania (completed / pending)
Kategorie zadań
Logowanie i rejestracja użytkowników
Trzeci kontener (np. Nginx lub React frontend)
Panel administracyjny

📌 Podsumowanie
Projekt spełnia minimalne wymagania przedmiotu Tworzenie aplikacji dla środowisk chmurowych.
Aplikacja działa poprawnie i uruchamia się jedną komendą Docker Compose.
