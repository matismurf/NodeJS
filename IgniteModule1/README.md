# NodeJS

O que é node.js?
-Uma plataforma open-source que permite execução da linguagem javascript do lado do servidor

O que é REST?
-Representation State Transfer(Transferência Representacional de Estado)
-é um modelo de arquitetura
-Possui 6 regras(Client-server,stateless,cache,interface uniforme,camadas,código sob demanda)

Métodos de requisições-http verbs
-Get-Leitura
-Post-Criação
-Put-Atualização
-Delete-deleção
-Patch-Atualização parcial

HTTP Codes
-1XX:Informativo-a solicitação foi aceita ou o processo continua em andamento
-2XX:Confirmação
	-200-Requisição bem sucedida
	-201-Created-Geralmente usado para POST após uma inserção
-3XX:Redirecionamento
	-301-Moved Permantly
	-302-Moved
-4XX:Erro do cliente
	-400-Bad Request
	-401-Unauthorized
	-403-Forbidden
	-404-Not Found
	-422-Unprocessable Entity
-5XX:Erro no servidor-o servidor falhou ao concluir a solicitação
	-500-internal server error
	-502-Bad Gateway

Parâmetros das Requisições
-Header params
-Query Params
-Route Params
-Body Params

Boas Práticas API Rest
-A utilização correta dos métodos HTTP
-a utilizalização correta dos status no retorno das respostas
-Padrão de nomenclatura
	-Busca de usuários-GET
	-Busca de usuário por id-GET
	-Deleção ded um usuário-DELETE
	-Atualização do status do usuário-PATCH
-Os médicos HTTP são:
	-GET - buscar uma informação dentro do servidor
	-POST - Inserir uma informação no servidor
	-PUT - Alterar uma informação no servidor
	-PATCH - Alterar uma informação específica
	-DELETE - Deletar uma informação no servidor
-Tipos de parâmetros
	-Route Params - identificar um recurso para poder editar/deletar/buscar
	-Query Params - Paginação/ Filtro
	-Body Params - Os objetos para inserção/alteração de algum recurso(JSON)
-O que é middleware
	-o middleware é um software que diferentes aplicações usam para se comunicar umas com as outras
