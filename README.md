# Regressão Não Paramétrica + Teste KS

Este projeto apenas testa um modelo de regressão não paramétrico (LOWESS) e o uso do teste de Kolmogorov-Smirnov (KS), também não paramétrico, como possível solução e validação para um problema de negócio que não segue linearidade.

## Abordagem

- **Regressão LOWESS** (`statsmodels`): ajusta uma curva suave aos dados sem assumir uma forma funcional (linear ou outra).
- **Teste KS** (`scipy`): valida o resultado sem depender de premissas de distribuição.

## Como rodar

```bash
python -m venv .venv
.venv\Scripts\python.exe -m pip install statsmodels scipy numpy matplotlib ipykernel
```

Depois abra o `notebook.ipynb` e selecione o kernel da `.venv`.
