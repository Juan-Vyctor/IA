# Tratamento dos Dados

> **Cada arquivo vai se referir a uma "parte" do tratamento, já que os notebooks não se conversam, tem que começar a partir do arquivo novo.**

# Arquivo CSV

### The uploaded CSV contains **3,736 rows and 36 columns**.

The wavenumber values are ordered from approximately **399.19 to 4000.60 cm⁻¹**. The uploaded file contains **no missing values**.

### `wavenumber` — FTIR wavenumber in cm⁻¹

A faixa de infravermelho usada em cada amostra de célula, nesse caso tratado como ID das linhas.

Seguindo a IA do Google:

> "It acts as the exact 'address' or coordinate on a graph where a specific biological molecule (like a protein, DNA, or sugar) reveals its presence."

Cada valor representa a posição na faixa infravermelha, e os valores em cada coluna representam o quanto a amostra reage à essa exposição.

### `M1_1` to `M1_12` — Primary cervical carcinoma spectra

Celulas no "segundo" estágio de degradação. Elas degradam de "saudável" para isso.

### `M2_1` to `M2_11` — Metastatic cell spectra

Células no "terceiro" estágio de degradação. Elas degradam de M1_1/12 para isso.

### `PC_1` to `PC_12` — Healthy cervical cell spectra

Células saudáveis, sem degradação. Elas estão saudáveis e começam a degradar a partir daqui.
