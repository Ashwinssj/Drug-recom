# Disease Prediction and Drug Recommendation Application

A web-based application built with Django that helps predict diseases based on symptoms and recommends appropriate medications.

## Features

- Disease prediction based on user symptoms
- Drug recommendations for predicted diseases
- User-friendly interface
- Secure authentication system
- Medical history tracking

## Prerequisites

- Python 3.x
- Django
- pip (Python package manager)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Disease-Prediction-and-Drug-Recommendationn-Application.git
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
.\venv\Scripts\activate
```

3. Install required dependencies:
```bash
pip install -r requirements.txt
```

4. Apply database migrations:
```bash
python manage.py migrate
```

5. Create a superuser (admin):
```bash
python manage.py createsuperuser
```

6. Run the development server:
```bash
python manage.py runserver
```

The application will be available at `http://127.0.0.1:8000/`

## Usage

1. Register a new account or login with existing credentials
2. Select symptoms from the provided list
3. Submit for disease prediction
4. View predicted disease and recommended medications
5. Access your medical history through the dashboard

## Admin Access

Access the admin panel at `http://127.0.0.1:8000/admin` using your superuser credentials to:
- Manage users
- Update disease-symptom relationships
- Modify drug recommendations
- View and manage medical records

## Project Structure

```plaintext
├── healthcare/          # Main project directory
├── prediction/         # Disease prediction app
├── users/             # User management app
├── static/            # Static files (CSS, JS, images)
├── templates/         # HTML templates
├── manage.py          # Django management script
└── requirements.txt   # Project dependencies
```

## Contributing

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Django Framework
- Medical data sources
- Contributors and maintainers

## Support

For support, please open an issue in the repository or contact the maintainers.
