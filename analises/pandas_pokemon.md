# Pokemon<img src = "../imagens/pokebola.png" height = 50 width = 60>(PyPanda) 

<img src = "../imagens/pokemon.png">

### Organização do Banco de Dados:

 Para a organização do banco de dados, foi criado um esquema de banco relacional. Dessa forma, os dados retirados do dataset podem ser distribuídos e retirados para análise com maior praticidade.

 <img src = "../imagens/banco_teste.png">

 Após a esquematização do banco relacional. Foi utilizado o Pandas para a criação de suas tabelas em CSV e depois relacionados em seu arquivos principal.

 ##### Clique [aqui](../cod_programacao/T_Pokemon.ipynb) para ver o código da programação. 🖥️

 ### Tratamento do Banco de Dados:

Criado uma função que identifica as colunas que usam dados semelhanteas a fim de, criar uma tabela de correlação, nesta nova tabela um numero de SK (ID) foi gerado para cada registro unico da soma das colunas semelhantes.

 ### Finalização do Tratamento de dados:

 Na segunda etapa, substituimos os valores em TEXTO do arquivo original para os SK das novas tabelas craidas, e assim reduzindo o tamanho do arquivo do bando em 27%.


