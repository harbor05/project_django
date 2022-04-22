# Project_Django

Production server Live [here]()  
Development server Live [here]()

</br>

## Table of Contents

- [Meta Information](#Meta-Information)
- [Features](#Features)
- [Project Structure](#Project-structure)
- [Getting Started](#Getting-Started)
- [Known Issues](#Known-Issues)
- [Docs](#Docs)

</br>

## Meta Information

- Django
- Stack
  - Django Rest Framework
- Auth
  - Google OAuth

</br>

## Features

- Django Init

</br>

## Project Structure

```bash
├── .venv
├── website/
│   └── settings/
└──
```

</br>

## Getting Started

### Starting Command

```bash
# Start venv
source .venv/bin/activate

# End venv
deactivate

# Setup requirements
pip install -r requirements.txt

# Local server
python manage.py runserver --settings=website.settings.development

# Production
python manage.py runserver --settings=website.settings.production
```

---

## Known Issues
