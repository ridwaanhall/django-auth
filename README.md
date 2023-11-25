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

1. Signup
#### Endpoint: `POST /signup`
#### Request body:
    {
        "username": "ridwaanhall",
        "password": "12345678",
        "email": "test@test.com"
    }
#### Example Response:
    {
    "token": ""24581de39310e6c68a23e95edb3ec06de78331ec,
    "user": {
        "id": 2,
        "username": "ridwaanhall1",
        "password": "12345678",
        "email": "test@test.com"
    }
}

2. Login
#### Endpoint: `POST /login`
#### Request body:
    {
        "username": "ridwaanhall",
        "password": "12345678"
    }

4. Testing Token