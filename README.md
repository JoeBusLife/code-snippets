# code-snippets

### Git
- git init
- git status
- git add .
- git commit -m submit1
- git remote add origin https://githu...
- git push -u origin main  
- git pull origin main --rebase  
- git rm -r --cached <folder>

### Other
- cd school/python/
- touch .gitignore app.py other.py
- code .
- explorer.exe .
- python3 -m unittest test_flask.py
- python3 -m venv venv
- source venv/bin/activate
- deactivate
- pip install -r requirements.txt
- pip freeze > requirements.txt
- sudo service postgresql status
- sudo service postgresql start
- createdb blogly_test
- python seed.py
- flask run --port 8050   

### Flask
- request.args: the key/value pairs in the URL query string
- request.form: the key/value pairs in the body, from a HTML post form, or JavaScript request that isn't JSON encoded
- request.files: the files in the body, which Flask keeps separate from form. HTML forms must use enctype=multipart/form-data or files will not be uploaded.
- request.values: combined args and form, preferring args if keys overlap
- request.json: parsed JSON data. The request must have the application/json content type, or use request.get_json(force=True) to ignore the content type.
  
### Node
- npm init
- npm i
  npm i --save-dev supertest
- node <file>
- nodemon <file>
- nodemon --inspect <file>
