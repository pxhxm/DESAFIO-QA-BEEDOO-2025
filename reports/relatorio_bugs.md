Relatório de Bugs
 
## Bug 001 - Exclusão do Curso
**Severidade:** Alta  
**Prioridade:** Alta  
**Ambiente:** Chrome 130 / Windows 10  
 
**Passos para Reproduzir:**
1. Acessar a tela "Listar Cursos"
2. Selecionar um curso existente
3. Clicar em “Excluir Curso”
4. Confirmar a exclusão
5. É exibido um pop-up de: “Curso excluído com sucesso!”
5. Validar que o curso foi excluído da Lista de Cursos
 
**Resultado Esperado:** Excluir o curso da lista  
**Resultado Obtido:** Curso continua listado  
**Status:** Aberto  
**Evidência:** (https://docs.google.com/document/d/1i1pvUbubiJJKTSyVEsD4qka2w7oiwS1k/edit?usp=drive_link&ouid=106137551970754038384&rtpof=true&sd=true)
 
 
-----
 
 
## Bug 002 - Campos obrigatórios
**Severidade:** Alta  
**Prioridade:** Alta  
**Ambiente:** Chrome 130 / Windows 10  
 
**Passos para Reproduzir:**
1. Acessar a tela "Cadastrar Curso"
2. Preencher campos
3. Deixar o campo “Nome do curso” em branco
4. Clicar no botão “Cadastrar curso”
5. É exibido um pop-up de: “Campos obrigatórios não preenchidos!”
6. Validar que o curso não foi criado na Lista de Cursos
 
**Resultado Esperado:** Exibir mensagem “Campos obrigatórios não preenchidos!” e o curso não deverá ser exibido na “Lista de Cursos”  
**Resultado Obtido:** Mensagem de sucesso exibida, e o curso está criado na lista, com o nome em branco. 
**Status:** Aberto  
**Evidência:** (https://docs.google.com/document/d/1HWkL9oI2qhbCPeHcO66KtVW7JbthY03U/edit?usp=drive_link&ouid=106137551970754038384&rtpof=true&sd=true)
