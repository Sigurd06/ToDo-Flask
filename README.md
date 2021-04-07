### Run Application
###### Windows 
    set FLASK_APP=app
    set FLASK_DEBUG=1
    set FLASK_ENV=development
    set FLASK_DATABASE_HOST='localhost'
    set FLASK_DATABASE_PASSWORD='root'
    set FLASK_DATABASE_USER='root'
    set FLASK_DATABASE='todoer'
    flask run

###### Linux & Mac
    export FLASK_APP=app
    export FLASK_DEBUG=1
    export FLASK_ENV=development
    export FLASK_DATABASE_HOST='localhost'
    export FLASK_DATABASE_PASSWORD='root'
    export FLASK_DATABASE_USER='root'
    export FLASK_DATABASE='todoer'
    flask run