# Beon JSON Server

Faça um Fork deste projeto para o seu GitHub e após isto clone para a sua máquina local. Caso nunca tenha realizado este procedimento siga as instruções em: [GitHub - Bifurcar um Repo](https://docs.github.com/pt/get-started/quickstart/fork-a-repo)

### Requisitos mínimos

- **_Node 14.x ou superior_**

## Instruções de uso

- No prompt de comando vá até o diretório onde você clonou o repositório bifurcado e execute `npm install` para instalar as dependências do projeto.
- Faça a instalação do pacote npm JSON Server através do comando `npm install -g json-server`.
- Execute `json-server --watch db.json`.

Após este passos o servidor deve estar executando na porta 4000 da sua máquina local. Para testar basta acessar através do seu navegador o endereço http://localhost:4000 e obter os dados retornados pela API.
