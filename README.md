ETL_ProjetoFinal

Um investidor estrangeiro que
controla um fundo de investimentos global, está avaliando incluir ações de
empresas brasileiras de capital aberto em sua carteira e para tomar a decisão contratou
você para fazer um ETL de um dataset com os dados financeiros de 22 empresas
brasileiras de capital aberto.


Sua missão é extrair para o
ambiente Python/Pandas estes dados da base que está em armazenada no link:  https://tinyurl.com/4d7rk5s5
e após isso verificar se a base está   com
os atributos nos formatos esperados (número para as contas: receita, custo,
lucro, ebit, custo, ativo pl e passivo e string para empresa e setor, lembrando
que no ambiente pandas string fica classificada como object). Caso esteja tudo
certo com o formato dos números, você deverá ainda no ambiente python/pandas
gerar um arquivo csv  chamado “invest” pelo
colab e fazer o download desse arquivo para sua máquina.


Em seguida você deverá subir esse
arquivo para o seu google drive, após isso, abra o looker studio e pelo
conector do google planilhas carregue a base chamada invest.


No ambiente do looker studio você
deverá criar os seguintes campos calculados:

1 – ROA  = (lucro / ativo)


2 – ROE = (lucro / pl)


3 – Margem (lucro / receita)


4 - % CP = (pl / ativo)


5 - % CT = (passivo/ativo)

Agora você deverá criar um gráfico de cartão para cada uma das 5 métricas calculadas e exibir o resultado agrupado pela média.
Em seguida insira uma tabela com o nome da empresa e seus respectivos valores de ROE. Após isso, insira 3 controles com filtros,
sendo: 1 do tipo lista suspensa para o campo setor, outro do tipo caixa de entrada para o campo empresa e o último do tipo controle deslizante para o campo ROE.
