# Optimization of assigning offshore platforms to airports

Simple optimization example of assigning offshore platforms to airports at Campos Basin regarding the demand for staff on oil rigs


The main objective of this repository is to develop a simple optimization example of **assigning offshore platforms to airports** at  *Campos Basin* regarding the demand for staff on oil rigs. On a daily basis, workers and equipment have to go back and forth to these offshore platforms. Companies want to minimize the cost associated to logistics by optimally choosing :

The airport that will service each offshore platform
- The size of the fleet of vehicles to be made available at each location
- The number of trips made by each vehicle to assure the demand for supplies of each platform



## Contents




### 1. Requirements
This text files contains all of the Python packages that need to be installed prior to the execution of the notebook
The packages I used to run the code in the book are listed in requirements.txt (Note that some of these exact version numbers may not be available on your platform: you may have to tweak them for your own use). To install the requirements using conda, run the following statement from the command-line:
```
 
$ conda install --file requirements.txt

```

### 2. Notebook

The file [producao_bacia_campos.ipynb](https://github.com/piagaarcia/otimizacao-petroleo-offshore/blob/main/producao_bacia_campos.ipynb) contains the notebook with the model.

### 3. Packages


The following Python packages are used in this notebook.

- Pandas
- Geopandas
- Matplotlib
- Seaborn
- Numpy
- Acos, Cos, Sin from Math
- LpProblem, LpVariable, LpMinimize, LpStatus, LpSum, value
- Warnings

### 4. Data Source

You may download the data from this sources:

First, regarding the basis in production [CAMPOS_EM_PRODUCAO](http://hmlapp5.anp.gov.br/geoserver/oracleworskspace/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=oracleworskspace:CAMPOS_PRODUCAO_SIRGAS&outputFormat=JSON)

[MUNICIPIOS_RJ](https://geoftp.ibge.gov.br/organizacao_do_territorio/malhas_territoriais/malhas_municipais/municipio_2019/UFs/RJ/rj_municipios.zip)

Finally, concerning the [UEPS_OPERACAO](https://www.gov.br/anp/pt-br/centrais-de-conteudo/dados-abertos/arquivos/lpo/dados-abertos-ueps-operacao-1.csv)




## Credits

All credits go to [Vinicius Sanches](https://github.com/vinismachadoo)
 


