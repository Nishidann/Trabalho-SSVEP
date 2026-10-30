# Classificação de sinais SSVEP

Trabalho de análise e classificação de sinais de EEG do tipo **SSVEP** (*Steady-State Visually Evoked Potential*) usando o **AVI SSVEP Dataset** (parte *single-target*).

## Etapas

| Notebook | Conteúdo | Situação |
|---|---|---|
| [`01_leitura_dos_dados.ipynb`](01_leitura_dos_dados.ipynb) | Estrutura dos dados e comparação dos 4 participantes | ✅ concluído |
| Pré-processamento e classificação | Filtros, janelas, extração de características e classificadores | próxima etapa |

## Como rodar

1. Instale as dependências:
   ```
   pip install -r requirements.txt
   ```
2. Baixe o **AVI SSVEP Dataset** em www.setzner.com e coloque os arquivos `Sub1_singletarget.mat` a `Sub4_singletarget.mat` na pasta `dados/`.
3. Abra o notebook:
   ```
   jupyter notebook 01_leitura_dos_dados.ipynb
   ```

Os arquivos do dataset não estão neste repositório porque os termos de uso não permitem republicá-los.

## Referência

Vilic, A. *AVI SSVEP Dataset*. www.setzner.com, 2013.
