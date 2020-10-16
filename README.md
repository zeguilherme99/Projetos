# Projetos
Projeto Integrador Grupo 06 | Turma 09

# Documentação Back-End

## Categoria

## Model

| Atributo  | Tipo  |
|-----------|-------|
|ID|Long|
|Tipo|String|
|Nome|String|

A tabela possuirá os atributos ID referente ao código de cada tema e descrição onde iremos inserir: as descrições, produtos, serviços, usuários, etc.

## Crud
| Métodos  | End-Points | Descrição |
|-----------|-------|-----|
| Get | /categoria | Listar todos as categorias existentes|
| Get | /categoria/{id} | Listar categoria específica pelo ID |
| Get | /categoria/descricao/{descricao} | Listar uma categoria específica pela descrição |
| Post | /categoria | Inserir os dados |
| Put | /categoria | Editar algum dado específico |
| Delete | /categoria/{id} | Excluir algum dado pelo ID |

A tabela possuirá os end-points básicos (get, post, put e delete) e mais dois métodos específicos, que buscam pelo id e pela descrição.
