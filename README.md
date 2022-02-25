# Projeto individual desenvolvido dentro do módulo de Back-end do curso de Desenvolvimento Web FullStack na Trybe para fins avaliativos.

# Habilidades

Esse projeto foi desenvolvido visando os seguintes pontos de aprendizado:

- Entender o funcionamento da camada de Model;
- Delegar responsabilidades específicas para essa camada;
- Conectar a aplicação com diferentes `collections` do bancos de dados;
- Estruturar a aplicação em camadas;
- Delegar responsabilidades específicas para cada parte do app;
- Melhorar manutenibilidade e reusabilidade do código;
- Entender e aplicar os padrões REST;
- Escrever assinaturas para APIs intuitivas e facilmente entendíveis.

## O que foi desenvolvido

O objetivo foi desenvolver uma API utilizando a arquitetura MSC!

A API em questão trata-se de um sistema de gerenciamento de vendas, onde será possível criar, visualizar, deletar e atualizar produtos e vendas.

---

# Instruções para rodar o projeto

1. Clone o repositório

- `git clone https://github.com/breenolf/sd-09-breenolf-store-manager.git`.
- Entre na pasta do repositório que você acabou de clonar:
  - `cd sd-09-store-manager`

2. Instale as dependências e inicialize o projeto

 - Instale as dependências:
    - `npm install`
 - Inicialize o projeto:
    - `npm start`
 - Rode os testes:
    - `npm test`

---

### Conexão com o Banco:

A conexão do banco local deverá conter os seguintes parâmetros:

```javascript
const MONGO_DB_URL = 'mongodb://localhost:27017/StoreManager';
const DB_NAME = 'StoreManager';
```

Para os testes rodarem altere a conexão do banco para:

```javascript
const MONGO_DB_URL = 'mongodb://mongodb:27017/StoreManager';
const DB_NAME = 'StoreManager';
```

## Linter

Para garantir a qualidade do código de forma a tê-lo mais legível, de mais fácil manutenção e seguindo as boas práticas de desenvolvimento foi utilizado neste projeto o linter ESLint. Para rodar o linter localmente, execute o comando abaixo:

  - `npm run lint`

---
