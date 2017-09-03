# Django Boilerplate - Simple Ajax Crud

Example used in the blog post [How to Implement CRUD Using Ajax and Json](https://simpleisbetterthancomplex.com/tutorial/2016/11/15/how-to-implement-a-crud-using-ajax-and-json.html)

## Running Locally

Clone the repository::

```bash
git clone https://github.com/scedar/django_boilerplate.git
```

Installing the dependencies::

```bash
pip install -r requirements.txt
```

Set your Google API key in you settings file::

``` python
GEOPOSITION_GOOGLE_MAPS_API_KEY = 'YOUR_API_KEY'
```

API keys may be obtained here: https://developers.google.com/maps/documentation/javascript/get-api-key

If you are still using Django <1.3, you are advised to install `django-staticfiles`_ for static file serving.

Run `sh $ python manage.py makemigrations books`- to create migrations for those changes
Run `sh $ python manage.py migrate` - to apply those changes to the database.

Run `sh $ python manage.py runserver` - to apply those changes to the database.


## References

* [How to Implement CRUD Using Ajax and Json](https://simpleisbetterthancomplex.com/tutorial/2016/11/15/how-to-implement-a-crud-using-ajax-and-json.html)
* [django-geoposition](https://github.com/philippbosch/django-geoposition)


## Authors

* **Ochomo William** - [Scedar Technologies Co.](https://scedar.bitbucket.io/), [ochomoswill](https://ochomoswill.github.io/)


