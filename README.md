# Flaskr
As seen on https://flask.palletsprojects.com/tutorial/

### Setup
```
~/github/Flaskr $  source bin/activate

(Flaskr) ~/github/Flaskr $  export FLASK_APP=flaskr && export FLASK_ENV=development

(Flaskr) ~/github/Flaskr $  pip3 install flask
...

(Flaskr) ~/github/Flaskr $  flask init-db

(Flaskr) ~/github/Flaskr $  flask run --host=0.0.0.0
 * Serving Flask app "flaskr" (lazy loading)
 * Environment: development
 * Debug mode: on
 * Running on http://0.0.0.0:5000/ (Press CTRL+C to quit)
 * Restarting with stat
 * Debugger is active!
 * Debugger PIN: ***
192.168.1.1 - - [13/Jan/2021 17:11:25] "GET / HTTP/1.1" 200 -
192.168.1.1 - - [13/Jan/2021 17:11:26] "GET /about HTTP/1.1" 200 -
192.168.1.1 - - [13/Jan/2021 17:11:27] "GET /create HTTP/1.1" 200 -
192.168.1.1 - - [13/Jan/2021 17:11:41] "POST /create HTTP/1.1" 302 -
```
