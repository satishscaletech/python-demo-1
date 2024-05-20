##Initialize virtual environment
source fastapienv/bin/activate

##database access
sqlite3 todos.db
.schema

##Generate random string
openssl rand -hex 32

##Install postgresql package
pip install psycopg2-binary

##Install alembic for database migration
pip install alembic

##Create Requirement files
pip3 freeze > requirements.txt

##Install pip dependency
pip install -r requirements.txt
