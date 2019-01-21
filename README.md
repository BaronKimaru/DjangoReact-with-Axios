### DjangoReact-with-Axios
> Encases use of `Django` with `Djangorrestframework`  as the backend whilst `React` is utilised as the frontend.
Requirements:
Django
Djangorestframework
node & npm

STEPS INVOLVED: 
[x] mkdir djangoreact && cd djangoreact
[x] Open vscode with this command in your cmd `code .` then now work from vscode terminal
[x] mkdir backend && mkdir frontend && cd backend
[x] virtualenv venv then activate(Windows: `cd venv/scripts` then `activate`, Linux: `source/bin/activate` )
[x] pip install django djangorestframework pylint pep8 autopep8 
[x] `.vscode` folder created in backend folder(to ensure Linting is done only on py files & not frontend .js files)
[x] create a settings.json file to vs code Linting, pep8 & autopep as well as pointing to relevant paths for both python and venv.
[x] run `django-admin startproject djangorreact`
[x] change the root 'djangorreact' name to 'src'
