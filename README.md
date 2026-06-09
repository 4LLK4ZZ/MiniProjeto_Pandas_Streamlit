# 📊 Dashboard de Análise de Vendas com Streamlit e Pandas

Este é um mini projeto de análise de dados interativa desenvolvido em Python, utilizando **Streamlit** para a interface gráfica e **Pandas** para a manipulação eficiente dos dados. A aplicação funciona como um sistema de controle e visualização de vendas multilojas, permitindo desde a inserção de novos registros até análises gerenciais avançadas.

---

## 🚀 Funcionalidades do Projeto

O sistema é dividido em 5 etapas e recursos principais, conforme o fluxo de utilização:

### 1. Visualização Geral dos Dados
Uma visão transparente da base de dados bruta, exibindo as principais colunas do negócio de forma paginada e organizada: data da compra, ID, localização da loja, vendedor e produto vendido.

### 2. Filtro Dinâmico de Colunas e Linhas
Permite ao usuário customizar o que deseja analisar. É possível selecionar quais colunas exibir através de *tags* dinâmicas e aplicar filtros específicos (como filtrar apenas vendas de uma determinada filial, ex: "Rio de Janeiro").

### 3. Cadastro de Novas Compras (Inserção)
Formulário lateral interativo para dar entrada em novas vendas em tempo real. O usuário preenche os campos (loja, vendedor, produto, cliente, gênero e forma de pagamento) e o sistema atualiza a base imediatamente, exibindo um alerta de sucesso: `"Compra adicionada"`.

### 4. Resumo e Volume de Dados (KPIs Gerenciais)
Uma visão executiva baseada em um intervalo de datas selecionável (Data Inicial e Data Final). A tela calcula e exibe automaticamente:
* **Números Gerais:** Valor total acumulado e quantidade de vendas no período.
* **Destaque por Filial:** A principal loja vendedora e sua respectiva receita.
* **Destaque por Funcionário:** O melhor vendedor do período e a sua comissão calculada de forma dinâmica.

### 5. Tabela Dinâmica (*Pivot Table*)
Recurso avançado para cruzamento de dados. O usuário consegue definir dinamicamente os índices (ex: agrupar por `loja` e `vendedor`), as colunas (ex: separar por `produto`) e a métrica de agregação (ex: `soma` do `preço`), gerando uma matriz de inteligência de negócios instantânea.

---

## 🛠️ Tecnologias Utilizadas

* **[Python](https://www.python.org/)** (Linguagem base)
* **[Streamlit](https://streamlit.io/)** (Construção da interface web e componentes dinâmicos)
* **[Pandas](https://pandas.pydata.org/)** (Estruturação, filtragem e criação de tabelas dinâmicas)

---

## 📦 Como Executar o Projeto

### Pré-requisitos
Certifique-se de ter o Python instalado na sua máquina. Em seguida, instale as dependências necessárias:

```bash
pip install streamlit pandas
