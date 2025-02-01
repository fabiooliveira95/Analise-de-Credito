# Análise de Crédito Bancário

Este projeto tem como objetivo explorar e analisar dados de clientes de uma instituição financeira para entender os fatores que influenciam a inadimplência (default) dos clientes. O conjunto de dados contém informações como idade, sexo, escolaridade, estado civil, salário anual, tipo de cartão, meses de relacionamento, quantidade de produtos, iterações nos últimos 12 meses, meses inativos nos últimos 12 meses, limite de crédito, valor das transações nos últimos 12 meses e quantidade de transações nos últimos 12 meses.

## Objetivo

O principal objetivo deste projeto é identificar padrões e comportamentos que possam explicar por que um cliente deixa de honrar suas dívidas (inadimplência) com base em outros atributos, como salário, escolaridade e movimentação financeira.

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

1. **Exploração de Dados**: 
   - Leitura dos dados em um DataFrame pandas.
   - Análise inicial da estrutura dos dados.
   - Verificação de dados faltantes.
   - Análise de atributos categóricos e numéricos.

2. **Transformação e Limpeza de Dados**:
   - Correção do schema das colunas.
   - Remoção de dados faltantes.
   - Conversão de colunas categóricas para numéricas quando necessário.

3. **Análise de Dados**:
   - Análise de proporções de clientes adimplentes e inadimplentes.
   - Exploração de correlações entre variáveis.
   - Visualização de dados para identificar padrões.

4. **Conclusões**:
   - Identificação de fatores que influenciam a inadimplência.
   - Sugestões para mitigação de riscos de crédito.

## Dados

O conjunto de dados utilizado neste projeto está no formato CSV e contém as seguintes colunas:

- `id`: Identificador único do cliente.
- `default`: Indicador de inadimplência (0 = adimplente, 1 = inadimplente).
- `idade`: Idade do cliente.
- `sexo`: Sexo do cliente (M ou F).
- `dependentes`: Número de dependentes do cliente.
- `escolaridade`: Nível de escolaridade do cliente.
- `estado_civil`: Estado civil do cliente.
- `salario_anual`: Faixa salarial anual do cliente.
- `tipo_cartao`: Tipo de cartão do cliente.
- `meses_de_relacionamento`: Tempo de relacionamento com a instituição financeira em meses.
- `qtd_produtos`: Quantidade de produtos contratados pelo cliente.
- `iteracoes_12m`: Número de iterações com a instituição nos últimos 12 meses.
- `meses_inativo_12m`: Número de meses inativos nos últimos 12 meses.
- `limite_credito`: Limite de crédito do cliente.
- `valor_transacoes_12m`: Valor total das transações nos últimos 12 meses.
- `qtd_transacoes_12m`: Quantidade de transações nos últimos 12 meses.

## Requisitos

Para executar este projeto, você precisará das seguintes bibliotecas Python:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

Você pode instalar as dependências necessárias usando o seguinte comando:

```bash
pip install pandas numpy matplotlib seaborn

git clone https://github.com/fabiooliveira95/analise-de-credito-bancario.git

cd analise-de-credito-bancario

jupyter notebook analise_de_credito-bancario.ipynb


Este `README.md` fornece uma visão geral do projeto, incluindo objetivos, estrutura, dados utilizados,
requisitos,instruções de execução, resultados e conclusões. Você pode personalizá-lo conforme necessário para refletir melhor o seu trabalho.
