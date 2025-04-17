# DNC-BoardTasks-Back

Projeto desenvolvido com **Express.js** com o aprendizado das aulas na **Escola DNC**.  
Este repositório representa a **API Back-End** do sistema de gerenciamento de tarefas (BoardTasks), com foco em boas práticas de arquitetura, organização de rotas e uso de variáveis de ambiente.

## Tecnologias Utilizadas

- **Node.js**
- **Express.js**
- **dotenv**
- **nodemon** 
- **cors**
- **mongoose**

## Pré-requisitos

Antes de executar o projeto, garanta que você tenha instalado:
- [Node.js](https://nodejs.org/)  
- [NPM](https://www.npmjs.com/) (ou [Yarn](https://yarnpkg.com/) se preferir)

## Como rodar o projeto localmente
1. **Clone este repositório**:
   ```bash
   git clone https://github.com/seu-usuario/DNC-BoardTasks-Back.git
   cd DNC-BoardTasks-Back
   ```

2. **Configure as variáveis de ambiente**:
   
   Copie o arquivo `.EXEMPLO.env`:
   
     ```bash
     cp .EXEMPLO.env .env
     ```
   Preencha as variáveis com os valores corretos (como `PORT`, `DB_URI`, etc).

4. **Instale as dependências**:
   ```bash
   npm install
   ```

5. **Inicie o servidor em modo desenvolvimento**:
   ```bash
   npm run dev
   ```

6. Pronto! A API estará disponível em:
   ```
   http://localhost:4000
   ```

## Documentação da API

A documentação da API pode ser acessada via navegador após iniciar o servidor:

[http://localhost:4000](http://localhost:4000)

## Créditos

Projeto desenvolvido durante o curso da **Escola DNC**, sob orientação de **Rubens Flinco**.  
Código com fins educacionais e práticos, voltado ao aprendizado de arquitetura e desenvolvimento back-end com Node.js.
