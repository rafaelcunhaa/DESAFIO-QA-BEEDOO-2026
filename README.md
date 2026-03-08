# DESAFIO-QA-BEEDOO-2026


## Objetivo da aplicação

A aplicação tem como objetivo permitir o cadastro e gerenciamento de cursos. 
O sistema possibilita que usuários adicionem novos cursos e visualizem os cursos cadastrados em uma lista.

## Principais fluxos da aplicação

### Cadastrar Cursos
- Usuário preenche as informações do curso no formulário de cadastro
- Usuario envia o formulario feito
- Curso é salvo no sistema

### Listagem de cursos
- Sistema exibe os cursos cadastrados
- Usuário pode visualizar ou pode excluir o cursos

### Validação de campos
- O sistema deve validar campos obrigatórios antes do cadastro

## Pontos críticos para teste
- Validação de campos obrigatórios no cadastro de cursos
- Tratamento de erros ao enviar informações inválidas
- Comportamento da aplicação ao inserir dados inesperados
- Persistência dos cursos cadastrados na listagem

## Cenários de Teste

[Link](https://docs.google.com/spreadsheets/d/1n2mia43C560ylDSUsmUFDLJ4xWSKecSItiII6V1rS68/edit?usp=sharing) para cenários de teste

## Evidências dos testes

### CT01 - Cadastro de curso válido 👍
<img width="1913" height="939" alt="image" src="https://github.com/user-attachments/assets/65c729c1-087d-49b3-9f6a-27e6df0c0aff" />
<img width="1919" height="942" alt="image" src="https://github.com/user-attachments/assets/b0d7833a-6899-4854-bfe8-a9dae4b15347" />

### CT02 - Cadastro sem informações👎
<img width="1919" height="940" alt="image" src="https://github.com/user-attachments/assets/9902a17b-4b50-4dd3-b891-24fb78d123bf" />
<img width="1919" height="942" alt="image" src="https://github.com/user-attachments/assets/a41b1a13-c813-43b2-8ee9-5abe649aaba9" />

### CT03 - Ver curso na listagem👍
<img width="1919" height="941" alt="image" src="https://github.com/user-attachments/assets/6e0269ae-56ab-4284-ac7f-c076529104b6" />


### CT04 - Inserção de dados inválidos👎
<img width="1919" height="944" alt="image" src="https://github.com/user-attachments/assets/d22eb129-8193-4e9f-9209-913e962806cf" />
<img width="1919" height="942" alt="image" src="https://github.com/user-attachments/assets/03c4211c-4015-415a-9871-ac8dfcc89d28" />

### CT05 - Exclusão de curso(tentativa no curso "Computação")👎
<img width="1919" height="941" alt="image" src="https://github.com/user-attachments/assets/79d282fd-c81b-4239-887d-32ce0eff64f7" />
<img width="1124" height="946" alt="image" src="https://github.com/user-attachments/assets/a9d1dd99-ac71-44b0-b4a6-28deac97507b" />

### CT06 - Cadastro de curso duplicado👎
<img width="1918" height="943" alt="image" src="https://github.com/user-attachments/assets/01dc302f-0497-48b8-b0b7-4322ce8738b2" />

## Bugs encontrados

Durante a execução dos testes foram identificados alguns problemas relacionados à validação de dados e funcionamento de funcionalidades do sistema.
Os bugs encontrados estão documentados abaixo neste repositório, contendo título, passos para reprodução, resultado atual, resultado esperado e severidade.



