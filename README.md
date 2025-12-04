# 🎭 Y.Afisha — Análise de Produto, Vendas e Marketing

## Sobre o Projeto
O projeto simula uma rotina real de análise na Y.Afisha da **Y.Afisha** e sua primeira missão é ajudar a empresa a gastar melhor em marketing. Para isso, você analisa o comportamento dos usuários, compras, ciclos de retenção e retorno financeiro das campanhas.

## 🎯 Objetivo Principal
Responder três perguntas essenciais:
1. **Como as pessoas usam o produto?**
2. **Quando começam a comprar e quanto geram de receita?**
3. **Quais canais de marketing realmente valem o investimento?**

## 📌 O Que Foi Feito

### **1. Carregamento e Preparação dos Dados**
Arquivos utilizados:
- `visits_log_us.csv` — sessões, dispositivos e origem de anúncio.
- `orders_log_us.csv` — pedidos e receitas.
- `costs_us.csv` — despesas por canal.

Ações executadas:
- Conversão de datas e tipos numéricos.
- Consolidação do período (2017–2018).
- Ajuste da granularidade: dia/semana/mês.
- Identificação de sessões, usuários únicos, duração e recorrência.

---

### **2. Métricas de Produto**
- Usuários ativos diários, semanais e mensais (DAU/WAU/MAU).
- Número de sessões por dia.
- Duração média de sessão.
- Frequência de retorno por coortes.

---

### **3. Métricas de Vendas**
- Tempo até a primeira compra por coorte.
- Número médio de pedidos por usuário.
- Ticket médio e distribuição de receitas.
- **LTV (Lifetime Value)** por canal e coorte.

---

### **4. Métricas de Marketing**
- Gastos totais e por canal.
- **CAC (Custo de Aquisição de Cliente)**.
- **ROI por canal**.
- **ROMI por idade da conta** — velocidade de payback.
- Comparação por dispositivo e origem ao longo do tempo.

Visualizações criadas:
- Linha do tempo de gastos.
- CAC × ROI.
- Heatmap de ROMI.
- LTV por canal.
- Atividade dos usuários ao longo do ciclo.

---

### **5. Conclusão e Recomendação Final**
**Escalar:** Canal **1**, com ROI ~1,7 e CAC competitivo. Melhor relação retorno/custo.

**Otimizar:** Canal **2**. Apesar do CAC alto, ainda entrega ROI acima de 1.

**Cortar/Estancar:** Canal **3**, pior custo-benefício. ROI < 0,5 e CAC mais alto.

**Potencial para escalar:** Canais **4, 5, 9 e 10**, caso o **LTV** confirme sustentabilidade.

Fundamentação:
- **ROI** para medir retorno real de cada real investido.
- **CAC** para eficiência de aquisição.
- **ROMI** para velocidade de recuperação do investimento.

Visão geral:
- Canal 1 é o “golden child”: barato e lucrativo.
- Canal 2 dá sinais positivos se otimizado.
- Canal 3 drena orçamento e destrói margem.
- Canais 4, 5, 9 e 10 são apostas promissoras se o LTV sustentar o gasto.
- A performance geral em 2018 caiu — payback mais lento sugere revisar o mix de canais.

---

## 🚀 Resultado Esperado
Ao final do projeto, você tem:
- análise completa de produto, comportamento e receita;
- visão clara da eficiência dos canais;
- recomendações práticas para realocar investimento;
- base sólida para orientar decisões de marketing baseadas em dados.
