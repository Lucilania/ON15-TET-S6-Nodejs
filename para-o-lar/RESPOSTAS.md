
1.	CRUD são as quatro operações básicas no mundo do desenvolvimento. No entanto, assim como na matemática nenhum calculo complexo é feito sem que seja utilizado as quatro operações básicas (soma, subtração, multiplicação e divisão), na programação também temos operações similares que servem como base para muitos tipos de soluções, sendo elas:

CREATE: operação utilizada para criar/registrar informações em determinado lugar, podendo ser um banco de dados ou até numa simples lista de informações. Aqui vale o exemplo do registro de usuários em uma plataforma, ou até a criação de um novo post que será publicado em determinado blog. Estes e vários outros modelos de criação utilizam o conceito de create.

READ: operação responsável pela consulta de dados. Sabe quando você entra na sua conta do LinkedIn e visita o perfil de alguém ou até o seu mesmo? O que acontece por trás dos panos é uma operação de read, uma vez que você está solicitando dados que serão lidos pela plataforma que, consequentemente, serão exibidos na tela e você poderá fazer a leitura :). Basicamente o LinkedIn consulta nossas informações no banco de dados deles com uma operação de read e os apresenta de forma bastante amigável para nós.

UPDATE: operação que trabalha na atualização de informações. Ainda utilizando o LinkedIn como exemplo, esta operação é aplicada quando você deseja atualizar seus dados que estão disponíveis no seu perfil. Aqui é algo mais limitado, você não pode atualizar os dados de outra pessoa. Essa operação requer que somente o dono das informações possa atualiza-las. No mundo da programação, muitas funções que são responsáveis por atualizar algum banco de dados utilizam o conceito de update para fazê-lo.

DELETE: operador que permite a deleção de dados. Esta operação é significativamente menos utilizada por desenvolvedores em relação as outras, isso porque é ela quem permite a exclusão total de informações que estão armazenadas em determinado local. Mas digamos que você queira excluir seu nome de uma lista de aniversário que você disse que poderia ir no fim de semana, mas que não poderá mais. Se esta lista estivesse gravada em um banco de informações, provavelmente seria necessário utilizar o operador de deleção para te tirar de lá!

2.	Os verbos HTTP são: Post, Get, Put, Patch, Delete.
 As operações CRUD são: Create, Read, Update/Replace, Updade/Modify, Delete.

 O protoclo HTTP funciona com os clintes enviando requests para os servers, e os servers respondendo a estes requests. As operações CRUD são enviadas através de requests HTTP, feitos através dos verbos. O CRUD é um acronímico que resume as quatro principais formas de intereção entre database e aplicações, ou seja:
 
               POST /users # Cria um usuario
               PUT /users/{id} # Atualiza o usuario
               PATCH  /users/{id} # Parcialmente atualiza o usuario
               DELETE /users/{id # Remove o usuario
               
3.HATEOAS é uma restrição que faz parte da arquitetura de aplicações REST, cujo objetivo é ajudar os clientes a consumirem o serviço sem a necessidade de conhecimento prévio profundo da API. Para que uma API seja considerada do tipo RESTful, ela precisa está em conformidade com os seguintes critérios: Ter uma arquitetura cliente/servidor formada por clientes, servidores e recursos, com solicitações gerenciadas por HTTP. Estabelecer uma comunicação stateless entre cliente e servidor.

4. idempotência ocorre quando é possível fazer diversos requests idênticos tendo o mesmo efeito de um único request. é uma forma de deixar os APIs tolerantes aos erros dos consumidores. Sifnifica que o resultado do request vai ser bem-sucedido independete da quantidade de vezes que for executado.

6. O método de requisição HTTP PATCH aplica modificações parciais a um recurso. O método HTTP PUT permite apenas substituições completas de um documento. Em contraste ao PUT , o método PATCH não é idempotente, ou seja, requisições sucessivas idênticas podem obter efeitos distintos.
