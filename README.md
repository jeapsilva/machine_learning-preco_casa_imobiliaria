# Algoritmo para Predizer Preço de Imóvel na Cidade do Rio de Janeiro.

Esse projeto mostra todo o pipeline de preparação, treinamento e aplicação de um modelo de Machine Learning, cujo dataset encontra-se no formato json.

Nesse projeto é utilizado a Regressão Linear através de 3 técnicas: Regressão Linear, Árvore de Decisão e Florestas Aleatórias. Em seguida dos três algoritmos são comparados através das métricas R², Erro Quadrado Médio(EQM) e Raiz Quadrada do Erro Quadrado Médio(EQM²). 

Feito isso, o algoritmo de Árvore de Decisão e Floresta Aleatória são otimizados através de dois métodos: Validação Cruzada e RandomSearchCV. Por fim, essas duas análises também são comparadas através das métricas de R², EQM e EQM². Logo, a análise final utiliza o modelo que possui maior R² e menor EQM. 

Por fim, após o modelo final ser otimizado com os hiperparâmetros testados na validação cruzada e no RandomSearchCV, o modelo é exportado para que possa ser utilizado para predições no futuro. Vale ressaltar que salvar esse modelo foi importante pois a otimização demorou um tempo e exigiu um poder computacional. 

Além de exportar o modelo, também foi criado uma interface para input das variáveis necessários para predizer o preço. Desse modo o algoritmo pode ser utilizado a partir de um botão "CALCULAR", dando liberdade para o usuário que queira utilizar o código, mas não tenha tanto conhecimento sobre a programação envolvida.
