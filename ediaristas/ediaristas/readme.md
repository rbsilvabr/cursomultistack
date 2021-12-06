## Projeto e-diaristas

### Instalando o projeto

#### Clonar o projeto
`git clone https://github.com/rbsilvabr/cursomultistack.git`

#### Instalar dependências
`pip install -r requirements.txt`

#### Alterar configurações do BD no arquivo `settings.py` 
```
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'nome_do_banco_de_dados',
        'HOST': 'host_do_BD',
        'PORT': porta_do_BD,
        'USER': 'usuario_do_BD',
        'PASSWORD': 'senha_do_BD',
    }
}
```

#### Migrar banco de dados
`pip manage.py migrate`

#### Iniciar o servidor
`pip manage.py runserver`
