# Guia Prático de Utilização da Biblioteca de Prompts e Comandos

---

## 1. Como Ler as Colunas

Na aba **“Biblioteca 200+”**, você encontrará a seguinte estrutura:

| Coluna | O que significa |
| :--- | :--- |
| **Categoria** | Área do comando: *Excel, Python, Finanças, IA*, etc. |
| **Comando / Palavra-chave** | A palavra-chave que você pode colocar no seu prompt. |
| **Para que serve** | O objetivo daquele comando. |
| **Exemplo pronto para copiar** | Um exemplo prático de utilização. |
| **Nível** | Básico, intermediário ou avançado. |
| **Combinações recomendadas** | Outros comandos que funcionam bem em conjunto. |

---

## 2. O que significa “Combinações Recomendadas”?

Imagine que você encontre a palavra-chave `debug`. Na última coluna, podem aparecer sugestões como:

`explain-code` | `refactor` | `optimize` | `unit-test`

Isso significa que você pode combinar múltiplos comandos:
$$	ext{debug} + 	ext{explain-code} + 	ext{refactor} + 	ext{optimize} + 	ext{unit-test}$$

### Função de Cada Parte

* 🐞 **`debug`** → Encontra os erros
* 💡 **`explain-code`** → Explica a causa dos erros
* 🛠️ **`refactor`** → Reorganiza o código
* ⚡ **`optimize`** → Melhora o desempenho
* 🧪 **`unit-test`** → Cria testes para validação

---

### Exemplo Comparativo

> ❌ **Antes (Prompt genérico):**  
> *"Corrija meu código."*

> ✅ **Depois (Prompt combinado):**  
> **Comandos:** `debug + explain-code + refactor + optimize + unit-test`  
> *"Analise meu código Python. Encontre os erros. Explique por que acontecem. Corrija os erros. Refatore o código. Otimize o desempenho. Crie testes para verificar a solução."*

---

## 3. Como Combinar os Comandos

A lógica de construção de um prompt poderoso segue este fluxo:

```
🎯 Comando principal (Define o QUE fazer)
       ↓
🔧 Comandos complementares (Definem COMO fazer)
       ↓
📋 Formato (Define como APRESENTAR o resultado)
```

**Exemplo:**
`EDA + statistics + visualization + key-points + table`

**Tradução prática:**
> *"Analise os dados $
ightarrow$ faça estatística $
ightarrow$ sugira gráficos $
ightarrow$ extraia os principais pontos $
ightarrow$ apresente em tabela."*

---

## 4. Exemplos Práticos por Área

### 🐍 Python

#### Exemplo 1: Debugging
* **Combinação:** `debug + explain-code + refactor + optimize`
* **Fluxo:** Encontrar $
ightarrow$ Explicar $
ightarrow$ Corrigir $
ightarrow$ Melhorar

#### Exemplo 2: Manipulação de Dados
* **Combinação:** `pandas + data-cleaning + EDA + visualization`
* **Fluxo:** Manipular $
ightarrow$ Limpar $
ightarrow$ Explorar $
ightarrow$ Visualizar

```text
pandas + data-cleaning + EDA + visualization

Analise meu DataFrame.
Faça:
1. Limpeza dos dados;
2. Tratamento de valores ausentes;
3. Análise exploratória;
4. Identificação de outliers;
5. Gráficos relevantes;
6. Principais insights.
```

---

### 📊 5. Data Science

**Combinação essencial:** `EDA + data-cleaning + statistics + visualization`

* 🔍 **`EDA`** $
ightarrow$ Entender os dados
* 🧹 **`data-cleaning`** $
ightarrow$ Corrigir os dados
* 📈 **`statistics`** $
ightarrow$ Quantificar os padrões
* 👁️ **`visualization`** $
ightarrow$ Enxergar os padrões

---

### 🤖 6. Machine Learning

Esta combinação estrutura um **pipeline completo de Machine Learning**:

```
Dados ──> EDA ──> feature-engineering ──> model-selection ──> cross-validation ──> hyperparameter-tuning ──> model-evaluation ──> Modelo Final
```

* **Prompt:** `EDA + feature-engineering + model-selection + cross-validation + hyperparameter-tuning + model-evaluation`

---

### 💰 7. Finanças

* **Combinação:** `financial-analysis + risk-return + compare + scenario-analysis`
* **Objetivo:** Análise financeira $+$ Risco x Retorno $+$ Comparação $+$ Cenários

