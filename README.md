# 📘 Miniguia de Estudos: O Investidor Inteligente & Value Investing

> **Desafio de Projeto DIO** — Criando um Caderno Temático com Inteligência Artificial no NotebookLM e Portfólio de Destaque.

---

## 🎯 Contexto e Objetivos

Este repositório foi desenvolvido como parte de um desafio prático da [DIO](https://dio.me). O objetivo principal é consolidar o conhecimento sobre a metodologia de **Value Investing (Investimento em Valor)** criada por Benjamin Graham, utilizando o **Google NotebookLM** como ferramenta de aprendizagem ativa e curadoria de conhecimento.

Adicionalmente, expandindo o escopo acadêmico para uma aplicação mercadológica real, as informações sintetizadas foram utilizadas para a estruturação de um infoproduto (eBook) e uma Landing Page de vendas integrada à plataforma Kiwify.

---

## 📚 Curadoria de Fontes

Para alimentar o NotebookLM e garantir respostas precisas baseadas na filosofia clássica de investimentos, foram selecionadas as seguintes fontes:

1. **O Investidor Inteligente (Benjamin Graham)** — Capítulos selecionados sobre o "Senhor Mercado" e Margem de Segurança.
2. **Análise de Performance de Dividendos no Mercado Brasileiro** — Dados históricos baseados na filosofia de Luiz Barsi Filho (o "Graham Brasileiro").
3. **Fórmula de Graham Explicada** — Guias práticos sobre o cálculo de valor intrínseco (VPA e LPA).
4. **Artigos de Finanças Comportamentais** — Estudos sobre a irracionalidade dos mercados financeiros a curto prazo.

---

## 🧠 Engenharia de Prompts & Troubleshooting

Durante a interação com o NotebookLM, foram testadas diferentes abordagens de prompts para extrair insights profundos.

### ❌ Prompt Inicial (Genérico)

```
Pergunta: "O que Benjamin Graham diz sobre ações?"
Resultado: Resposta superficial, listando conceitos básicos de forma desorganizada.
```

### ✅ Prompt Otimizado (Engenharia de Prompt)

```
Pergunta: "Aja como um analista CNPI sênior especialista em Value Investing.
Com base estritamente nas fontes fornecidas, explique como a metáfora do
'Senhor Mercado' justifica a necessidade de uma 'Margem de Segurança' na
compra de ações brasileiras perenes. Cite exemplos de setores."

Resultado: Resposta altamente estruturada, conectando o comportamento
irracional do mercado com a proteção de capital em setores perenes
(como energia e bancos).
```

### 🔧 Desafios Encontrados (Troubleshooting)

| Problema | Causa | Solução Aplicada |
|---|---|---|
| Alucinação com Fórmulas | Modelo aplicou a Fórmula de Graham sem contextualizar os limites de 22,5 para o mercado atual | Inserção de fonte complementar delimitando os parâmetros aceitáveis de P/L e P/VP, forçando o NotebookLM a cruzar os dados corretamente |
| Respostas genéricas | Prompts sem persona ou restrições de fonte | Adição de papel (analista CNPI sênior) e restrição explícita às fontes carregadas |

---

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumo Estruturado

- **O Senhor Mercado:** O mercado acionário deve ser visto como um sócio emocional. Ele dita preços irracionais diariamente; o investidor inteligente compra quando ele está excessivamente pessimista e vende quando está excessivamente otimista.
- **Margem de Segurança:** A diferença entre o valor intrínseco (real) da empresa e o preço de tela na bolsa. Quanto maior a margem, menor o risco de perda permanente de capital.
- **Fórmula de Preço Justo:**

$$\text{Preço Justo} = \sqrt{22{,}5 \times \text{LPA} \times \text{VPA}}$$

### 2. Glossário de Conceitos

| Termo | Definição |
|---|---|
| **Value Investing** | Filosofia de investimento focada em comprar ativos por menos do que eles realmente valem |
| **LPA (Lucro por Ação)** | Lucro da empresa dividido pelo número de ações emitidas |
| **VPA (Valor Patrimonial por Ação)** | Patrimônio líquido da empresa dividido pela quantidade de ações |
| **Margem de Segurança** | Desconto aplicado ao preço de compra em relação ao valor intrínseco calculado |
| **P/L (Preço/Lucro)** | Múltiplo que indica quantos anos de lucro o mercado está pagando pela ação |
| **P/VP (Preço/Valor Patrimonial)** | Relação entre preço de mercado e valor contábil da ação |

### 3. Prompts Reutilizáveis para Revisão

```
"Sintetize os 3 pontos mais críticos do capítulo de Margem de Segurança
 da fonte X em formato de tópicos para memorização."

"Gere 5 perguntas de múltipla escolha com base no glossário de Value
 Investing para testar meu conhecimento."

"Com base nas fontes carregadas, qual empresa brasileira do setor elétrico
 teria a maior margem de segurança segundo a Fórmula de Graham?"
```

---

## 🚀 Aplicação Comercial & Links do Projeto

Os estudos foram convertidos em uma infraestrutura de vendas real como diferencial técnico:

| Recurso | Link |
|---|---|
| 🔗 **Landing Page de Vendas (GitHub Pages)** | [yago-silva-ads.github.io/investidor-inteligente](https://yago-silva-ads.github.io/investidor-inteligente/) |
| 🛒 **Checkout Kiwify** | [Adquira o eBook aqui — R$ 10,00](https://pay.kiwify.com.br/pUDitcM) |

---

## 👤 Desenvolvedor

Conecte-se para networking e oportunidades no ecossistema de tecnologia e finanças:

| Plataforma | Link |
|---|---|
| 💼 **LinkedIn** | [Yago Santos Silva](https://www.linkedin.com/in/yago-silva-ads/) |
| 🐙 **GitHub** | [@yago-silva-ads](https://github.com/yago-silva-ads) |

---

<p align="center">
  Feito com 💛 por <strong>Yago Santos Silva</strong> · Desafio DIO · 2026
</p>
