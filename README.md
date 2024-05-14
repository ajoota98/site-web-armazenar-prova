# site-web-armazenar-prova

**Passo a Passo para Executar o Programa**

-----------------------
Instalação do Python:
Faça o download e instale a versão mais recente do Python no site oficial: Python.org


-----------------------
Clonagem do Repositório:
Abra o terminal ou prompt de comando e navegue até o diretório onde você deseja clonar o repositório.

Execute o seguinte comando para clonar o repositório da aplicação:

git clone **link do repositório**


-----------------------
Instalação de Dependências:

Navegue até o diretório recém-clonado da aplicação.

Verifique se você está no diretório correto onde o arquivo requirements.txt está presente.

Execute o seguinte comando para instalar as dependências do projeto:
pip install -r requirements.txt


-----------------------
Configuração do Banco de Dados:

Caso você nao tenha, instale manualmente o Flask, Execute o seguinte comando:
pip install flask


Caso ocorra algum problema, você precisa instalar o Flask-SQLAlchemy. Aqui está o comando para instalar o Flask-SQLAlchemy:
pip install flask-sqlalchemy


No diretório da aplicação, execute o seguinte comando para iniciar o servidor Flask:
python app.py

-----------------------
Acesso à Aplicação:

Após iniciar a aplicação, abra um navegador da web (como Google Chrome, Firefox, etc.).

Na barra de endereços do navegador, digite o seguinte endereço que aparece no terminal/prompt (geralmente algo como https://localhost:5000 ou http://127.0.0.1:5000

Isso abrirá a aplicação em seu navegador e você poderá começar a usar a funcionalidade de cadastro, consulta, edição e remoção de itens.






-----------------------------


Procedimentos e Métodos Utilizados:
Framework Flask:

Escolhi o Flask como o framework para desenvolver a aplicação devido à sua simplicidade e flexibilidade.

Flask-SQLAlchemy:
Utilizei o Flask-SQLAlchemy para interagir com o banco de dados SQLite. SQLAlchemy é um ORM poderoso em Python, e Flask-SQLAlchemy integra perfeitamente o SQLAlchemy ao Flask, simplificando a manipulação de dados em bancos de dados relacionais.


Padrão MVC (Model-View-Controller):
Segui o padrão de arquitetura MVC para organizar o código da aplicação de forma clara e modular. Dividi a aplicação em três componentes principais:
Model: Representado pelos modelos de dados definidos usando Flask-SQLAlchemy.
View: As páginas HTML renderizadas usando templates Jinja2, localizadas no diretório templates/.
Controller: As rotas e a lógica de controle definidas em app.py.

O ORM SQLAlchemy foi escolhido para facilitar a interação com o banco de dados. Isso nos permite trabalhar com objetos Python em vez de escrever SQL manualmente, tornando o código mais legível e fácil de manter.


Usei o Jinja2 como mecanismo de template para gerar páginas HTML dinâmicas. Jinja2 é uma poderosa linguagem de template que permite a inclusão de lógica de programação nos templates HTML, tornando-os altamente flexíveis.


Escolhi o SQLite como banco de dados para esta aplicação devido à sua simplicidade e facilidade de uso. O SQLite é um banco de dados relacional embutido que não requer configuração de servidor separado, tornando-o ideal para aplicativos menores e desenvolvimento rápido.

Optei por ferramentas e métodos que são simples e fáceis de usar, como Flask, Flask-SQLAlchemy e SQLite. Isso permite um desenvolvimento rápido e eficiente da aplicação.

Ao seguir o padrão MVC e usar o ORM SQLAlchemy, o código da aplicação fica organizado, legível e fácil de manter.
