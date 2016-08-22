# django-planet-demo
[django-planet](https://github.com/matagus/django-planet-demo) demo project using Django 1.8.x and Python 3.5+

## Installation:

 * Clone this project: `git clone git@github.com:matagus/django-planet-demo.git`
 * `cd django-planet-demo`
 * Create a virtual environment and get into it
 * Install requirements `pip install -r requirements.txt`
 * `python manage.py migrate`
 * `python manage.py runserver`
 * Load some rss/atom feeds: `python manage.py planet_add_feed http://feeds.bbci.co.uk/news/rss.xml`
 * Point your browser to [http://localhost:8000](http://localhost:8000)
