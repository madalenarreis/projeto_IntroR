## Análise de Dados: Arrecadação Fiscal vs Infraestrutura de Saneamento

## Link do site:  https://madalenarreis.github.io/projeto_IntroR/

## Descrição do Projeto:
Este projeto realiza uma análise integrada de dados governamentais brasileiros, combinando diferentes fontes oficiais para extrair insights sobre desenvolvimento regional e políticas públicas. A abordagem utiliza técnicas modernas de análise de dados para investigar relações entre variáveis socioeconómicas e indicadores de desenvolvimento.

Mais especificamente, realizei uma análise integrada entre dados de arrecadação fiscal e indicadores de infraestrutura de saneamento básico no Brasil. O objetivo foi investigar possíveis correlações entre o desenvolvimento de infraestrutura pública e a capacidade de arrecadação tributária.

## Origem das Bases de Dados
As bases de dados utilizadas neste projeto foram selecionadas através do seguinte prompt enviado ao ChatGPT:
### Prompt utilizado:
"
Estou a trabalhar num projeto onde tenho de analisar e relacionar dois conjuntos de dados do portal dados.gov.br. Podes sugerir-me dois datasets deste link: (https://dados.gov.br/dados/conjuntos-datos).
O que preciso especificamente:

Dois conjuntos que possam ser relacionados entre si, que permitam fazer uma análise relevante e com significado. Precisam de ter uma estrutura adequada para analisar em R (como CSV ou Excel).
A análise não precisa de ser muito complexa, mas é suposto conseguir tirar conclusões interessantes.

Contexto do trabalho:
É para uma disciplina de análise de dados em que preciso de fazer integração entre bases de dados e depois representar relações em gráficos.
Os datasets podem ser de qualquer área: saúde, educação, economia, etc. Podem ser dados nacionais ou regionais.
envia-me:
--Os links diretos para fazer download dos datasets

--Uma breve explicação do que cada conjunto contém

--Uma ideia de como poderiam ser relacionados na análise

Obrigada pela ajuda!
"

## Bases de Dados Selecionadas:
### 1. Base de Arrecadação por UF
Link: (https://www.gov.br/receitafederal/dados/arrecadacao-estado.csv/@@download/file)

Esta base é disponibilizada pela Receita Federal do Brasil e contém registos mensais da arrecadação de tributos federais, organizados por Unidade da Federação. A sua abrangência é nacional, cobrindo todas as 27 UFs ao longo dos anos 2000- 2025.

Os dados permitem analisar a capacidade económica e contributiva de cada estado, detalhando a arrecadação de impostos como IRPF, IRPJ e IPI. Esta informação é crucial para compreender disparidades regionais, avaliar políticas fiscais e estudar a evolução da atividade económica no território nacional.

### 2. Base do Sisagua (Sistema de Informação de Vigilância da Qualidade da Água)
Link: (https://arquivosdadosabertos.saude.gov.br/dados/sisagua/cadastro_populacao_abastecida_csv.zip)

O Sistema de Informação de Vigilância da Qualidade da Água (SISAGUA) é gerido pelo Ministério da Saúde e compila informações sobre as formas de abastecimento de água nos municípios brasileiros. A base possui abrangência nacional e é atualizada anualmente, detalhando a situação do acesso à água em todo o país.

Através destes dados, é possível avaliar as condições de saneamento básico da população, identificando os tipos de abastecimento disponíveis (como rede canalizada, poços ou chafarizes) e a população atendida por cada um. A base suporta análises sobre desigualdades regionais, eficácia de políticas públicas de saneamento e a relação entre acesso à água e indicadores de desenvolvimento social.


