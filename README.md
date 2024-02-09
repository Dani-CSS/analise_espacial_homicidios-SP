# analise_espacial_homicidios-SP
Análise espacial com Python, utilizando a biblioteca GeoPandas, dentre outras, para visualização da distribuição espacial dos homicídios dolosos cometidos no estado de São Paulo no ano de 2022.

Foram feitas algumas manipulações e análises preliminares dos dados, incluindo a substituição de valores nulos pela média dos valores e a transformação de algumas colunas em inteiros.

Utilizando bibliotecas como Matplotlib e Seaborn, foram incluídas algumas visualizações dos dados, com boxplots das variáveis de idade em relação ao sexo e à cor da pele, bem como um histograma da idade em relação ao sexo.

Além disso, foram adicionadas informações georreferenciadas aos dados, culminando em um GeoDataFrame para a visualização geoespacial dos casos de homicídios em São Paulo. Os gráficos de barras mostram o ranking das cidades com base na incidência dos homicídios.

# requirements

pandas==1.3.3
numpy==1.21.2
matplotlib==3.4.3
seaborn==0.11.2
geopandas==0.10.2
shapely==1.7.1
geobr==0.1.8
libpysal==4.5.1
esda==2.4.0
splot==1.1.3

