# One click ticket
Aplicação web de geração de senhas e gerenciamento de tickets.

Uma das dificuldades de se implantar um sistema de gerenciamento de tickets em uma empresa é a resistência dos usuários para digitar as informações do ticket no momento da abertura. Muitos criam uma resistência em "abrir um chamado" alegando sempre pressa na resolução dos problemas.

A proposta do One Click Ticket é implantar progressivamente um sistema de controle de ticket, sendo que inicialmente é um sistema de senhas, onde o sistema vai gerar apenas uma senha para acompanhamento. A digitação das informações do ticket é, inicialmente, digitada pelo help desk/atendente. Opcionalmente, o usuário poderá digitar informações na abertura da senha.

O One Click Ticket vai permitir a evolução do controle de tickets de uma simples geração de senha de atendimento até um sistema de ITSM completo!

Informações do projeto:

* PHP 8.2.12
* Laravel 11
* MySQL/MariaDB 10
* Composer

Para rodar o projeto:

* Baixe o projeto no seu computador
* Crie o banco MySQL e configure o mesmo no arquivo .env
* Acesse a pasta oneclickticket e digite o comando "composer install"
* Rode as migrações com o comando "php artisan migrate"
* Rode o servidor utilizando o comando "php artisan serve"
* Acesse no navegador localhost:8080/admin, acesse com usuário "admin" senha "admin"
* No painel de admin, cadastre seus usuários e suas permissões
* Acesse o sistema em localhost:8080/login com o usuário cadastrado

Em breve, manual de utilização aqui! :)
