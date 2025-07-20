# Análise de Variação nos Preços de Ações da Coca-Cola - Dow Jones

Este exercício utiliza dados da bolsa de valores dos EUA, Dow Jones, para analisar as flutuações nos preços das ações da Coca-Cola ao longo de um determinado período. A base de dados pode ser baixada [aqui](link_para_os_dados).

## Objetivo
O objetivo principal desta análise é entender e destacar as variações significativas nos preços das ações da Coca-Cola, identificando padrões e momentos de instabilidade no mercado.

## Conjunto de Dados

O dataset contém as seguintes colunas principais:

| Coluna                          | Descrição                                    |
|--------------------------------|----------------------------------------------|
| quarter                        | Trimestre do ano                             |
| stock                         | Código da ação                               |
| date                          | Data da observação                           |
| open                          | Preço de abertura da ação                    |
| high                          | Preço máximo registrado                      |
| low                           | Preço mínimo registrado                      |
| close                         | Preço de fechamento da ação                  |
| volume                        | Volume negociado                             |
| percent_change_price           | Percentual de variação do preço              |
| percent_change_volume_over_last_wk | Variação percentual do volume em relação à semana anterior |
| previous_weeks_volume          | Volume da semana anterior                     |
| next_weeks_open               | Preço de abertura da próxima semana          |
| next_weeks_close              | Preço de fechamento da próxima semana        |
| percent_change_next_weeks_price | Variação percentual do preço na próxima semana |
| days_to_next_dividend          | Dias até o próximo dividendo                   |
| percent_return_next_dividend   | Retorno percentual esperado do próximo dividendo |

---

## Método
1. **Download dos Dados:**
   - Utilizamos o pacote wget para baixar os dados da bolsa de valores Dow Jones.
  

2. **Análise de Variação de Preços:**
   - Fizemos uma análise dos preços iniciais das ações da Coca-Cola.
   - Identificamos flutuações notáveis ao longo do período analisado.
   - Destacamos uma queda de aproximadamente 5% nos preços, indo de 65.88 em 1/07/2011 para 62.70 em 1/14/2011.
   - Observamos variações contínuas nos preços, indicando possível instabilidade no mercado ou influências externas.
   - O pico de preço em 5/20/2011 e a subsequente queda até o fechamento em 6/24/2011 sugerem um período de volatilidade nos preços das ações da Coca-Cola.


## Análises Realizadas

### Variação do Preço de Fechamento das Ações da Coca-Cola

*A imagem abaixo ilustra os valores de fechamento das ações ao longo do tempo.*

<img width="1322" height="791" alt="Captura de tela 2025-07-20 120627" src="https://github.com/user-attachments/assets/b0defbdf-d0a1-4823-a536-b820a79bce52" />

---

### Visualização dos Quatro Valores no Mesmo Gráfico

*Este gráfico permite comparar os valores de abertura, fechamento, máximo e mínimo das ações simultaneamente.*
<img width="837" height="656" alt="Captura de tela 2025-07-20 120803" src="https://github.com/user-attachments/assets/7ad7557b-4aef-4dd9-a824-73ef3f63b362" />

---

### Variação do Preço de Abertura das Ações da Coca-Cola

*Gráfico demonstrando os valores de abertura das ações ao longo do tempo.*
<img width="927" height="693" alt="Captura de tela 2025-07-20 120906" src="https://github.com/user-attachments/assets/38545840-9351-41fc-bb65-a22abc7792f2" />


---

### Variação do Preço de Fechamento das Ações da Coca-Cola ao Longo do Tempo
<img width="1397" height="766" alt="Captura de tela 2025-07-20 121020" src="https://github.com/user-attachments/assets/437809b4-27b6-4643-ad28-dca58cd111ba" />




---

### Variação do Preço de Abertura e Fechamento das Ações da Coca-Cola ao Longo do Tempo
<img width="1340" height="772" alt="Captura de tela 2025-07-20 121145" src="https://github.com/user-attachments/assets/d34a88c8-62d1-422e-b9fa-2325841ca427" />





---

## Insight Principal

Durante o período analisado, notou-se que o preço das ações da Coca-Cola sofreu flutuações notáveis. Em 07/01/2011, o preço de fechamento estava em 65,88, caindo aproximadamente 5% para 62,70 em 14/01/2011. Nos dias seguintes, os preços continuaram a oscilar, sugerindo um possível ambiente de instabilidade no mercado ou influências externas afetando os valores.

A análise mostra um padrão contínuo de variações, com momentos de alta seguidos por quedas e estabilizações. Esse comportamento indica um mercado volátil durante o período.

Destaca-se o pico do preço em 20/05/2011 e a queda subsequente até o fechamento em 24/06/2011, o que evidencia um período de alta volatilidade nas ações da Coca-Cola.

Esses resultados ilustram como diversos fatores podem impactar o preço das ações, criando diferentes tendências ao longo do tempo.


## Tecnologias Utilizadas

- Python (Pandas, Matplotlib, Seaborn)
- wget (para download dos dados)
- Jupyter Notebook (para desenvolvimento e visualização)



