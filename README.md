# 🧠 Análise de Desempenho Cognitivo Humano

Um projeto avançado de análise de dados que investiga os fatores que impactam o desempenho cognitivo humano, utilizando estatística, machine learning e storytelling visual com foco consultivo.

---

## 📊 Cenário de Negócio

Nos últimos meses, o desempenho cognitivo de estudantes e profissionais gerou preocupação. A liderança quer decisões baseadas em dados para aumentar produtividade, reduzir estresse e melhorar memória.

A demanda:

> “Quais fatores mais impactam o desempenho, e como podemos agir sobre eles?”

---

## 🎯 Objetivo do Projeto

- Descobrir os principais fatores que afetam o desempenho cognitivo
- Prever o desempenho com machine learning
- Segmentar indivíduos por perfil de risco
- Gerar insights executivos e planos de ação

---

## 🔬 Técnicas Analíticas Aplicadas

| Pergunta Estratégica                                 | Técnica Estatística           | Etapa CRISP-DM         |
|------------------------------------------------------|-------------------------------|------------------------|
| 1. Quais fatores se correlacionam com desempenho?    | Correlação de Spearman        | Compreensão dos Dados |
| 2. Como os grupos de desempenho se diferenciam?      | Teste t de Student            | Preparação dos Dados  |
| 3. Há interação entre variáveis?                     | Regressão com Interação       | Modelagem             |
| 4. Podemos prever desempenho com ML?                 | Random Forest + SHAP          | Modelagem             |
| 5. Quais são os perfis cognitivos?                   | K-Means Clustering            | Modelagem             |
| 6. Quais fatores devemos priorizar?                  | Análise de Pareto             | Avaliação             |

---

## Dados Utilizados

Fonte:https://www.kaggle.com/datasets/samxsam/human-cognitive-performance-analysis
-----

## 🧱 Estrutura do Projeto (estilo Cookiecutter)

```text
analise-cognitiva/
├── data/               # Dados brutos e tratados
├── notebooks/          # Jupyter Notebook principal
├── reports/
│   └── figures/        # Gráficos gerados
├── src/                # Funções Python reutilizáveis (opcional)
├── README.md           # Este arquivo
├── executive_summary.md
├── relatorio_final_cognitivo.pdf
├── requirements.txt
└── LICENSE             # Licença MIT





---

## 🧾 `executive_summary.md`

```markdown
# Resumo Executivo

Esta análise teve como objetivo identificar os principais fatores que influenciam o desempenho cognitivo humano e transformá-los em estratégias práticas.

---

## 🔍 3 Descobertas

1. **O tempo de reação é o fator mais crítico**, com forte correlação negativa (r = -0.82) com o desempenho cognitivo.
2. **O estresse reduz em até 60% os benefícios do sono**, indicando necessidade de intervenções combinadas.
3. **23% da amostra está em um cluster de alto risco**, apresentando déficits graves em todas as dimensões.

---

## 🎯 3 Recomendações

1. **Implementar programas de agilidade mental** voltados especialmente a quem apresenta tempo de reação baixo.
2. **Atuar simultaneamente em sono e estresse**, priorizando intervenções integradas.
3. **Criar plano de ação específico para o grupo de alto risco**, com metas e indicadores mensais de melhoria.

---

> Este projeto oferece base estratégica para ações de saúde cognitiva, produtividade e bem-estar em ambientes corporativos e acadêmicos.

