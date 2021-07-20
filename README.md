# Projeto Final Itaú Back End Grupo2(Perseverance)
Repositório para desenvolvimento do desafio do grupo 02 do treinamento ItauTech fornecido pela Gama Academy, edição PCD, julho de 2021.


### 💻 Equipe
- [Bruno Oliveira](https://github.com/BrunoSantosdeOliveira)
- [Carlos Rogerio](https://github.com/crportes/)
- [Cinthia Cruz](https://github.com/Cinthia2406)
- [Daniel Damasceno]()
- [Henrique Ferreira](https://github.com/henriqueandrade01)


## 🚀 Ferramentas Utilizadas

Tecnologias que utilizamos para desenvolver este web client:

- [Visual Studio](https://visualstudio.microsoft.com)
- [Newtonsoft.Json ](https://www.nuget.org/packages/Newtonsoft.Json/)
- [MySql.Data](https://www.nuget.org/packages/MySql.Data/)
- [SQLServer](https://www.microsoft.com/pt-br/sql-server/sql-server-downloads)
- [.NET Core 5.0](https://dotnet.microsoft.com/download/dotnet/5.0)



## 👨🏻‍💻 Objetivos
<p>-Construir uma API .Net  que possua 2 endpoints principais:</p>
<p>-Recuperação de todas as contas bancárias</p>
<p>-Recuperação dos detalhes de 1 conta bancária (inclusive dados do seu titular)</p>



## ⚙️ ESPECIFICAÇÕES
Algumas tecnologias são obrigatórias para este projeto:
Banco de Dados: MySQL
API:.Net
Modelagem de Dados:
Todo cliente possui os seguintes dados para serem cadastrados
<p>● codigo interno</p>
<p>● nome</p>
<p>● cpf</p>
<p>● telefone</p>
<p>● email</p>
<p>Toda conta bancária possui os seguintes dados</p>
<p>● agência</p>
<p>● tipo da conta (0 - conta corrente, 1 - poupança, 2 - investimento)</p>
<p>● saldo</p>
<p>● titular da conta</p>

## ENTREGÁVEIS
Endpoint para consulta de todas as contas (deve retornar uma lista de objetos do tipo
que armazena Conta Bancária):
/contas
Endpoint para consultas do detalhe da conta
/contas/{id}
Todos os dados devem ser retornados em formato JSON

## INSTALAÇÃO DA API(PRE REQUISITOS)

- A [API](https://github.com/crportes/ProjetoFinalItauBackEndGrupo2) do projeto deve estar em execução.

**Clone o projeto e acesse a pasta**

```bash
$ git clone https://github.com/BrunoSantosdeOliveira/ProjetoFinalItauBackEndGrupo2 && cd desafio-afya-front-end
```
</p>Executar comandos no terminal para instalação de extenções:</p>
</p>MySql.Data.EntityFramework 8.0.25</p>
</p>dotnet add package MySql.Data.EntityFramework --version 8.0.25</p>
</p>MySqlConnector 1.3.11</p>
</p>dotnet add package MySqlConnector --version 1.3.11</p>
</p>Newtonsoft.Json 13.0.1</p>
</p>dotnet add package Newtonsoft.Json --version 13.0.1</p>
