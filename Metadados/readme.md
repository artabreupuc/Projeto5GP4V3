# Navegação pelos metadados

## Essa pasta sera utilizada para contextualizar e armazear os metadados do projeto.

Dando inicio a navegação, temos 4 pastas, cada pasta representa uma nova edição da prova encceja por ano, temos os anos: **2018, 2019, 2020, 2022.**

Dentro de cada pasta teremos os seguintes pastas: Dados, dicionario, inputs, leia-me, matriz de referencia e sqlscrpitsgerais

![MetaDados](https://github.com/artabreupuc/Projeto5GP4V3/assets/141786256/7deb7629-eaa6-4b7c-91f0-9a2d6beaa9b8)

### **Contexto dos dados:**

Conforme a realização das provas durante os anos já listados, as matrizes, avaliações socioeconomicas e estruturas foram se alterando. Com base no que foi dito,

---

* Pasta DADOS:

Para armazencar da melhor formas todas as bases de dados utilizadas no projeto

---

* Pasta DICIONÁRIO DE DADOS:

Ao selecionar essa pasta, dois arquivos estãoa disponiveis, basicamente o mesmo conteudo, mas em formatos diferentes, um em formato xlsx e o outro em ODS. Dentro de cada arquivo, existem 4 pastas de trabalhos, são elas: NACIONAL REGULAR, NACIONALL PPL, QUESTIONÁRIO NACIONAL PPL E ITENS PROVA. Dentro de cada uma dessas pastas, teremos uma tabela chamada DICIONÁRIO DE VARIÁVEIS com as seguintes colunas:

Nome da coluna | Função
--------- | ------
NOME DA VARIÁVEL | Vai falar o nome de uma variavel
Descrição | Vai informar o que a Variavel pode armazenar
Variaveis Categoricas | Vai responder as variaveis que tem categorias, tendo duas sub colunas, a Categoria que vai informar o valor numerico da categorias numericas e a descrição vai passar o siginificados de cada categoria 
Tamanho | Vai descrever a quantidade de caracteres do valor da variavel
Tipo | Vai descreve o tipo da variavel

Para entender de forma mais detalhada cada arquivo que foi sendo alterando com o decorrer da edição das provas, basta ir selecioando as pastas dos anos, que estão logo acima.

---

* Pasta MATRIZ DE REFERENCIA:

Ao selecionar essa pasta, temos duas pastas disponiveis, a pasta ensino médio e pasta ensino fundamental. Dentro da pasta ENSINO FUNDAMENTAL, temos 4 arquivos em PDF, uma para cada matriz de conhecimento, são elas: **CIENCIAS**, **HISTÓRIA e GEOGRAFIA**, **LÍNGUA PORTUGUESA** E **MATEMÁTICA**.

Já dentro da pasta ENSINO MÉDIO, temos 4 arquivos em PDF, uma para cada matriz de conhecimento, são elas: CIÊNCIAS DA NATUREZA E SUAS TECNOLOGIAS, **CIÊNCIAS HUMANAS E SUAS TECNOLOGIAS**, **LINGUAGENS**, **CÓDIGOS E SUAS TECNOLOGIAS**, **MATEMÁTICA E SUAS TECNOLOGIAS**

---

* Pasta SQLSCRIPTSGERAIS:

Ao selecionar essa pasta criada no projeto anterior, existem alguns scripts em sql usados para processos de padronização de dados e manipulação de registros. Futuramente, esses scrpits podem uteis.

---

* Pasta INPUTS EM SPS E SAS:

Ao selecionar essa pasta, existem arquivos em formato sas e sps que ajudam a manipular bases de dados do projeto.

---

### Navegação pelo Repositorio de MetaDados:

Segue uma explicação de como é feita a utilização do repositorio e as camadas do mesmo.

* **Branchs**:

**Master:** É o "Ambiente de produção" do projeto, essa branch vai armazenar todos os codigos e documentações oficiis. Sempre sendo a prioridade no quesito de vercionamento atualizado.

**Bastidores:** É o "Ambiente de teste" do projeto, onde sera feitas todas as alterações de codigos e documentações antes de ser oficializada e mergeada para a o "Ambiente de Produção", a branch Master.
