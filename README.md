# Atividade 3 - Limpeza, Tratamento e Exploração de Dados
**Este projeto tem como objetivo realizar um processo completo de limpeza, tratamento e exploração inicial de uma base de dados (atividade3_dataset.csv) para prepará-la para análises futuras. O script foi desenvolvido em Python, utilizando as bibliotecas Pandas e Matplotlib.**

# ⚙️Visão Geral do Projeto
O script segue um fluxo de trabalho padrão em Ciência de Dados, executando as seguintes etapas:
```
Configuração do Ambiente: Conexão com o Google Drive para acesso à base de dados.

Leitura e Inspeção: Carregamento do arquivo CSV e análise inicial dos dados (tipos, valores nulos e duplicados).

Tratamento de Dados:

Preenchimento de valores ausentes (com a média para colunas numéricas e a moda para categóricas).

Remoção de linhas duplicadas.

Padronização e Conversão:

Padronização de valores inconsistentes (ex: SÃO PAULO para SP).

Conversão de colunas de data e números armazenados como texto para os formatos corretos.

Análise e Visualização:

Geração de estatísticas descritivas para a base limpa.

Criação de gráficos de distribuição e correlação para visualização dos dados.

Criação de Nova Coluna: Adição de uma coluna binária (Acima_da_Media) para indicar se um valor está acima da média de sua respectiva coluna numérica.

Exportação: Salvamento do novo DataFrame limpo e tratado em um arquivo CSV (base_limpa.csv).
```
# 🛠️ Tecnologias e Bibliotecas Utilizadas
1. Python: Linguagem de programação principal.

2. Pandas: Essencial para a manipulação, limpeza e análise dos dados.

3. Matplotlib e Seaborn: Utilizadas para a visualização dos dados e geração dos gráficos.

# 📂 Como Usar
Para rodar este script, siga os passos abaixo:

**Garanta que o arquivo atividade3_dataset.csv esteja salvo no seu Google Drive.**

**Abra o script em um ambiente como o Google Colab**

**Execute a primeira célula para conectar ao Google Drive**

**Execute as demais células na ordem para que a limpeza e a análise sejam feitas corretamente.**
