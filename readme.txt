Este pequeno projeto foi um desafio, aonde dado um DANFE (Documento Auxiliar de Nota Fiscal Eletrônica) em .xml, faço a análise dos dados
e então crio as tabelas que contém as informações de uma nota fiscal eletrônica.
Via Python, é feita a conexão com um servidor local MySql, e então são criados os scripts de criação/inserção de dados nas tabelas. Após isso, o documento é percorrido
e os dados são armazenados em listas, que são convertidas a tuplas, para então serem inseridos no banco.
Na documentação, o modelo entidade-relacionamento mostra os relacionamentos das tabelas, e o dicionário de dados mostra os significados das colunas.
Os primeiro código a ser executado é o extraction.ipynb, e então o challenge.ipynb

Pontos de melhoria:

-Explorar melhor a modelagem star schema.
-Criação de uma nova tabela de lacres (Para isso, devo refinar a análise dos dados)
-Separar melhor as etapas do processamento
-Validação pós-processamento, para validar se os dados na database estão batendo com os do documento
-Utilizar orientação a objetos para melhoria da estrutura
-Aprimorar a função de pegar id por coluna para pegar qualquer coluna por coluna
