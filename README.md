#### Create virtual env
`mkdir django-rest-api`
`cd django-rest-api`
`python3.10 -m venv venv`  (`virtualenv venv -p python3` / `python3 -m virtualenv venv`)

#### Activate virtula env
`source venv/bin/activate`

#### Creating the requirement file and install all the pacakages
create the file as `requirements.txt`
then run `pip install -r requirements.txt`
pip upgrade if want, `pip install --upgrade pip`

#### Product table data insert using python shell
`python manage.py shell`
`from products.models import Product`
`Product.objects.create(title="Hello world again", content="this is amazing", price="20.00")`