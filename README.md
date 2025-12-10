# 📊 Painel Crédito Fácil  
Dashboard Executivo de Crédito, Risco e Rentabilidade

---

## 📌 Visão Geral

O Painel **Crédito Fácil** centraliza, monitora e analisa todo o ciclo operacional do produto de crédito consignado privado.  
Ele foi construído para fornecer **visibilidade executiva**, **governança de risco** e **inteligência financeira** para tomada de decisão rápida e assertiva.

O modelo consolida dados de contas, liberações, limites, elegibilidade, receitas e comportamento de consumo, transformando tudo em um storytelling executivo claro e orientado ao negócio.

---

## 🎯 Objetivos Principais

- Medir o **crescimento da carteira** (volume + quantidade).
- Acompanhar a **rentabilidade líquida** do produto.
- Controlar a **capacidade financeira** e risco de alavancagem.
- Avaliar **aderência** entre elegíveis e utilizadores.
- Identificar **grupos que mais consomem crédito** (salário, idade, região).
- Oferecer visibilidade de **governança e performance** para alta gestão.

---

## 📊 Indicadores do Topo (Cards Executivos)

### **1. Qtd Contratos Concedidos**
Total acumulado de contratos ativos concedidos.

### **2. Valor Concedido Acumulado**
Montante financeiro total concedido pela operação.

### **3. Ticket Médio**
Valor médio concedido por contrato acumulado.

### **4. Valor Recebido Acumulado + % Recuperação**
Quanto do total concedido já retornou à operação.  
O % de recuperação mede eficiência que já retornou para a carteira.

### **5. Valor a Receber Acumulado**
Montante ainda pendente de recebimento.

### **6. Receita BCJ Líquida Acumulada + Margem**
Mostra a receita da tarifa cobrada BCJ.  
O % de margem demonstra eficiência da receita, comparando receita líquida BCJ vs capital concedido.

### **7. Receita Fundo Líquida Acumulada + Margem**
Mesma lógica do indicador anterior, porém aplicada ao Fundo.  

### **8. Receita Total (BCJ + Fundo)**
Consolida a visão de receita BCJ + Fundo.

---

## 📈 Componentes Analíticos

### **Total Aprovado e Status de Elegibilidade**
Mostra quantas contas aprovadas estão aptas a aderir ao Crédito Fácil.  
Responde:  
> *Do total de contas aprovadas, quantas são elegível ao produto?*

### **Elegíveis Utilizando x Não Utilizando**
Monitora adesão real dos colaboradores elegíveis.  
Responde:  
> *Do total de colaboradores elegíveis, quantos estão utilizando o produto?*

### **QTD de Contratos Concedidos x Previsto Mês**
Evolução temporal da quantidade de contratos concedidos x Previsto (meta).

### **Valor Concedido x Previsto por Mês**
Evolução financeira mensal do produto x Previsto (meta).

### **Salário x Capacidade de Limite**
Indicador estratégico governaça de disponibilização de capital.

Responde:
- *Estamos operando abaixo, dentro ou acima do limite saudável de alavancagem?*

Permite medir o espaço real ainda disponível para expansão com segurança.

### **Ranking de Crédito Concedido por Empresa**
Identifica as empresas mais relevantes no ciclo do produto.  
Ajuda a priorizar ações comerciais e análises de risco.

### **Distribuição por Faixa Salarial**
Quem mais utiliza crédito?  
Permite entender elasticidade e comportamento de consumo por faixa de remuneração.

### **Distribuição por Faixa Etária**
Complementa o perfil comportamental, indicando quais grupos têm maior propensão a contratar crédito.

### **Valor Concedido por Região**
Mapa estratégico com concentração geográfica da operação.

---

## 📊 Visão Analítica Completa

A visão tabular permite análises detalhadas por empresa:

- Contas aprovadas  
- Elegíveis ao crédito  
- Utilizando crédito  
- Salário acumulado  
- Limite acumulado  
- Contratos por período  
- Comparação entre meses  
- Atrasos / utilização real  
- Margem realizada  
- Desempenho frente ao limite disponível  

É uma ferramenta tática para gestão operacional e auditoria do produto.

---

## 🧠 Narrativa Executiva – Perguntas Respondidas pelo Painel

O painel entrega respostas diretas às perguntas centrais de negócio:

### **1. A carteira está crescendo? Em que ritmo?**  
Visualização clara de evolução mensal de quantidade e volume concedido.

### **2. Qual é a rentabilidade real do produto?**  
Receita líquida, margens e performance por fonte de capital.

### **3. A operação está dentro da capacidade financeira permitida?**  
Análise integrada de salário acumulado vs limite acumulado.

### **4. Quais empresas são mais relevantes para o produto?**  
Ranking por valor e quantidade.

### **5. A adesão entre elegíveis está adequada?**  
Medição de engajamento e conversão do público elegível.

### **6. Quem mais consome crédito?**  
Distribuições por:

- Faixa salarial  
- Faixa etária  
- Região  

### **7. Qual é a saúde operacional da carteira?**  
Indicadores de vencidos, adiantados, em aberto e liquidações.

Toda essa narrativa foi estruturada para garantir **clareza, segurança e velocidade** nas decisões executivas.

---

## 🛠 Arquitetura e Tecnologias

| Componente | Descrição |
|-----------|-----------|
| **Power BI** | Modelagem, ETL leve, DAX e storytelling visual |
| **SQL / Tabelas Fact & Dim** | Tratamento e padronização de dados |
| **Modelagem Star Schema** | Separação entre Fatos e Dimensões |
| **DAX Otimizado** | Medidas com regras de negócio e lógica temporal |
| **Camada de Governança** | Verificações, filtros e consistência analítica |

---


