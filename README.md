# samu_recife
Descrição Curta (Para a barra lateral "About" do repositório) 
Pipeline de análise e modelagem estatística de chamados de emergência do SAMU Recife (2020–2025), 
desenvolvido em Python com foco em integridade de dados (SHA-256) e previsão de séries temporais via SARIMA.

# 🚑 SAMU Recife: Análise e Modelagem de Dados de Urgência (2020–2025)

Este repositório apresenta um projeto end-to-end de ciência e engenharia de dados 
focado na extração, limpeza, validação de integridade e modelagem estatística de registros de chamados de emergência do **SAMU
(Serviço de Atendimento Móvel de Urgência)**, utilizando dados públicos do portal de Dados Abertos da Cidade do Recife.

## 🚀 Sobre o Projeto
O objetivo central deste notebook é explorar o comportamento histórico dos atendimentos de urgência médica ao longo dos anos,
garantindo total rastreabilidade dos arquivos brutos e aplicando técnicas de séries temporais 
para compreender padrões sazonais e prever tendências de chamados.

## 🛠️ Tecnologias e Bibliotecas
* **Linguagem:** Python
* **Manipulação e Análise:** Pandas, NumPy
* **Segurança e Integridade:** Algoritmo de hash **SHA-256** para validação de arquivos de dados
* **Modelagem Estatística:** **SARIMA** (*Seasonal Autoregressive Integrated Moving Average*) via `statsmodels`
* **Visualização:** Matplotlib / Seaborn
* **Ambiente de Desenvolvimento:** Jupyter Notebook / Google Colab

## 📊 Etapas do Pipeline de Dados
1. **Ingestão e Pré-processamento:** Leitura de grandes volumes de dados de chamados de emergência (2020–2025), tratamento de valores nulos, conversão de tipos temporais e padronização de colunas.
2. **Validação de Integridade (SHA-256):** Aplicação de funções de hash criptográfico para garantir a autenticidade e o controle de versão dos conjuntos de dados manipulados.
3. **Análise Exploratória (EDA):** Investigação de sazonalidade, horários de pico, tipos de ocorrências e distribuição geográfica/temporal dos chamados.
4. **Modelagem Preditiva (SARIMA):** Construção, ajuste de parâmetros e validação de modelos de séries temporais para projeção de ocorrências futuras.

## ⚙️ Como Executar o Projeto
1. Clone este repositório:
   ```bash
   git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
