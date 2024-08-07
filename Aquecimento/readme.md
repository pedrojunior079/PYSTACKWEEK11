# Pystack Week 11.0 
:computer: Criar um ambiente virtual para o python
    # Linux
      python3 -m venv venv
      # Windows
        python -m venv venv

:computer: Após a criação do venv vamos ativa-lo:
#Ativar
   # Linux
     source venv/bin/activate
     # Windows
       venv\Scripts\Activate
       # Caso algum comando retorne um erro de permissão execute o código e tente novamente:
         Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned

:computer: Instalando o servidor Django dentro do ambiente virtual
:computer: pip install django
# Atualize o instalador do pip do python caso esteja desatualiazado  
:computer:python.exe -m pip install --upgrade pip
:computer: python manage.py makemigrations
:computer: python manage.py migrate  
continua em  55:11min