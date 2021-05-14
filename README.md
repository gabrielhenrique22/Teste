
# Teste  

#Item 1
Business inteligence significa modelo , ou plataforma de ingeligência 
artificial integrado voltado para análise, gestão, cordenação 
ou aprimoramento de dados voltado ao mercado de negócios (empresarial).

##Item 2
Processo de extração, transformação e carregamento (ETL)
Exemplos: 
 	IBM InfoSphere DataStage
	Microsoft SQL Server Integration Services (SSIS)

O principal objetivo desse recurso é garantir a integração de dados,
 através de várias tarefas utilizando um data warehousing

 No SQL Server , cada coluna,
expressão e parâmetro tem um tipo de dados relacionado, dados inteiros,
 dados de caractere, dados monetários, data e hora, 
a função do SQL server é integrar e acessar estes dados de forma 
facil e simplificada para seu Usuário.


###Item 3

Ferramenta Número 1:  Excel  (mais antiga e mais famosa, e mais usada)
Ferramenta Número 2: Power Pivot: Ferramenta de modelagem de dados 
Ferramenta Número 3: Power Query: Ferramenta de transformação de dados
e integrada no Power BI que seria a ferramenta de Visualização de dados

####Item 4 

A tabela fato é a principal tabela do Data Warehouse,
ela vai conectar nas dimensões. Nessa tabela são armazenadas 
chaves que servem para ligar os dados das dimensões com a fato.
Dimensões ( para os Dados Descritivos ) e Fatos ( para os dados
que são métricas ), por Exemplo : Clientes, Produtos, Lojas, 
Funcionários, são todos dimensões, nao numerais ( são caracteres).
métricas = Numerais.


#####Item 5

Modelagem mais usada no Power BI : Power Query transformador de dados 
para criação de um data warehouse e graficos por filtros: (cidades, 
clientes, produtos e vendedor)

######Item 6 
A chave substituta (surrogate) ou artificial é um dado que é criado para 
fins de controle do banco de dados, ela não existe fora da solução de software
sendo desenvolvida. Geralmente é um ID numérico único, estável (não muda)
sequencial e auto incrementado. Você tem algum controle sobre ele.

A chave natural é aquela que existe fora da aplicação e está sendo 
usada como chave. Um CPF ou CNPJ é uma chave natural, ela existe
independente do banco de dados. Pode ser até um nome, embora incomum,
pode ser um e-mail, telefone, ou número de algum documento.

#######Item 7
1:1 significa que para cada linha de uma tabela será referenciada em uma linha 
na ouna outra tabela 
1:N significa que para cada linha em uma tabela será referenciada diversas linhas 
na outra tabela.

#########Item 8
O conceito de drill-down está diretamente relacionado com o fato de sairmos de 
um nível mais alto da hierarquia e buscarmos informações detalhadas (níveis menores).
Drill down

drill Up: é o contrário do Drill Down, ocorre quando o usuário aumenta a granularidade, 
diminuindo o nível de detalhamento da informação;

Exemplo : Quantidade de produtos vendidos X em tal cidade:
municipio < Cidade < Capital < estado < País 
Drill down<---------------------------drill Up
