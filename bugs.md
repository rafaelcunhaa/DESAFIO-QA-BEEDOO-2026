# Bugs

## 1 — Cadastro sem validação
Bug 01 – Sistema permite cadastrar curso sem preencher campos obrigatórios

### Passos para reproduzir:

- Acessar a página de cadastro de cursos
- Deixar todos os campos vazios
- Clicar no botão de cadastrar curso

### Resultado atual

O sistema cadastra o curso mesmo sem nenhuma informação preenchida.

### Resultado esperado

O sistema deveria impedir o cadastro e exibir mensagem informando que os campos são obrigatórios.

### Severidade

Alta – Pode comprometer a integridade dos dados cadastrados.

## 2 — Falta de validação de dados
Bug 02 – Sistema aceita dados inválidos no cadastro de cursos

### Passos para reproduzir:

- Acessar a página de cadastro
- Inserir caracteres especiais no nome do curso
- Inserir número negativo no campo de vagas
- Inserir uma data inválida
- Clicar em cadastrar

### Resultado atual

O sistema permite o cadastro mesmo com dados inválidos.

### Resultado esperado

O sistema deveria validar os dados inseridos e impedir o cadastro quando as informações forem inválidas.

### Severidade

Média – Pode gerar registros inconsistentes no sistema.


## 3 — Exclusão de curso não funciona
Bug 03 – Botão de excluir curso não remove o curso da listagem

### Passos para reproduzir:

- Acessar a página de listagem de cursos
- Selecionar um curso cadastrado
- Inserir número negativo no campo de vagas
- Clicar no botão "Excluir"

### Resultado atual

O curso permanece na listagem mesmo após clicar em excluir.

### Resultado esperado

O curso deveria ser removido da listagem.

### Severidade

Alta – A funcionalidade de exclusão não está funcionando.

## 4 — Cadastro de cursos duplicados
Bug 04 – Sistema permite cadastro de cursos duplicados

### Passos para reproduzir:

- Cadastrar um curso com determinado nome
- Repetir o cadastro com as mesmas informações

### Resultado atual

O sistema permite cadastrar o mesmo curso várias vezes.

### Resultado esperado

O sistema deveria impedir cadastros duplicados ou alertar o usuário.

### Severidade

Média – Pode gerar duplicidade de informações.










