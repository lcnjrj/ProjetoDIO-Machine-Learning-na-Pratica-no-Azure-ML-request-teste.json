Como Entregar esse projeto?

1. Crie um novo repositório no github com um nome a sua preferência
2. Crie um modelo de previsão com seus devidos pontos de extremidade configurados
3. Escreva o passo a passo desse processo em um readme.md de como você chegou nessa etapa
4. Salve nesse repositório o readme.md e o arquivo .json de pontos de extremidade
5. Compartilhe conosco o link desse repositório através do botão 'entregar projeto'

6. Passo-a-Passo
https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html
https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/02-content-safety.html

No passo "URL da Web", informei a URL https://aka.ms/bike-rentals do conjunto de dados. 

Todas as vezes que tentei com a url fornecida acima deu erro e tive de reiniciar, então achei nesse git https://github.com/casjunior93/Projeto-DIO---Trabalhando-com-Machine-Learning-na-Pratica-no-Azure-ML/blob/main/README.md uma url alternativa, usei essa URL: https://raw.githubusercontent.com/MicrosoftLearning/mslearn-ai-fundamentals/main/data/ml/daily-bike-share.csv  e continuei seguindo as instruções da url:
https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html

teste.json

{
  "Inputs": {
    "data": [
      {
        "day": 1,
        "mnth": 1,
        "year": 2024,
        "season": 1,
        "holiday": 0,
        "weekday": 0,
        "workingday": 0,
        "weathersit": 0,
        "temp": 0.0,
        "atemp": 0.0,
        "hum": 0.0,
        "windspeed": 0.0
      }
    ]
  },
  "GlobalParameters": 0.0
}


Resultado:

{
  "Results": [
    365.0545351117373
  ]
}
