# ProductsRESTfulAPI
Simple products API using Python, Flask, SQLite, SQL Alchemy and Marshmallow!

```Python
# Activate venv (Windows)
$ env/Scripts/activate

# Install all Dependencies
$ pip install -r requirements.txt

# Create SQLite DB
$ python
>> from app import db
>> db.create_all()
>> exit()

# Run server
python app.py
```

<h2> Endpoints </h2>
<ul> 
<li>GET /product</li>
<li>GET /product/:id</li>
<li>POST /product</li>
<li>PUT /product/:id</li>
<li>DELETE /product/:id
</ul>
