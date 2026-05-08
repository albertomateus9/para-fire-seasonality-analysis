# Para Fire Seasonality Analysis

Fire seasonality lab for Para with monthly aggregation, rainfall comparison, and correlation.

## Overview

**Curricular code:** P18  
**Discipline:** Digital Transformation I and Environmental Education  
**Difficulty:** Intermediate  
**Dataset reference:** INPE/INMET-style fire and rainfall sample  
**Primary source:** https://queimadas.dgi.inpe.br/

This repository is an educational portfolio project for the first module of a technical Data Science curriculum. It uses a small safe sample by default and provides a script that documents how a real public dataset could be obtained or prepared later.

No large dataset, private school document, real student record, or personal contact detail is versioned in this repository.

## Concepts Practiced

- time groupby
- corr
- subplots
- exploratory analysis

## Repository Structure

```text
data/
  sample/       # small safe sample used by smoke tests
  raw/          # external raw files, ignored except .gitkeep
  processed/    # generated outputs, ignored except .gitkeep
notebooks/
  01_exploracao.ipynb
scripts/
  download_data.py
src/
  main.py
charts/
reports/
```

## Quick Start

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
python -m src.main --sample
```

Linux/macOS activation:

```bash
source .venv/bin/activate
```

## Data Policy

- The default workflow uses only sample data committed to `data/sample/`.
- Real public datasets should be downloaded manually or through `scripts/download_data.py` after reviewing the source terms.
- Generated outputs are written to `data/processed/`, `charts/`, or `reports/`.

---

# Para Fire Seasonality Analysis

Fire seasonality lab for Para with monthly aggregation, rainfall comparison, and correlation.

## Visao Geral

**Codigo curricular:** P18  
**Disciplina:** Transformacao Digital I e Educacao Ambiental  
**Dificuldade:** Intermediario  
**Referencia de dataset:** INPE/INMET-style fire and rainfall sample  
**Fonte primaria:** https://queimadas.dgi.inpe.br/

Este repositorio e um projeto educacional de portfolio para o primeiro modulo de um curso tecnico em Ciencia de Dados. Ele usa uma amostra pequena e segura por padrao e traz um script que documenta como um dataset publico real poderia ser obtido ou preparado depois.

Nenhum dataset grande, documento interno escolar, registro real de estudante ou contato pessoal e versionado neste repositorio.

## Conceitos Praticados

- time groupby
- corr
- subplots
- exploratory analysis

## Como Rodar

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
python -m src.main --sample
```

## Politica De Dados

- O fluxo padrao usa apenas dados de amostra em `data/sample/`.
- Datasets publicos reais devem ser baixados manualmente ou por `scripts/download_data.py` apos revisao dos termos da fonte.
- Saidas geradas ficam em `data/processed/`, `charts/` ou `reports/`.

## License

MIT. See [LICENSE](LICENSE).
