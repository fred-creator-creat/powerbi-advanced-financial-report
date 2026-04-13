# 📊 Desafio de Projeto: Relatório de Vendas e Lucros com Power BI (Nível Avançado)

Este repositório contém o segundo desafio de Business Intelligence, focado na criação de um dashboard interativo e elaborado utilizando a base de dados *Financial Sample*. O projeto destaca técnicas de navegabilidade, design de interface (UI) e organização de visuais complexos.

---

## 🏛️ Contexto e Parcerias

* **Plataforma de Ensino**: [DIO (Digital Innovation One)](https://www.dio.me/)
* **Empresa Patrocinadora**: [Klabin](https://www.klabin.com.br/)
* **Formação**: Power BI Analyst
* **Desenvolvedor**: [Fred Cavalheiro]

---

## 🛠️ Tecnologias Utilizadas

* **[Microsoft Power BI Desktop](https://powerbi.microsoft.com/)**: Modelagem, cálculos DAX e criação de visuais.
* **[Power Query](https://learn.microsoft.com/pt-br/power-query/)**: Saneamento e tratamento da base de dados.

---

## ⚠️ Justificativa e Notas de Ambiente Técnico

Como parte do meu processo de transição de carreira para Tecnologia, este projeto foi desenvolvido sob condições específicas que exigiram soluções alternativas para garantir a entrega:

* **Restrição de Conta Corporativa**: Por não possuir um e-mail institucional/empresarial, a funcionalidade de publicação no **Power BI Service** foi substituída pela entrega do arquivo fonte `.pbix` e demonstração em vídeo.
* **Adaptação de Visuais (Gráfico de Radar)**: O gráfico de Radar (que exige login na AppSource) foi substituído pelo **Gráfico de Rosca**. Esta escolha técnica garantiu que a análise de dados fosse mantida com visuais nativos de alta performance, oferecendo uma leitura intuitiva e contornando a barreira de licenciamento da AppSource.
* **Hardware e Resiliência**: O desenvolvimento seguiu em máquina com limitações de hardware, exigindo otimização constante do modelo de dados para evitar travamentos durante o processo criativo.
* **Interrupções no Vídeo**: O vídeo de demonstração apresenta pop-ups de autenticação da Microsoft. Tais avisos são decorrentes da tentativa automática do software em validar uma conta corporativa inexistente e foram mantidos para registrar a experiência real de navegabilidade e resiliência em ambiente de estudante.

---

## 🚀 Estrutura do Relatório

O dashboard foi dividido em duas páginas principais para melhor distribuição da carga cognitiva e clareza visual:

### 1. Sales Report (Página 1)
* **Navegabilidade**: Botões laterais para alternância rápida entre as páginas de Vendas e Lucro.
* **Interatividade Avançada (Bookmarks)**: 
    * Alternância dinâmica entre **Mapa** e **Treemap** para análise geográfica.
    * Alternância entre **Gráfico de Barras** e **Gráfico de Rosca** utilizando botões de seleção.
* **Configuração Técnica**: Utilização de **Visuais Selecionados** nos indicadores, garantindo que a troca de gráficos ocorra de forma isolada, sem interferir nos filtros ativos ou nos demais elementos da página.
* **Filtros e Ações**: Botão de "Limpar Segmentações" (Borracha) configurado para resetar todos os filtros de data simultaneamente.
* **Visuais**: Organização de KPIs principais e segmentadores em estilo bloco para melhor aproveitamento de tela.

### 2. Profit Analysis (Página 2)
* **Análise Profunda**: Uso da **Árvore Hierárquica** para decomposição do lucro por país e segmento.
* **Design**: Segmentadores de ano configurados em estilo **Bloco** para melhor alinhamento estético.
* **Visuais Complementares**: Gráficos de Cascata por trimestre e análise de lucro por produto (Gráfico de Rosca).

---

## 📂 Entregáveis e Documentação

### 📊 Projeto e Dados
* [📈 **Arquivo Power BI (Sales_Report_Advanced_Analytics.pbix)**](./Sales_Report_Advanced_Analytics.pbix)
* [📄 **Dataset Utilizado (Financial-Sample.xlsx)**](./Financial-Sample.xlsx)

### 🎥 Demonstração
* [🎥 **Vídeo de Navegação**](./Video_Demonstracao_Dashboard.mp4)

### 🖼️ Galeria de Capturas
* [🖼️ **Página 1: Sales Report 1**](./Sales-Report-1.png)
* [🖼️ **Página 1: Sales Report 2**](./Sales-Report-2.png)
* [🖼️ **Página 2: Profit Analysis**](./Profit-Analysis.png)

---

## 📞 Contato e Conexão
**Fred Cavalheiro**
* 🔄 **Transição de Carreira:** De Segurança Patrimonial (Vigilante) para Tecnologia/Dados.
* 🎓 **Técnico em Desenvolvimento de Sistemas** (Senac).
* 📚 **Estudante de:** Machine Learning e Análise de Dados (Python, Neo4j, Power BI e Excel).
* 🔗 **[Meu Perfil no LinkedIn](https://www.linkedin.com/in/fred-cavalheiro/)**

---
**Projeto desenvolvido para consolidar conhecimentos em UI/UX e Navegabilidade no Power BI.**
