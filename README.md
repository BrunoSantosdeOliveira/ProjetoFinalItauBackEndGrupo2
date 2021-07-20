# ProjetoFinalItauBackEndGrupo2
Repositório para desenvolvimento do desafio do grupo 02 do treinamento ItauTech, edição PCD, julho de 2021.


### 💻 Equipe
- [Bruno Oliveira](https://github.com/BrunoSantosdeOliveira)
- [Carlos Rogerio](https://github.com/crportes/)
- [Cinthia Cruz](https://github.com/Cinthia2406)
- [Daniel Damasceno]()
- [Henrique Ferreira](https://github.com/henriqueandrade01)

Ferramentas Utilizadas
Visual Studio
WhatsApp
Banco de dados
SQLServer.

OBJETIVOS
1. Construir uma API .Net  que possua 2 endpoints principais:
a. Recuperação de todas as contas bancárias
b. Recuperação dos detalhes de 1 conta bancária (inclusive dados do seu titular)

ESPECIFICAÇÕES
Algumas tecnologias são obrigatórias para este projeto:
Banco de Dados: MySQL
API:.Net
Modelagem de Dados:
Todo cliente possui os seguintes dados para serem cadastrados
● codigo interno
● nome
● cpf
● telefone
● email
Toda conta bancária possui os seguintes dados
● agência
● tipo da conta (0 - conta corrente, 1 - poupança, 2 - investimento)
● saldo
● titular da conta
ENTREGÁVEIS
Endpoint para consulta de todas as contas (deve retornar uma lista de objetos do tipo
que armazena Conta Bancária):
/contas
Endpoint para consultas do detalhe da conta
/contas/{id}
Todos os dados devem ser retornados em formato JSON

INSTALAÇÃO DA API


PRE REQUISITOS
Instalação do .NET Core 5.0
https://dotnet.microsoft.com/download/dotnet/5.0
Executar comandos no terminal para instalação de extenções:
MySql.Data.EntityFramework 8.0.25
dotnet add package MySql.Data.EntityFramework --version 8.0.25
MySqlConnector 1.3.11
dotnet add package MySqlConnector --version 1.3.11
Newtonsoft.Json 13.0.1
dotnet add package Newtonsoft.Json --version 13.0.1
