# GrowBuddy: Personal Growth & Skill Tracking App

<p align="center">
  <img src="static/images/growbuddy-logo.svg" alt="GrowBuddy Logo" width="200">
</p>

## 🌱 About GrowBuddy

GrowBuddy is a personal growth and skill tracking application designed to help users monitor their progress, set goals, and build consistent habits. With a gamified approach to personal development, GrowBuddy makes it fun and engaging to grow your skills and track your journey.

## ✨ Features

- **Skill Tracking**: Monitor progress across multiple skills with customizable categories
- **Goal Setting**: Create and track daily, weekly, monthly, or one-time goals
- **Journal Entries**: Document your journey with mood tracking and reflections
- **Progress Analytics**: Visualize your growth with charts and insights
- **Achievement System**: Earn badges and level up as you make progress
- **Streak Tracking**: Build consistency with streak counters
- **Dark/Light Mode**: Choose your preferred visual theme

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- pip (Python package manager)
- Virtual environment (recommended)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/growbuddy.git
   cd growbuddy
   ```

2. Create and activate a virtual environment:
   ```bash
   # On Windows
   python -m venv venv
   venv\Scripts\activate
   
   # On macOS/Linux
   python -m venv venv
   source venv/bin/activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Apply migrations:
   ```bash
   python manage.py migrate
   ```

5. Create a superuser:
   ```bash
   python manage.py createsuperuser
   ```

6. Run the development server:
   ```bash
   python manage.py runserver
   ```

7. Visit `http://127.0.0.1:8000/` in your browser to access GrowBuddy

## 📱 App Structure

- **users**: User authentication and profile management
- **skills**: Skill tracking and goal management
- **journal**: Journaling and reflection tools
- **analytics**: Progress tracking and insights
- **core**: Shared functionality across the application

## 🎨 Tech Stack

- **Backend**: Django
- **Database**: SQLite (development) / PostgreSQL (production)
- **Frontend**: HTML, CSS, JavaScript
- **UI Framework**: Bootstrap 5
- **Icons**: Font Awesome
- **Fonts**: Google Fonts (Quicksand, Poppins)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgements

- Font Awesome for icons
- Google Fonts for typography
- Bootstrap team for the UI framework

---

<p align="center">Made with ❤️ for personal growth</p>