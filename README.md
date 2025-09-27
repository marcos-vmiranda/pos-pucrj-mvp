**PUC Rio - Pós Graduação em Ciência de Dados e Analytics**
# MVP: *Machine Learning & Analytics*
- **Autor:** Marcos Vinícius de Miranda  
- **Data:** 27/09/2025
- **Matrícula:** 4052025001185

## 1. Descrição do projeto

O objetivo desse projeto é desenvolver um modelo de classificação para prever se um veículo irá atrasar mais que 30 minutos (tempo padrão de tolerância), a partir de informações históricas das viagens de todos os veículos.

A aplicação desse modelo será na antecipação da chamada dos veículos que já estejam na base, em detrimento dos veículos que tenham previsão de atraso.

Em uma base de distribuição de combustíveis é de grande importância que o atendimento seja feito ao longo do dia de maneira uniforme, a fim de evitar horários de pico que geram excesso de veículos e filas na base, causando insatisfação dos clientes. Os atrasos da chegada dos veículos em relação ao horário agendado prejudicam a eficiência da base, uma vez que a as baias de carregamento ficam vazias aguardando os veículo atrasados.

Essa aplicação é de grande valor para o negócio, pois irá gerar os seguintes benefícios:
  - Evitar que a base fique aguardando um veículo que provavelmente irá atrasar
  - Reduzir o tempo médio de permanência na unidade (TMPU), que é um indicador operacional importante
  - Aumentar a eficiência operacional da base, ou seja, permitir que mais veículos sejam carregados num mesmo tempo
  - Aumentar a taxa de ocupação das baias
  - Melhorar o nível de atendimentos dos clientes, um vez que as filas e os tempos de espera serão reduzidos

## 2. Descrição dos arquivos
- MVP_ML_marcosMiranda.ipynb: notebook do projeto
- requirements.txt: pacotes necessários ao notebook
- atrasos_tratados.csv: dataset de treino (extraído de janeiro a maio de 2025)
- atrasos_junho_tratatos: dataset de teste (extraído de junho de 2025)
- modelo_atrasos.pkl: arquivo picke do modelo