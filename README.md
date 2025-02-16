Uma API do zero para gerenciar tickets de suporte técnico. 
=

A API permitirá :

1.Criar

2.Atualizar

3.Listar  

4.Filtrar tickets 

5.Fechar e excluir tickets

Vamos focar no desenvolvimento do back-end utilizando Node.js
=

Com rotas para criar, obter, atualizar e excluir tickets. Os dados enviados nas requisições incluem informações sobre equipamento, descrição e nome do usuário. Vamos praticar a geração automática de IDs e permitir a edição de equipamento e descrição, mantendo o nome do usuário fixo.

Testar middlewares utilizando o Insomnia para enviar uma requisição POST e verificar o conteúdo recebido. O middleware é essencial para processar e manipular dados enviados nas requisições HTTP.

É desenvolvido um arquivo "database.js" para manipular o banco de dados, utilizando o módulo file system do Node.js. São criados métodos para inserir e selecionar dados, além de um método de persistência. Ao instanciar a classe, o arquivo é automaticamente criado se não existir, permitindo o armazenamento permanente dos dados.

Como criar uma rota para deletar um ticket em uma aplicação
=

Foi utilizado o Insomnia para enviar uma requisição do tipo delete, passando o ID do ticket a ser removido. Em seguida, foi criado um controller para lidar com a remoção do ticket no banco de dados. Após testar a funcionalidade, foi possível observar a remoção do ticket no banco de dados e na API.
