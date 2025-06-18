# 🗳️ My First Polls App

A beginner-friendly Django web app for creating and voting on polls.  
[Live on GitHub &rarr;](https://github.com/gsri-18/My_First_Polls_App/tree/main/thath/thath)

---

## 🚩 Features

- List all available polls
- Vote for your favorite choice
- View poll results instantly
- Admin interface for poll management
- Clean, minimal UI

---

## 🚀 Quick Start

1. **Clone the repository**
    ```bash
    git clone https://github.com/gsri-18/My_First_Polls_App.git
    cd My_First_Polls_App/thath
    ```

2. **Set up a virtual environment**
    ```bash
    python3 -m venv kshetram
    source kshetram/bin/activate
    ```

3. **Install dependencies**
    ```bash
    pip install django
    ```

4. **Apply migrations**
    ```bash
    python manage.py migrate
    ```

5. **Create a superuser (optional)**
    ```bash
    python manage.py createsuperuser
    ```

6. **Run the development server**
    ```bash
    python manage.py runserver
    ```

7. **Visit the app**
    ```
    http://127.0.0.1:8000/polls/
    ```

---

## 🗂️ Project Structure

```
My_First_Polls_App/
└── thath/
    ├── manage.py
    ├── db.sqlite3
    ├── polls/
    │   ├── migrations/
    │   ├── templates/
    │   │   └── polls/
    │   │       ├── index.html
    │   │       ├── detail.html
    │   │       └── results.html
    │   ├── models.py
    │   ├── views.py
    │   ├── urls.py
    │   └── ...
    └── thath/
        ├── settings.py
        ├── urls.py
        └── ...
```

---

## 🛠️ Customization

- Add/edit polls and choices via the [Django admin](http://127.0.0.1:8000/admin/)
- Customize templates in `polls/templates/polls/`

---

## 🤝 Contributing

Contributions and suggestions are welcome!  
Open an issue or submit a pull request.

---

## 📄 License

MIT License

---

> Made with ❤️ using [Django](https://www.djangoproject.com/)