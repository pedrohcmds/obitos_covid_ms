# Análise preditva dos óbitos causados por COVID-19 no MS

## Resumo


A pandemia do COVID-19 é um evento muito impactante na vida das pessoas. Por esse motivo e também pela falta de ações do Estado, o número de óbitos foi muito grande. E mesmo que cada vida importe, o número de óbitos vistos por essa doença é assustador. 

Além disso, é difícil entender quais dos casos realmente são causados pela covid, uma vez que muitos pacientes acabam falecendo antes da confirmação da doença. Por esse motivo nos datasets, muitas portes por SARS - Síndrome Respiraória Aguda Grave, ou mesmo pneumonia são somadas ao número de óbitos causados por covid.

Diante disso este projeto busca criar um modelo preditivo para o número de óbitos confirmados de COVID-19 no Estado de Mato Grosso do Sul partir da análise da série temporal deses dados.


<center><img src="https://user-images.githubusercontent.com/37647139/133510771-5a1b6714-4d27-43ff-8ee1-8ed037f23163.png" alt="Bandeira do Mato Grosso do Sul" width="150"/></center>

Porque no Mato Grosso do Sul? 3 principais motivos: 
- Porque é o estado que mais tem vacinado sua população entre todos do Brasil;
- Porque é um estado com questões próprias interessantes, como a grande faixa fronteiriça;
- E finalmente, porque é meu estado de nascimento

## Objetivo

Criar um modelo, a partir dos dados coletados, que possa fazer uma previsão do número de óbitos confirmados de COVID-19, além de identificar a tendência de aumento ou diminuição no número de óbitos.

## Dos dados

Os dados usados nesse projeto são derivados da plataforma de dados abertos [brasil.io](https://brasil.io/dataset/covid19/caso_full/), que tem feito um excelente trabalho em reunir os dados relacionados à pandemia do COVID-19 no Brasil.

## Resultados

Os resultados demonstram uma tendência que queda do número de casos confirmados de COVID-19 no Mato Grosso do Sul a partir de agosto de 2020, permanecendo assim até o fim do ano.


<img src="https://github.com/pedrohcmds/obitos_covid_ms/raw/main/dados/images/modelo_previs%C3%B5es.png" alt="Gráfico do modelo de previsões com changepoints em vermelho" width="600"/>

Além disso foram analisados a tendência, efeitos de feriados e dos dias da semana nos dados, como pode ser visto na imagem abaixo:

<img src="https://github.com/pedrohcmds/obitos_covid_ms/raw/main/dados/images/tend%C3%AAncia.png" alt="Gráfico do modelo de previsões com changepoints em vermelho" width="600"/>

## Conclusão


Dessa forma, entende-se que o modelo previu corretamente a queda do número de casos a aprtir do mês de agosto, quando a vacinação teve início. Além disso, a partir dessas análises foi possível entender quais os pontos no tempo que mais resultaram em alterações de tendência:

- A partir de abril com um tendência de alta forte
- A partir de Agorsto, com uma tendência de queda pouco acentuada.

