# Django Authentication

## Steps
1. Create virtual environment
   ```bash
   python -m venv venv
   ```

2. Activate virtual environment
   ```bash
   source venv/bin/activate
   ```

3. Install dependencies
   ```bash
   pip install django djangorestframework
   ```

4. Migrate database
   ```bash
   python manage.py migrate
   ```

5. Run on Replit or you can click run on replit
   ```bash
   python manage.py runserver
   ```

## Using Postman

### Signup

#### Endpoint: `POST /signup`
#### Request body:
    {
        "username": "ridwaanhall",
        "password": "12345678",
        "email": "test@test.com"
    }
