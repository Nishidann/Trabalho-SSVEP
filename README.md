# Classificação de sinais SSVEP

Trabalho de análise e classificação de sinais de EEG do tipo **SSVEP** (*Steady-State Visually Evoked Potential*) usando o **AVI SSVEP Dataset** (parte *single-target*).

## Notebooks

| Notebook | Conteúdo | Abrir no Colab |
|---|---|---|
| `01_leitura_dos_dados.ipynb` | Estrutura dos dados e comparação entre os 4 participantes | [Abrir](https://colab.research.google.com/github/Nishidann/Trabalho-SSVEP/blob/main/01_leitura_dos_dados.ipynb) |
| `02_preprocessamento.ipynb` | Conversão para o MNE, filtro passa-faixa e espectros no domínio da frequência | [Abrir](https://colab.research.google.com/github/Nishidann/Trabalho-SSVEP/blob/main/02_preprocessamento.ipynb) |

## Como rodar

### No Google Colab

Abra o notebook pelo link da tabela e execute as células em ordem. A primeira célula de código baixa os dados e instala o que faltar.

### No computador

1. Instale as dependências:
   ```
   pip install -r requirements.txt
   ```
2. Abra os notebooks em ordem:
   ```
   jupyter notebook 01_leitura_dos_dados.ipynb
   ```

A primeira célula de código de cada notebook cria a pasta `dados/` com os arquivos `Sub1_singletarget.mat` a `Sub4_singletarget.mat`, copiados do repositório de tutoriais da disciplina ([bneurd/tutoriais](https://github.com/bneurd/tutoriais)). Se a pasta `dados/` já existir, nada é baixado. Para isso, o `git` precisa estar instalado.

Os arquivos do dataset não estão neste repositório porque os termos de uso não permitem republicá-los.

## Referência

Vilic, A. *AVI SSVEP Dataset*. www.setzner.com, 2013.
