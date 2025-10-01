Análise de Dados: Arrecadação Fiscal vs Infraestrutura de Saneamento

Descrição do Projeto
Este projeto realiza uma análise integrada de dados governamentais brasileiros, combinando diferentes fontes oficiais para extrair insights sobre desenvolvimento regional e políticas públicas. A abordagem utiliza técnicas modernas de análise de dados para investigar relações entre variáveis socioeconómicas e indicadores de desenvolvimento.
Mais especificamnete, realizei uma análise integrada entre dados de arrecadação fiscal e indicadores de infraestrutura de saneamento básico no Brasil. O objetivo foi investigar possíveis correlações entre o desenvolvimento de infraestrutura pública e a capacidade de arrecadação tributária.

Origem das Bases de Dados
As bases de dados utilizadas neste projeto foram selecionadas através do seguinte prompt enviado ao ChatGPT:

Prompt utilizado:
"
Estou a trabalhar num projeto onde tenho de analisar e relacionar dois conjuntos de dados do portal dados.gov.br. Podes sugerir-me dois datasets deste link: (https://dados.gov.br/dados/conjuntos-datos).
O que preciso especificamente:
Dois conjuntos que possam ser relacionados entre si, que permitam fazer uma análise relevante e com significado. Precisam de ter uma estrutura adequada para analisar em R (como CSV ou Excel).
A análise não precisa de ser muito complexa, mas é suposto conseguir tirar conclusões interessantes.
Contexto do trabalho:
É para uma disciplina de análise de dados em que preciso de fazer integração entre bases de dados e depois representar relações em gráficos.
Os datasets podem ser de qualquer área: saúde, educação, economia, etc. Podem ser dados nacionais ou regionais.
envia-me:
-Os links diretos para fazer download dos datasets
-Uma breve explicação do que cada conjunto contém
-Uma ideia de como poderiam ser relacionados na análise
Obrigada pela ajuda!
"

Bases de Dados Selecionadas:
1. Base de Arrecadação por UF
Link: (https://www.gov.br/receitafederal/dados/arrecadacao-estado.csv/@@download/file)

Descrição: Esta base contém dados mensais de arrecadação tributária federal por Unidade da Federação, incluindo impostos como IRPF, IRPJ, IPI, COFINS, entre outros. Contém 47 variáveis e 8.290 observações, abrangendo o período de 2000 a 2025.

Principais Variáveis:

Ano e Mês: Período de referência

UF: Unidade da Federação

IRPF: Imposto de Renda da Pessoa Física

IRPJ: Imposto de Renda da Pessoa Jurídica

IPI: Imposto sobre Produtos Industrializados

COFINS: Contribuição para o Financiamento da Seguridade Social

OUTRAS RECEITAS ADMINISTRADAS: Receitas adicionais diversas

2. Base do Sisagua (Sistema de Informação de Vigilância da Qualidade da Água)
Link: (https://arquivosdadosabertos.saude.gov.br/dados/sisagua/cadastro_populacao_abastecida_csv.zip)

Descrição: Cadastro nacional de formas de abastecimento de água para consumo humano, contendo informações sobre a população abastecida e tipos de infraestrutura disponível. Possui 37 variáveis e 1.720.737 observações.

Principais Variáveis:

UF e Município: Localização geográfica

Ano de referência: Período dos dados

Canalização: Indicador de disponibilidade de água canalizada

População estimada: Número de pessoas abastecidas

Carro Pipa, Chafariz, Fonte, Cisterna: Formas alternativas de abastecimento

População rural e População urbana: Distribuição demográfica

Resultados Principais
A análise revela uma correlação positiva entre o percentual de municípios com água canalizada e a arrecadação do IRPF no estado do Rio de Janeiro, sugerindo que o desenvolvimento de infraestrutura básica pode estar associado à melhoria de indicadores econômicos e de arrecadação tributária.


Link:
https://madalenarreis.github.io/teste/
