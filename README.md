# DesafioDIOInvest
Este repositório tem como objetivo aplicar os conceitos de Excel no desenvolvimento de uma ferramenta prática de simulação de investimentos em fundos imobiliários, para a conclusão do desafio proposto no Bootcamp Santander - Excel com Inteligência Artificial - 2º Semestre, da DIO.
---

## 🎯 Objetivos do Projeto 

- Automatizar cálculos financeiros aplicados a FIIs  

---

## ⚙️ Funcionalidades da Planilha 

A solução construída apresenta as seguintes funcionalidades:

- Entrada de valores controlados pelo usuário  
- Automação de cálculos financeiros  
- Projeção mensal do patrimônio  
- Cálculo estimado de dividendos mensais  
- Indicadores consolidados  
- Dashboard gráfico de evolução  

---
## 🖌️ Identidade Visual

Cores:
- VERMELHO: #AF2233
- AMARELO: #FF8D00
- AZUL MARINHO: #0A0F23
- NAVY: #023341
- LARANJA: #F04D07
- VERDE: #59B093

Fontes:
- Título: Broadway, 16
- Corpo: Arial Narrow, 12
  
---
## 📃 Variavéis Criadas

- aporte: valor investido mensalmente
- patrimonio: projeção do valor acumulado no período informado
- qtd_anos: período informado, em anos
- rendimento_carteira: rendimento anual da carteira de investimentos
- salario: valor do salário do usuário
- taxa_mensal: taxa de rendimentos mensal
- perfil_investidor: perfil do usuário
- fii_papel
- fii_tijolo
- fii_hibrido
- fii_fofs
- fii_desenvolvimento
- fii_hotelaria
  
---
## 🔢 Fórmulas Implementadas  

| Cálculo | Fórmula aplicada |
|---|---|
| Sugestão de investimento | salario * 30% |
| Patrimônio acumulado | VF(taxa_mensal;qtd_anos*12;-aporte) |
| Dividendos mensais | patrimonio*taxa_mensal |
| Cenário | VF para cada ano informado |
| Dividendos | Cenário * rendimento_carteira |
| Valor Investido | aporte |
| Percentual Sugerido | PROCV(fii_(Tipo de FII) &"-"& perfil_investidor;Apoio!B2:D22;3;FALSO |
| Valores | aporte* Percentual Sugerido |

---
## 📈 Gráfico
Gráfico de pizza representando o percentual sugerido para cada FIIs de acordo com o perfil de investimento.

---
## 🧮 Apoio
A planilha Apoio contém os percentuais por perfis de acordo com a chave de identificação, usada nos calculos de Percentual Sugerido.

