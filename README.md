# API-com-Django-3-Aprofundando-em-testes-e-documentacao

API com Django 3: Aprofundando em testes e documentação: 

https://cursos.alura.com.br/course/api-django-3-testes-documentacao

>pip install -r requirements.txt

>python manage.py migrate

>python manage.py createsuperuser

>python manage.py runserver

>python manage.py loaddata programas_inicias.json

Módulo 1:

* Aprendemos que é possível carregar dados iniciais para os modelos através das fixtures. Para isso, dentro de cada APP, podemos criar uma pasta chamada fixtures com dados no formato JSON, por exemplo, e carregá-los executando o comando manage.py loaddata seguido do nome do arquivo que contém os dados.
* Aprendemos que existem diferentes formas de testar uma aplicação, como testes manuais, automatizados, testes de unidade, integração, entre outros.

Módulo 2:

* Aprendemos que o teste de unidade é um método de teste de software no qual os componentes individuais do programa, chamados de unidades, são testados a despeito das dependências necessárias;
* Criamos os testes de unidade para verificar os campos serializados e se o modelo atribuía os valores default quando eram omitidos.

Módulo 3:

* Criamos os testes que verificam a autenticação de um usuário com base nas políticas de acesso do Django, criando um usuário na base de dados de testes;
* Verificamos as tentativas de acesso de um usuário com as credenciais corretas e incorretas e realizamos uma requisição GET de um usuário autenticado.

Módulo 4:

* Aprendemos que é possível carregar os dados das fixtures no banco de dados de testes;
* Testamos a API da Alura no Postman, verificando se o statuscode da requisição era o esperado. Além disso, verificamos também se o tipo de dado da resposta estava no formato desejado.

Módulo 5:

* Entendemos a importância de documentar uma API para outras pessoas e sistemas. Porém, essa documentação deve seguir o ritmo da implementação de código;
* Integramos o Swagger no Django Rest Framework e vimos na prática a documentação gerada. Além disso, realizamos alguns testes no Swagger.

--------------------------------------------------------------------------------------------------------------------------------------------


API with Django 3: Deepening testing and documentation:

https://cursos.alura.com.br/course/api-django-3-testes-documentacao

>pip install -r requirements.txt

>python manage.py migrate

>python manage.py createsuperuser

>python manage.py runserver

>python manage.py loaddata programas_inicias.json

Module 1:

* We learned that it is possible to load initial data for models through fixtures. For this, within each APP, we can create a folder called fixtures with data in JSON format, for example, and load them by executing the command manage.py loaddata followed by the name of the file that contains the data.
* We learned that there are different ways to test an application, such as manual testing, automated testing, unit testing, integration, among others.

Module 2:

* We learned that unit testing is a method of testing software in which individual program components, called units, are tested regardless of necessary dependencies;
* We created the unit tests to verify the serialized fields and that the model assigned the default values ​​when they were omitted.

Module 3:

* We created tests that verify a user's authentication based on Django's access policies, creating a user in the test database;
* We check login attempts by a user with correct and incorrect credentials and perform a GET request from an authenticated user.

Module 4:

* We learned that it is possible to load fixture data into the test database;
* We tested Alura's API in Postman, verifying if the statuscode of the request was the expected one. In addition, we also checked whether the response data type was in the desired format.

Module 5:

* We understand the importance of documenting an API for other people and systems. However, this documentation must keep pace with code implementation;
* We integrated Swagger into the Django Rest Framework and saw the generated documentation in practice. In addition, we performed some tests on Swagger.
