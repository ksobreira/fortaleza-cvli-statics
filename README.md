

# 📊 Análise dos Crimes Violentos Letais Intencionais (CVLI) - Fortaleza (2009–2025)

---

## 🧠 Visão Geral

Este repositório contém uma análise estatística descritiva detalhada sobre os Crimes Violentos Letais Intencionais (CVLI) na cidade de Fortaleza. O projeto utiliza Python para processar dados históricos, gerar tabelas de frequência e visualizações gráficas que ajudam a compreender o perfil da criminalidade na região.

---

## 🎯 Problema de Pesquisa

Quais padrões podem ser observados nos CVLI em Fortaleza considerando:

* Perfil das vítimas
* Meio empregado no crime
* Distribuição temporal
* Características sociodemográficas

---

## 📂 Dataset

* Fonte: Base de dados CVLI (2009–2025)
* Formato: `.xlsx`
* Unidade de análise: ocorrência criminal

### Variáveis analisadas

| Categoria | Variáveis                         |
| --------- | --------------------------------- |
| Crime     | Natureza, Meio Empregado          |
| Vítima    | Gênero, Raça, Escolaridade, Idade |
| Temporal  | Data, Hora, Dia da Semana         |

---

## ⚙️ Tecnologias Utilizadas

| Ferramenta | Finalidade           |
| ---------- | -------------------- |
| Python     | Processamento        |
| Pandas     | Manipulação de dados |
| NumPy      | Operações numéricas  |
| Matplotlib | Visualização         |
| Seaborn    | Estética gráfica     |

---

## 🧪 Metodologia

O projeto segue etapas clássicas de **Data Analysis Pipeline**:

### 1️⃣ Preparação dos Dados

* Importação da planilha Excel
* Seleção de variáveis relevantes
* Conversão de tipos
* Tratamento de valores ausentes
* Limpeza de idades inválidas

---

### 2️⃣ Estatística Descritiva

#### Séries Estatísticas

* Frequência absoluta
* Frequência relativa (%)

Aplicadas a:

* Natureza do crime
* Meio empregado
* Gênero
* Escolaridade
* Raça
* Dia da semana

---

### 3️⃣ Análise Bivariada

Tabelas cruzadas:

* Meio Empregado × Gênero
* Escolaridade × Raça

Incluindo:

* Frequência simples
* Frequência relativa (%)

---

### 4️⃣ Visualização de Dados

#### 📌 Gráficos de Setor

* Distribuição por gênero
* Meio empregado

#### 📌 Gráficos de Barra

* Ocorrências por dia da semana
* Escolaridade das vítimas

#### 📌 Gráficos de Linha

* Ocorrências por mês
* Evolução anual
* Distribuição por horário

---

### 5️⃣ Estatística da Idade das Vítimas

#### Medidas de posição

* Média
* Mediana
* Moda
* Quartis
* Decis

#### Medidas de dispersão

* Variância
* Desvio padrão
* Coeficiente de variação

## 📁 Estrutura do Projeto

```
project-cvli-fortaleza/
│
├── data/
│   └── raw/
│       └── CVLI_2009-a-2025.xlsx
│
├── notebooks/
│   └── estatistica.ipynb
│
├── reports
│   └── figures/
│
├──README.md
├──requeriments.txt
```

---

## ▶️ Como Executar

### Clone o repositório

```bash
git clone https://github.com/ksobreira/fortaleza-cvli-statics.git
cd fortaleza-cvli-statics
```

### Instale dependências

```bash
pip install pandas numpy matplotlib seaborn openpyxl
```

### Execute

```bash
python estatistica.inpyb
```

Os gráficos serão salvos automaticamente em:

```
/reports/figures
```

---


## 👨‍💻 Autores

**Kauam Sobreira e Renato Romano**

Projeto acadêmico de Métodos quantitativos em computação.

---

## 📄 Licença

Uso acadêmico e educacional.

---

