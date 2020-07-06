# Code Test

Somos um time de desenvolvimento ágil, trabalhamos com várias tecnologias e linguagens, todas em microserviços, e por iso, você pode escolher a linguagem que achar mais interessante. Aqui, utilizamos principalmente python e java no backend, e no front, react, angular e flask (python), mas sempre estamos abertos a conhecer algo novo. Se você for Backend, nos apresente as chamadas e retornos da sua API, se for Frontend, pode utilizar um Mock (Mockjs por exemplo) para simular seu backend e conseguir desenvolver, mas caso seja FullStack, mostre tudo que der para fazer nesse tempo :).


## Do do list

A idéia é fazer um sistema de cadastro simples de Pacientes de um hospital, então basicamente a gente precisa de um backend restfull e um frontend consumindo esses metodos e seguir os passos:

* Criar um repositório público (github, gitlab, bitbucket,...)
* Separar o que for de Backend e de Frontend
* Criar um Readme, descrevendo o que você fez e como subir e utilizar (urls, postman...)
* Envia o link para a gente 

**Fields**

| Campo                     | Tipo  |
| --------------------------|:---------------------|
| 1 - Nome              | texto               |
| 2 - Email             | texto               |
| 3 - Cpf             | numero               |
| 4 - Data Nascimento             | data               |
| 5 - Endereço
| 5.1 - rua             | texto               |
| 5.2 - numero             | numero               |
| 5.3 - complemento             | texto               |
| 5.4 - cidade             | texto               |
| 5.5 - estado             | texto               |
| 5.6 - cep             | numero               |
| 6 - Telefone | numero               |

**Requirements:**

- Lista de pacientes
- Permitir o cadastro de paciente (Crud - Create, read, update, delete)

**Obs**

- Cada paciente tem apenas um endereço (fique a vontade)
- A modelagem dos dados fica a seu critério. 
- Banco de dados pode ser em memória (H2...)
- Se for fazer o front, pode utilizar componentes básicos e sem customização de qualquer framework padrão de CSS, (bootstrap, material...)

## Evaluation

O que você vai apresentar:

* Documentação do projeto (readme com os passos para executar corretamente seu projeto)
* Facilidade de configuração
* Facilidade para rodar o projeto
* Adaptação do projeto
* Código limpo e organização
* Boas práticas de desenvolvimento
* Testes unitários

## Bonus

O que não precisa fazer, mas como você não consegue viver sem...

* Design Patterns (descreva no readme)
* Script de Build automatizado
* Docker
* Testes integrados
* Autenticação, JWT, oAuth...
* Qualquer coisa a mais que você acha relevante (fique a vontade)
