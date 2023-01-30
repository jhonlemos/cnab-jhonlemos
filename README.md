# PROJETO CNAB teste-técnico

Esse é o projeto CNAB teste-técnico com o intuito de testar e avaliar meus conhecimentos técnicos com o back-end, mais especificamente em Python.

## Aplicação:

Foi dado um arquivo CNAB com os dados das movimentações financeiras de várias lojas. Precisei criar uma maneira para que estes dados fossem importados para um banco de dados.

Minha tarefa foi criar uma interface web que aceite upload do arquivo CNAB, normalize os dados e armazene-os em um banco de dados relacional e exiba essas informações em tela.

## Ferramentas ultilizadas:

- Python
- Django
- Django Rest Framework

# INSTRUÇÃO DE FUNCIONAMENTO

### Crie o ambiente virtual em seu terminal

```
python -m venv venv
```

### Inicie o ambiente virtual

#### Windows

###### Abra o PowerShell

```
.\venv\Scripts\activate
```

#### Linux

```
source venv/bin/activate
```

### Instale as dependências

```
pip install -r requirements.txt
```

### Execute as migrações

```
python manage.py migrate
```

### Inicie o servidor

```
python manage.py runserver
```

#### Para acessar a API coloque o end point

```
/api/cnab/
```
