UserStory
 
**ID:** US001  
**Título:** Criação de Curso - Plataforma Beedoo
 
**Como** um usuário com permissão para criação de cursos <br>
**Quero** criar um novo curso na plataforma Beedoo  
**Para** que aumente a lista de cursos na biblioteca da plataforma
 
## Critérios de Aceite
- O usuário deve ter permissão para criação
- Deve exibir mensagem de erro se o curso já for existente
- Após criação, o curso deverá aparecer na tela de Lista de Cursos
 
## Regras de Negócio
- Não deverá ser permitido a duplicidade de cursos
- O nome do curso não poderá conter mais que 400 caracteres
 
-------
 
**ID:** US002  
**Título:** Exclusão de Curso - Plataforma Beedoo
 
**Como** um usuário com permissão para exclusão de cursos <br>
**Quero** excluir um curso na plataforma Beedoo  
**Para** que eu remova um curso na biblioteca da plataforma
 
## Critérios de Aceite
- O usuário deve ter permissão para exclusão
- Deve exibir mensagem de "Curso excluído com sucesso!"
- Após exclusão, o curso deverá sumir na tela de Lista de Cursos
 
## Regras de Negócio
- O curso deverá ser excluído da lista
- Garantir que o curso seja removido da lista de cursos
 
 
-------
 
**ID:** US003  
**Título:** Impedir criação de curso com campos obrigatórios não preenchidos  - Plataforma Beedoo
 
**Como** um usuário com permissão para criação de cursos <br>
**Quero** incluir um curso na plataforma Beedoo sem preencher os campos obrigatórios <br>
**Para** que eu garanta que os cursos tenham todos campos devidamente preenchidos
 
## Critérios de Aceite
- O usuário deve ter permissão para criação
- Deve exibir mensagem de "Campos obrigatórios não preenchidos!"
- O curso não deverá ser exibido na tela de Lista de Cursos
 
## Regras de Negócio
- O curso não deverá ser exibido da lista de cursos
- Garantir que o curso não seja exibido na lista de cursos
 
 
-------
 
**ID:** US004 
**Título:** Realizar preenchimento de curso e cancelar o cadastro do novo curso - Plataforma Beedoo
 
**Como** um usuário com permissão para criação de cursos <br>
**Quero** incluir um curso na plataforma Beedoo e cancelar depois de preencher <br>
**Para** que eu garanta que os cursos não sejam criados sem clicar no botão "Cadastrar Curso"
 
## Critérios de Aceite
- O usuário deve ter permissão para criação
- Não deverá ser criado nenhum novo curso
- O curso não deverá ser exibido na tela de Lista de Cursos
 
## Regras de Negócio
- O curso não deverá ser exibido da lista de cursos
- Garantir que o curso não seja exibido na lista de cursos
