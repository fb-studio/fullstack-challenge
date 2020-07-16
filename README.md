<p align="center">
  <img src="https://fbredacao.com/assets/img/logo_sfb.png" />
</p>

## Challenge - FullStack Engineer

O objetivo deste desafio é avaliar seu domínio no desenvolvimento fullstack: organização, estilo e boas práticas com código, criação de APIs, conhecimento nas tecnologias e estruturas.

Você será avaliado pela sua capacidade de escrever um código simples, de fácil manutenção, e pela quantidade de funcionalidades que você entregar.

### Instruções

- **Nome do Projeto:** FB Quest
- **Objetivo do Projeto:** Criar um Aplicativo de resoluções de questões avulsas do ENEM com dashboad web para revisão das questões (CRUD) e ambos os ambientes precisam de APIs que enviem e recebam essas informações.
- **Tecnologias:** React/React Native e NodeJS.
- **User Interface:** Você pode [usar esse link](https://scene.zeplin.io/project/5f120b91fab6d3067d9ee699) como referência de UI durante o desenvolvimento.
- **Entregáveis:** siga as instruções abaixo:
  - Título: [FullStack-Engineer] Seu nome
  - Crie um repositório público para esse projeto e envie link.
  - Envie para cleanderson.queiroz@fariasbrito.com.br com cópia para marcos.mendes@fariasbrito.com.br

---
## **Desafio**
>### **Aplicativo**
- Tela incial do app antes de começar a responder as questões:
    - O usuário deve ser capaz de selecionar a quantidade de questões (min=1 | max=40);
    - O usuário só pode ser capaz de responder as questões disponíveis.
- Responder as questões;
    - Mostrar o tempo corrido (Ex.: 00:10);
    - Ao responder uma questão, usuário deve ser capaz de visualizar em seguida se a resposta está correta ou não.
    - Após responder a questão usuário deve ser capaz de ver a resolução caso a questão possua.
- Resultado das questões;
    - Mostrar uma % de aproveitamento geral de acertos de questões.
    - Tempo total gasto para responder as questões.
>### **Web**
- Crie um dashboard de Questões que:
    - O usuário deve ser capaz de visualizar as questões;
    - Editar enunciado ou resolução da questão (Rich Text);
    - O usuário deve ser capaz de marcar se a questão está disponivel ou não.
>### **Backend**
- Crie uma API Rest para buscar e atualizar as questões.

---
### O que nós vamos avaliar

- Você será avaliado pela qualidade do código, legibilidade e pela quantidade de funcionalidades implementadas.
- Você é livre para tomar as decisões técnicas com as quais você se sente mais confortável.
- Inclua um arquivo *README* que possua:
  - desafios/problemas com os quais você se deparou durante a execução do projeto.
  - maneiras através das quais você pode melhorar a aplicação, seja em performance, estrutura ou padrões. 
  - todas as intruções necessárias para que qualquer pessoa consiga rodar sua aplicação sem maiores problemas.

### Dicas

- Documente seu projeto em arquivos markdown explicando a estrutura, processo de setup e requisitos.
- Tenha sempre um mindset de usabilidade, acessibilidade e colaboração.
- A organização das branches e os commits no repositório falam muito sobre como você organiza seu trabalho.
- Você pode utilizar bibliotecas de componentes visuais;
- O material de UI/UX que fornecemos deve servir como uma referência de arquitetura e navegação, mas você não precisa necessariamente segui-lo à risca. Pode usar uma biblioteca de UI de sua preferência.
- Os testes unitários são opcionais porém são mais do que desejados.
- O design/estrutura do código da aplicação deve ser *production ready*.
- Tenha em mente os conceitos de *SOLID, KISS, YAGNI e DRY*.
- Use boas práticas de programação.

---

>### **API**

**Disponibilizamos um .json com algumas questões**

- [Questões.json](questoes.json)
```javascript
Formato:
[
  {
    "id": Number,
    "materia": String,
    "vestibular": String,
    "resolucao": String,
    "enunciado": String,
    "numeroQuestao": Number,
    "ano": Number,
    "alternativas":[
      {
        "letra": String,
        "correta": Boolean,
        "texto": String
      }
    ],
    "disponivel": Boolean
  }
]
```

- Campos Enunciado e Resolução é uma string HTML;
- "numeroQuestao" é a ordem da questão em um Simulado;

---
## FAQ
#### Posso utilizar frameworks/bibliotecas?
Sim. 
>**Ex.:** Bootstrap, Material-UI, styled-componentes, Express e etc..

#### React, Flutter, Angular ou Vue?
Você precisa implementar em React/React Native e NodeJS.

#### Banco de dados?
De preferência MongoDB

#### Preciso colocar alguma aplicação em produção?
Seria interessante pelo menos Dashboard Web e API. (Heroku, Firebase e etc ....)

#### Quanto tempo eu tenho ?
O tempo que você precisar, mas a maioria dos candidatos termina esse teste entre 5 a 7 dias. 

## Boa Sorte!
Sinta-se à vontade para fazer qualquer pergunta durante o desenvolvimento.