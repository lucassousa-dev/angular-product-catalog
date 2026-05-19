# Angular Product Catalog

Aplicação web desenvolvida em Angular para cadastro e listagem de produtos, utilizando comunicação HTTP com uma API simulada via JSON Server.

O projeto foi criado para praticar conceitos fundamentais de desenvolvimento front-end com Angular, incluindo componentização, serviços, formulários reativos e integração com uma camada de dados externa.

## Funcionalidades

- Cadastro de produtos
- Listagem dinâmica dos produtos cadastrados
- Comunicação com API simulada
- Separação de responsabilidades por componentes e serviços
- Atualização da interface após novas inserções

## Tecnologias utilizadas

- Angular 20
- TypeScript
- HTML
- CSS
- RxJS
- JSON Server

## Estrutura técnica

O projeto foi organizado com foco em separação de responsabilidades:

- `product-component`: interface e lógica de cadastro/listagem
- `ProductService`: comunicação HTTP com a API
- `Product`: modelo utilizado para tipagem dos dados
- `db.json`: base simulada consumida pela aplicação

## Como executar o projeto

### Pré-requisitos

- Node.js instalado
- Angular CLI instalado
- JSON Server instalado

### Passos

1. Clone o repositório:

```bash
git clone https://github.com/lucassousa-dev/angular-product-catalog.git
```

2. Clone o repositório:

```bash
cd angular-product-catalog
```

3. Instale as dependências:

```bash
npm i
```

4. Inicie a API simulada:

```bash
npx json-server --watch db.json --port 3000
```

5. Execute a aplicação Angular:

```bash
ng s
```

6. Acesse no navegador:

```bash
http://localhost:4200
```

## Aprendizados aplicados

- Criação e reutilização de componentes em Angular
- Uso de serviços para centralizar chamadas HTTP
- Manipulação de formulários reativos
- Consumo de dados via API simulada
- Atualização de estado na interface após operações de cadastro

## Possíveis evoluções

- Validação mais completa dos campos
- Edição e remoção de produtos
- Feedback visual de carregamento e erro
- Integração com uma API real
