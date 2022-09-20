# Comparação de Modelos Classificadores e Técnicas de Balanceamento:  Classificação da Qualidade do Vinho Tinto
# Os algoritmos são auto explicativos, e os dados estão em: [Link](https://github.com/RenatoMaximiano/Trabalho_ADP2/blob/main/dataset_)
[Algoritmo-1](https://github.com/RenatoMaximiano/Trabalho_ADP2/blob/main/Algoritmo1_Desbalanceado.ipynb) No primeiro algoritmo os dados estão desbalanceados.

[Algoritmo-2](https://github.com/RenatoMaximiano/Trabalho_ADP2/blob/main/Algoritmo2_Balanceamento.ipynb) No segundo algoritmo aplicamos 3 técnicas diferentes de balanceamento nos dados de treinamento de cada iteração, ou seja, sempre balanceando as instancias de cada classe nos 9 folds de treinamento e testando com o fold de teste desbalanceado. Aqui os dados são balanceados antes de entrar no segundo 10-fold-cross-validation, ou seja os novos dados de teste também são balanceados.

[Algoritmo-3](https://github.com/RenatoMaximiano/Trabalho_ADP2/blob/main/Algoritmo3_Balanceado.ipynb) No terceiro algoritmo também  aplicamos 3 técnicas diferentes de balanceamento, porém aqui os dados são balanceados dentro do segundo 10-fold-cross-validation, assim somente os novos dados de treinamento são balanceados, mantendo o desbalanceamento dos novos dados de teste.

<p align="center">
 <img src="https://user-images.githubusercontent.com/84810481/191355583-6d587f92-1fed-4573-88af-fe2c6b83d912.png">
</p>
