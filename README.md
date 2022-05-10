# fake-api-buy-an-idea

Rotas privadas
##
POST /companys  - cadastrar uma empresa

PUT /companys/:id - editar dados de uma empresa ja cadastrada, apenas a pessoa que cadastrou a empresa pode fazer isso

DELETE /companys/:id - apagar uma empresa ja cadastrada, apenas a pessoa que cadastrou a empresa pode fazer isso


Rotas publicas
##
GET /companys - listar todas as empresas cadastradas

GET /companys/:id - listar uma determinada empresa a partir do seu id


Rotas de usuário
##
POST /register - cadastrar um usuário

POST /login - logar como um usuário cadastrado

GET /users - listar todos os usuários

GET /users/:id - listar um usuário a partir do seu id
