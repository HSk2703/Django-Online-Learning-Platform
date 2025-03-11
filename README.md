# Django Online Learning Platform

This project is a **comprehensive online learning platform** developed using Django, aiming to provide users with access to a variety of courses, interactive lessons, and a seamless learning experience.

## Features

- **Course Management** – Administrators can create, update, and delete courses.
- **User Enrollment** – Users can enroll in courses and track their progress.
- **Assessments** – Incorporates quizzes and assignments to evaluate user understanding.
- **Discussion Forums** – Facilitates interaction between students and instructors.

## Technologies Used

- **Django** – Backend framework for robust web applications.
- **HTML5 & CSS3** – Structure and styling of web pages.
- **JavaScript** – Interactive elements and client-side logic.
- **SQLite** – Default database for development and testing.

## Project Structure

```
Django-Online-Learning-Platform/
├── myproject/          # Main project settings and configurations
├── onlinecourse/       # Core application handling courses and assessments
├── static/             # Static files (CSS, JavaScript, images)
├── templates/          # HTML templates
├── db.sqlite3          # SQLite database
├── manage.py           # Django management script
├── requirements.txt    # Project dependencies
├── runtime.txt         # Python runtime environment
```

## Getting Started

To set up the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/HSk2703/Django-Online-Learning-Platform.git
cd Django-Online-Learning-Platform
```

### 2. Create and Activate a Virtual Environment

```bash
python -m venv env
```

#### On Windows:
```bash
env\Scripts\activate
```

#### On macOS/Linux:
```bash
source env/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Apply Migrations

```bash
python manage.py migrate
```

### 5. Run the Development Server

```bash
python manage.py runserver
```

### 6. Access the Application

Open your web browser and navigate to:

👉 [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

## Contributing

Contributions are welcome! To contribute:

1. **Fork the repository**.
2. **Create a new branch** for your feature or bug fix.
3. **Commit your changes** with clear and descriptive messages.
4. **Push your changes** to your forked repository.
5. **Submit a pull request** detailing your changes.

## License

This project is licensed under the **Apache-2.0 License**. See the `LICENSE` file for more information.

