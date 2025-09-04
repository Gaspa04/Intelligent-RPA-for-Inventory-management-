# 📑 Documentação Inicial – TCC  
**Tema:** Automação RPA com IA para Otimização de Estoque e Compras em Empresas  
**Ferramentas:** Power Automate + Prophet + Dataset Público (Kaggle)  
**Autor:** 
-Felipe Ujvari Gasparino de Sousa – 10418415
-Thomaz de Souza Scopel - 10417182 
-Gustavo Nascimento Siqueira - 10419057

---

## 📚 Estrutura do Trabalho (Sumário)
1. Introdução  
2. Objetivos  
   - Objetivo Geral  
   - Objetivos Específicos  
3. Justificativa  
4. Fundamentação Teórica  
5. Metodologia  
   - Dados  
   - Ferramentas  
   - Fluxo Automatizado  
6. Indicadores de Sucesso (KPIs)  
7. Resultados e Discussão  
8. Conclusão  
9. Próximos Passos  

---

## 1. Introdução
A gestão de estoque é um dos maiores desafios no **setor empresarial**.  
Erros no processo de reposição podem gerar:  
- **Excesso de estoque**, resultando em custos financeiros elevados;  
- **Ruptura de estoque**, impactando diretamente as operações e o atendimento ao cliente.  

O presente trabalho propõe a utilização de **Automação Robótica de Processos (RPA)**, integrada com um modelo de **Inteligência Artificial de Previsão de Demanda (Prophet)**, para otimizar o processo de compras e melhorar a gestão de estoques em empresas de diversos setores.  

---

## 2. Objetivos
### 2.1 Objetivo Geral
Desenvolver um protótipo de automação para **otimizar o estoque de empresas**, utilizando **RPA (Power Automate)** para coletar dados e gerar pedidos automáticos de compra, e **IA (Prophet)** para prever a demanda de produtos.  

### 2.2 Objetivos Específicos
- Coletar dados históricos de vendas/consumo (dataset público);  
- Implementar um modelo de previsão de demanda utilizando Prophet;  
- Integrar o modelo com Power Automate para automatizar pedidos de compra;  
- Avaliar a solução por meio de indicadores de estoque e desempenho logístico.  

---

## 3. Justificativa
A integração entre **RPA e IA** permite que processos manuais e repetitivos sejam automatizados e, ao mesmo tempo, **decisões mais inteligentes** sejam tomadas.  
Com isso, empresas de diferentes portes e segmentos podem:  
- **Reduzir custos** associados a excesso ou falta de estoque;  
- **Aumentar a eficiência** na cadeia de suprimentos;  
- **Melhorar o atendimento ao cliente** ao evitar rupturas.  

Além disso, este trabalho contribui academicamente ao demonstrar a aplicação prática de tecnologias emergentes em um **problema real de gestão empresarial**.  

---

## 4. Fundamentação Teórica (resumo inicial)
- **RPA (Robotic Process Automation):** Tecnologia que permite a automação de tarefas repetitivas, como coleta de dados e geração de relatórios.  
- **IA aplicada à Previsão de Demanda:** Técnicas de séries temporais, com destaque para o **Prophet**, modelo desenvolvido pelo Facebook, robusto e fácil de aplicar.  
- **Gestão de Estoque em Empresas:** Envolve estratégias para equilibrar disponibilidade de insumos/produtos e custos operacionais.  
- **Integração RPA + IA:** Combinação que permite não apenas automatizar tarefas, mas também **tomar decisões baseadas em dados**.  

---

## 5. Metodologia
### 5.1 Dados
- Fonte: **Datasets de estoque e vendas** disponíveis no Kaggle.  
- Conteúdo: histórico de transações, detalhes de produtos e movimentação de estoque.  
- Preparação: limpeza dos dados, agregação por produto e período.  

### 5.2 Ferramentas
- **Power Automate** → responsável por coletar dados de planilhas/sistemas e automatizar a criação de pedidos de compra.  
- **Prophet (Python)** → modelo de previsão de demanda baseado em séries temporais.  

### 5.3 Fluxo Proposto
1. **Coleta de dados:** Power Automate lê planilha (Excel/CSV) com histórico de vendas/consumo.  
2. **Processamento:** Script em Python (Prophet) gera previsão de demanda futura.  
3. **Integração:** Power Automate recebe os resultados da previsão.  
4. **Automação:** Robô gera automaticamente um pedido de compra (Excel ou e-mail para fornecedor).  

---

## 6. Indicadores de Sucesso (KPIs)
- 📉 Redução do excesso de estoque (%)  
- 🚫 Redução da ruptura de estoque (%)  
- 💰 Economia financeira estimada  
- 📦 OTIF (On Time In Full – nível de atendimento ao cliente interno/externo)  

---

## 7. Resultados e Discussão
*(será preenchido após os testes e simulações com o dataset)*  

---

## 8. Conclusão
*(será desenvolvido ao final, após análise dos resultados obtidos)*  

---

## 9. Próximos Passos
1. **Selecionar dataset adequado** no Kaggle sobre estoque e vendas.  
2. **Rodar o Prophet** em Python para gerar previsões de alguns produtos.  
3. **Criar um fluxo no Power Automate** que leia uma planilha, acione o script Python (via Power Automate Desktop ou Azure Notebook) e gere uma saída com pedido automático.


## 10. Artigos Ciêntificos de Refência:
1. [Uploading ArtigoEstoquecomIA.pdf…]()
2. [Uploading ArtigoForecastInventorywithAI.pdf…]()
3. [Uploading ArtigoImpactofInventoryForecasting.pdf…]()
4. [Uploading 1704073.pdf…]()

