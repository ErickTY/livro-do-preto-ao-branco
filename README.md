# Do Preto ao Branco

## Tornando Modelos de IA Mais Transparentes

**Fundamentos, Matemática e Aplicações de Inteligência Artificial Explicável com Permutation Importance, LIME e SHAP**

**Autor:** Prof. Dr. Erick Toshio Yamamoto

Este é o **repositório oficial de materiais computacionais complementares do livro _Do Preto ao Branco — Tornando Modelos de IA Mais Transparentes_**.

O objetivo não é criar um projeto genérico de XAI, mas preservar uma relação rastreável entre o conteúdo da obra, os notebooks, os dados, as configurações experimentais e os resultados reproduzíveis.

## Relação com o livro

**capítulo → notebook → dataset → configuração → resultado → interpretação**

## Escopo técnico

- Permutation Feature Importance;
- LIME;
- valores de Shapley e SHAP;
- KernelSHAP;
- TreeSHAP;
- DeepSHAP;
- comparação entre explicações globais e locais;
- estudo de caso industrial.

## Organização

```text
livro-do-preto-ao-branco/
├── README.md
├── CITATION.cff
├── LICENSE-CODE
├── requirements.txt
├── environment.yml
├── .gitignore
├── notebooks/
│   ├── 01_fundamentos/
│   ├── 02_permutation_importance/
│   ├── 03_lime/
│   ├── 04_shapley/
│   ├── 05_shap/
│   ├── 06_kernelshap/
│   ├── 07_treeshap/
│   ├── 08_deepshap/
│   ├── 09_comparacao/
│   └── 10_estudo_de_caso_industrial/
├── datasets/
├── src/
├── figures/
└── docs/
```

## Reprodutibilidade

Cada notebook oficial deverá identificar o capítulo e a seção relacionados, o dataset, o modelo, o método XAI, a seed/`random_state`, os principais parâmetros, as dependências e a saída esperada.

> O código complementa o livro; não substitui as explicações conceituais, matemáticas e metodológicas da obra.

## Status

Estrutura computacional da primeira edição em preparação.
