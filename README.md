## plaid- with -django - celery
go to : https://github.com/brahada/plaid-example/tree/master/plaid-django-celery


## plaid-example- without - django
pip install -r requirements.txt

### keys
(fill for ? by going to sandbox sit : https://dashboard.plaid.com/overview/sandbox)

PLAID_CLIENT_ID=? \
PLAID_SECRET=? \
PLAID_PRODUCTS=? \
PLAID_COUNTRY_CODES=US \
PLAID_ENV=sandbox \
python server.py

open http://localhost:8000

