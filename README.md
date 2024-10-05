# Starter API Node.js com TypeScript e Express

Este projeto é um **Starter** para a criação de uma API REST utilizando **Node.js**, **TypeScript** e **Express**. Ele oferece uma estrutura inicial para o desenvolvimento de APIs mais robustas e escaláveis, com uma configuração mínima necessária para acelerar o desenvolvimento.

## Funcionalidades

- Configuração inicial para um projeto **Node.js** com **TypeScript**.
- Servidor web usando **Express**.
- Utilização de variáveis de ambiente com **dotenv**.
- Scripts prontos para desenvolvimento, build e testes.
- Sistema de testes configurado com **Vitest**.

### Tecnologias utilizadas

- **Node.js**: Ambiente de execução para JavaScript no lado do servidor.
- **TypeScript**: Superset de JavaScript que adiciona tipagem estática e outros recursos avançados.
- **Express**: Framework minimalista para construir APIs e servidores web.
- **Tsup**: Ferramenta de empacotamento para compilar o código TypeScript para JavaScript.
- **TSX**: Utilizado para executar scripts TypeScript sem precisar configurar diretamente o Node.js.
- **Vitest**: Framework de testes, similar ao Jest, que permite rodar testes unitários de forma rápida.
- **Dotenv**: Utilizado para carregar variáveis de ambiente a partir de um arquivo `.env`.

## Como instalar

Para clonar e configurar este projeto localmente, siga os passos abaixo:

1. Clone o repositório:

   ```bash
   git clone https://github.com/emersonbbezerra/starter_api_node_typescript_express.git
   ```

2. Navegue até o diretório do projeto:

   ```bash
   cd starter_api_node_typescript_express
   ```

3. Instale as dependências do projeto:
   ```bash
   npm install
   ```

## Como usar

### Modo de Desenvolvimento

Para rodar o servidor em modo de desenvolvimento, utilize o seguinte comando. Ele automaticamente recompilará o código sempre que houver mudanças:

```bash
npm run dev
```

### Build

Para compilar o código TypeScript para JavaScript, execute o seguinte comando. Os arquivos compilados serão gerados na pasta dist/:

```bash
npm run build
```

### Testes

Este projeto utiliza o Vitest para rodar os testes. Para executar todos os testes, use o comando:

```bash
npm run test

```

## Scripts

- **`dev`**: Inicia o servidor em modo de desenvolvimento, recompilando automaticamente o código sempre que houver alterações.
- **`build`**: Compila o código TypeScript para JavaScript utilizando o **tsup**.
- **`test`**: Executa os testes unitários com o **Vitest**.

## Estrutura de Pastas

- **src/**: Contém o código-fonte da aplicação.
- **dist/**: Onde o código compilado será gerado após a execução do comando de build.

## Contribuindo

Sinta-se à vontade para fazer um fork do projeto e contribuir com melhorias. Ao realizar modificações, lembre-se de criar uma branch específica para o seu trabalho e abrir um **pull request** quando finalizado.

---

Com isso, você tem um **starter** configurado para começar rapidamente o desenvolvimento de uma API REST usando **Node.js**, **TypeScript** e **Express**, além de contar com ferramentas que facilitam o build e os testes da sua aplicação.
