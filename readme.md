# DRF Clientes
Gerenciamento de Clientes

## Requisitos
- [Python](https://www.python.org/downloads/) 3.8.5 or +
- [pipenv](https://pypi.org/project/pipenv/)

## Iniciando a aplicação

**Criar um ambiente virtual**  
``` terminal
pipenv shell
```

**Instalar as dependências do projeto**  
``` terminal
pipenv install
```

**Realizar as migrações do Django**
``` terminal
python manage.py makemigrations clientes
python manage.py migrate
```

**Para utilizar uma base de dados com clientes fakes,executar o seguinte comando**
``` terminal
python populate_script.py
```

**Subir o servidor de aplicação**  
``` terminal
python manage.py runserver
```

---
