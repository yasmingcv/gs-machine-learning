# 🌧️ PrevIA

Previsão de **chuva forte (20 mm ou mais) no dia seguinte** em São Paulo, com dados reais do INMET (estação A701).

## Conteúdo

| Arquivo / pasta | O que é |
|---|---|
| `GS_ML_CitizenTech.ipynb` | notebook completo, já executado, com as análises |
| `dados/inmet_A701_sao_paulo_diario.csv` | dataset (6.795 dias) |
| `dados/README.md` | fonte, link, período e dicionário das colunas |
| `figuras/` | gráficos gerados pelo notebook |
| `resultados.json` | números principais (usados no relatório) |
| `requirements.txt` | bibliotecas necessárias |

O relatório está em `../RELATORIO_ML.md`.

## Como rodar

```bash
pip install -r requirements.txt
jupyter notebook GS_ML_CitizenTech.ipynb
```
