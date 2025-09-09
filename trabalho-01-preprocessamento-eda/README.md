# Trabalho 01 — EDA e Pré-processamento (MD N1)

**Objetivo:** explorar e preparar o dataset para etapas futuras de modelagem.

## Passos realizados
1. Carregamento do dataset (`AlgorithmDataset.csv`)
2. Visão geral: `head()`, `info()`, `describe()`
3. Cardinalidade: contagem de valores únicos por coluna
4. Qualidade: verificação de valores nulos
5. Limpeza: remoção de `id` e `Unnamed: 32` (quando existir)
6. Transformação: `diagnosis` mapeado para numérico (`M`→1, `B`→0)
7. Separação de variáveis numéricas
8. Normalização com `MinMaxScaler`
9. Visualização: boxplot de `texture_mean` por diagnóstico

## Como reproduzir
- **Colab**: abra `notebooks/MD_N1_Exercicio.ipynb` e execute.

