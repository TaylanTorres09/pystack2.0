# Projeto feito durante a semana PYSTACK WEEK 2.0,

### Para criar o ambiente virtual
* Linux
  python3 -m venv venv
* Windows
  python -m venv venv
  
### Para ativar
* Linux
  source venv/bin/activate
* Windows
  venv/Scripts/Activate ~ caso não funcione.
  
  Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
  venv/Scripts/Activate.ps1
  
### Bibliotecas necessárias
* pip install django
* pip install pillow

### Configuração de arquivos estáticos
STATIC_URL = '/static/'
STATICFILES_DIRS = (os.path.join(BASE_DIR, 'templates/static'),)
STATIC_ROOT = os.path.join('static')
MEDIA_ROOT = os.path.join(BASE_DIR, 'media')
MEDIA_URL = '/media/'


  
