# Django Example

Based on [Django documentation](https://docs.djangoproject.com/en/4.1/intro/tutorial01/).

## To Run

    python manage.py runserver

## To Run Tests

    python manage.py test

To test only the `Polls` app:

    python manage.py test polls

## To Get Code Coverage

    pip install coverage
    coverage run --source='.' manage.py test
    coverage report