> ❌ **Pergunta simples:** *"Qual investimento é melhor?"*  
> ✅ **Prompt Estruturado:**
> 
> ```text
> financial-analysis + risk-return + compare + scenario-analysis
> 
> Compare CDB, LCI, LCA e Tesouro Selic.
> Considere:
> - Rentabilidade;
> - Risco;
> - Liquidez;
> - Tributação;
> - Prazo;
> - Cenário otimista, base e pessimista.
> 
> Apresente uma tabela comparativa e explique a conclusão.
> ```

---

### 📚 8. Estudos

Crie um **professor particular sob medida**:

* **Combinação:** `ELI5 + teach-me + analogy + examples + quiz`

| Comando | Função |
| :--- | :--- |
| **`ELI5`** | Explica de maneira extremamente simples (*Like I'm 5*) |
| **`teach-me`** | Ensina o conceito passo a passo |
| **`analogy`** | Utiliza analogias do dia a dia |
| **`examples`** | Fornece exemplos práticos e numéricos |
| **`quiz`** | Testa o seu conhecimento ao final |

```text
ELI5 + teach-me + analogy + examples + quiz

Ensine regressão linear.
Comece explicando de forma muito simples. Depois use uma analogia.
Depois dê um exemplo numérico. Depois mostre um exemplo em Python.
Por fim, faça 5 perguntas para testar se eu entendi.
```

---

### ✍️ 9. Escrita

Ideal para e-mails, relatórios e documentos profissionais.

* **Combinação:** `rewrite + professional + concise + proofread`
* **Objetivo:** Reescrever $
ightarrow$ Profissionalizar $
ightarrow$ Ser objetivo $
ightarrow$ Revisar/Corrigir

---

### 🔎 10. Pesquisa

Ideal para investigações aprofundadas e acadêmicas.

* **Combinação:** `deep-research + primary-sources + fact-check + source-evaluation`
* **Fluxo:** Pesquisar profundamente $
ightarrow$ Buscar fontes primárias $
ightarrow$ Verificar fatos $
ightarrow$ Avaliar qualidade das fontes

---

### 📊 11. Excel

* **Combinação:** `excel-formula + debug-formula + formula-explanation`

```text
excel-formula + debug-formula + formula-explanation

Preciso calcular o rendimento de um investimento.
Crie a fórmula. Depois verifique se existe algum erro.
Por fim, explique a fórmula parte por parte.
```

---

### 🧠 12. Mapa Mental (Mind-map)

Estruture conteúdos visualmente para estudo ou apresentações.

* **Combinação:** `mind-map + teach-me + examples`

```text
mind-map + teach-me + examples

Crie um mapa mental sobre Machine Learning.
Organize em:
- Conceito;
- Tipos;
- Algoritmos;
- Treinamento;
- Validação;
- Métricas;
- Aplicações.

Explique cada ramo e dê exemplos.
```

---

## 13. 🔥 A Combinação Mais Importante

A estrutura de sucesso para qualquer prompt é:

$$\mathbf{Objetivo} + \mathbf{Método} + \mathbf{Profundidade} + \mathbf{Formato}$$

1. **O QUE?** $
ightarrow$ `analyze-data`
2. **COMO?** $
ightarrow$ `step-by-step`
3. **PROFUNDIDADE?** $
ightarrow$ `detailed`
4. **APRESENTAÇÃO?** $
ightarrow$ `table`

```text
analyze-data + step-by-step + detailed + table

Analise meu dataset.
Explique o processo passo a passo, seja detalhado e apresente os principais resultados em tabelas.
```

---

## ⭐ Fórmula Geral para Criar Seus Próprios Prompts

$$	ext{[OBJETIVO]} + 	ext{[MÉTODO]} + 	ext{[PROFUNDIDADE]} + 	ext{[VALIDAÇÃO]} + 	ext{[FORMATO]}$$

### Exemplos Práticos por Domínio

* **Data Science:** `EDA + statistics + visualization + fact-check + table`
* **Desenvolvimento Python:** `debug + explain-code + refactor + optimize + unit-test + code-block`
* **Investimentos & Finanças:** `financial-analysis + risk-return + compare + scenario-analysis + sensitivity-analysis + table`
* **Estudos & Aprendizado:** `ELI5 + teach-me + step-by-step + analogy + examples + quiz`
