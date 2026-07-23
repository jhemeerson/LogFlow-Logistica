# LogFlow-Logistica
Performance &amp; Diagnóstico Logístico.

Análise estratégica de entregas, clientes e vendedores.

Abaixo, divido a avaliação nas três visões solicitadas, destacando a situação atual, pontos críticos e insights acionáveis voltados para a tomada de decisão gerencial.

[Relatório Online: Logística.](https://app.powerbi.com/view?r=eyJrIjoiNjcwNWRhYzItMmY0OC00NDA1LWFmNjctMjA0NjE3NDI4ZGQ4IiwidCI6IjY1OWNlMmI4LTA3MTQtNDE5OC04YzM4LWRjOWI2MGFhYmI1NyJ9)


## Visão Entregas (Operations & SLA)

* Volume Total: 54 Mil entregas processadas.

* Nível de Serviço (OTD): O OTD atual está em **87%** (46.716 no prazo vs. 6.971 atrasadas).

* Sazonalidade & Queda Repentina: O volume de entregas manteve-se estável e em nível alto de Janeiro a Julho (com pico em Fevereiro com 5.832 entregas e Julho com 5.490). Porém, a partir de Agosto (4.713) ocorre uma queda drástica, atingindo o **menor patamar em Setembro** (2.475) e encerrando Dezembro com apenas 3.017 entregas.

* Concentração por Canal: Os canais **Canal07** (9.152) e **Canal12** (9.086) concentram a maior parte da operação.

* Gargalos Regionais (Cidades): Cidades específicas registram volumes desproporcionais de atraso (ex: **Cidade 104** com 134 atrasos, **Cidade 101** com 91 atrasos e **Cidade 106** com 61 atrasos).

#### Insights Acionáveis para Gestão

1. Investigar Causa Raiz do Recuo no 2º Semestre: Uma queda repentina de ~45% no volume de entregas a partir de Agosto/Setembro acena para gargalos na cadeia de suprimentos (falta de estoque/ruptura), perda de contratos ou mudança de regras comerciais. É urgente alinhar Operações com Vendas para diagnosticar a causa.

2. Plano de Ação para Polígonos Críticos (Cidades 104 e 101): Fazer re-routing ou rever transportadoras operando nestas praças específicas, pois concentram picos isolados de falha na entrega.

3. Redistribuição de Capacidade nos Canais Topo (07 e 12): Por responderem pelo maior volume operacional, qualquer gargalo de separação (picking/packing) nesses canais gera impacto direto no OTD global.

## Visão Clientes (Customer Experience & Retention)

* Base Total: 4 Mil clientes ativos.

* Experiência do Cliente (SLA Crítico): Identifica-se uma concentração altíssima de atrasos recorrentes em clientes específicos.

* Exemplo alarmante: O cliente ID 141161 teve 50 entregas atrasadas contra apenas 7 no prazo (SLA de ~12%). O cliente ID 118746 teve 49 atrasadas e apenas 1 no prazo.

* Concentração de Vendas (Top Clients): O maior cliente em volume é o ID 153815 (108 compras), seguido do ID 167145 (101 compras).

* Distribuição Geográfica de Clientes por Região: A região Norte (14.751) e Sudeste (13.366) lideram o volume de interações, seguidas por Nordeste (7.173 e 8.989) e canais digitais/televendas.

#### Insights Acionáveis para Gestão

1. Risco Iminente de Churn (SLA por Cliente): Clientes com taxa de atraso superior a 80% (como IDs 141161, 118746, 52909 e 167711) estão sob forte risco de cancelamento e insatisfação extrema.

* Ação: Criar uma força-tarefa de CS/Key Account Management para entrar em contato com essa lista prioritária, oferecendo mitigação de frete ou SLA dedicado.

2. Gargalo Concentrado no Canal 07 e Canal 11: Na tabela de clientes atrasados, os canais Canal07 e Canal11 repetem-se constantemente. É necessário auditar a malha logística e o parceiro transportador vinculado especificamente a esses canais.

## Visão Vendedores (Sales & Field Operations)

* Força de Vendas: 95 Vendedores atendendo 149 Cidades.

**Desempenho vs. Meta:**

* Volume Realizado: 54 Mil entregas para uma meta de 60 Mil (realizado em 90% da meta global).

* OTD Realizado: 87%, contra a meta estipulada de 90% (desvio de 3 p.p.).

**Desempenho por Equipe/Região:**

* A equipe Norte lidera em entregas (12.908 no prazo / 1.845 atrasadas), seguida do Sudeste (12.365 no prazo / 1.003 atrasadas).

* Desequilíbrio de SLA por Canal de Venda: A Internet apresenta um volume proporcional de atrasos muito elevado (4.234 no prazo vs. 1.609 atrasadas — quase 27.5% de atraso), assim como o Sul (1.294 atrasadas para 5.879 no prazo).

#### Insights Acionáveis para Gestão

1. Adequação do Prometido vs. Entregue no E-commerce (Internet): O canal Internet apresenta o pior índice relativo de OTD da operação. Isso indica que a promessa de prazo no checkout (Lead Time de vitrine) está desalinhada com a capacidade real de entrega da logística.

* Ação: Ajustar o Lead Time exibido no site em +1 ou +2 dias para evitar quebras de expectativa e quedas na nota de classificação do vendedor.

2. Plano de Incentivo / Gamificação Atrelado ao OTD: Vendedores das faixas inferiores (3 ou 4 estrelas na classificação) muitas vezes sofrem impactos em suas comissões por entregas não concluídas a tempo. Deve-se alinhar a meta de volume à qualidade logística da região do vendedor.



## 📊 Resumo Executivo da Matriz de Decisão

> **Visão Geral:** Quadro estratégico com os principais gargalos identificados na operação logística e as respectivas ações corretivas recomendadas para a liderança.

| Frente | Problema Crítico | Causa Provável | Ação Direta Recomendada |
| :--- | :--- | :--- | :--- |
| ⚙️ **Operacional** | Queda brusca de volume pós-Julho (~45%) | Ruptura de estoque, gargalos em CD ou perda de grandes canais. | Sincronizar planejamento de *demand forecasting* com o time de S&OP. |
| 👥 **Clientes** | Clientes "Top Atrasos" (>80% de falha no SLA) | Gargalo recorrente concentrado especificamente nos **Canais 07 e 11**. | Atendimento VIP preventivo (CS) e auditoria imediata nos parceiros de frete desses canais. |
| 🛒 **Comercial** | Canal Internet com alta taxa de atraso (~27.5%) | Promessa de entrega (Lead Time de vitrine) irrealista no checkout do site. | Ajustar regra de cálculo de prazo de entrega no e-commerce (+1 ou +2 dias).

<br>

[Portfólio:](https://portfolio-jhemerson-oliveira.lovable.app/)

[LinkedIn: Jhemerson Oliveira](https://www.linkedin.com/in/jhemerson-oliveira/)
