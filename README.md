# ndvistats
Jupyter Notebook com fluxo de cálculo de estatísticas zonais para polígonos selecionados utilizando geopandas, google earth engine api, rasterio, rasterstats e folium.

O objetivo do código é aplicar operações em vetores e dados raster utilizando python, e elaboração de figuras em QGIS.

Encontrar geometrias inválidas no arquivo polygons_test.GeoJSON. Propor um método de correção em python e aplicá-lo;
Calcular a área dos polígonos em hectares;
Utilizando o layer de UCs, obter para cada polígono se há intersect com alguma UC. Calcular a área de intersect e obter o nome da UC correspondente a cada polígono;
Baixar as últimas 5 datas de imagem Sentinel-2 (sem nuvem), calcular NDVI e recortar as imagens utilizando os polígonos obtidos no item anterior.
Calcular estatísticas zonais de média, mínimo,máximo e desvio padrão de NDVI referente a cada imagem.
Gerar mapas de NDVI recortado para cada data de imagem Sentinel-2. Utilizar preferencialmente map-composer do QGIS.
