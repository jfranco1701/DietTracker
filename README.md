# DietTracker

DietTracker is an application that is used to track a user's daily intake of food and beverages. DietTracker allows the user to search for nutrition information in the USDA Food Composition Databases or manually enter values for items.  Commonly consumed items can be added to a list of favorites which allows for quicker entry of them in the future.  The application also allows the user to track their current weight.  The user is able to view several graphs which allows for the easy review of their weight loss over time.   

DietTracker was developed using Angular on the frontend, Django for the backend API and PostgreSQL for the database. 

## Installation
```bash
docker-build .
docker-compose run django bash
python manage.py migrate
python manage.py createsuperuser --username admin --email admin
```

## Getting Started
To run DietTracker,
```bash
docker-compose up
```

# License
MIT License

Copyright (c) 2018 Joe Franco

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
