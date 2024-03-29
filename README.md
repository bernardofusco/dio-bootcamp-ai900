# dio-bootcamp-ai900

Respositório dos dados do Bootcamp da DIO (Digital Innovation One) AI 900 - Microsoft

Desafio do módulo 1
Depois de configurado o machinelearning do mslearn-bike-automl, tendo como referência:
https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html

É pedido que se crie o modelo de previsão com seus devidos pontos de extremidade configurados.
Após realizado descrever o passo a passo.

1 - Navegar até 'ML Automatizado' do lado esquerdo do painel;

2 - Selecionar o trabalho criado 'mslearn-bike-automl';

3 - Na aba superior selecionar 'Modelos + trabalhos finos';

4 - Selecionei o algoritmo 'VotingEnsemble';

5 - Selecionei 'Implantar' e a opção 'serviço Web' para implantar o modelo;

6 - Para preenchimento dos dados utilizei:

    Nome: predict-rentals
    Descrição: prever aluguéis de bicicleta
    Tipo de computação: instância de Contêiner do Azure
    Habilitar autenticação: Selecionado
    Clicar em 'Implantar'

7 - Depois de implantado, testar;

8 - Em Estúdio do Azure Machine Learning, no menu à esquerda, selecione Pontos de Extremidade e abra o ponto de extremidade em tempo real predict-rentals;

9 - Na página do ponto de extremidade em tempo real de predict-rentals, exiba a guia Testar;

10 - No painel Dados de entrada para testar o ponto de extremidade, substitua o modelo JSON pelo arquivo 'InserirDados.json';

11 - Clicar em 'Testar';

12 - O painel de teste pegou os dados de entrada e usou o modelo treinado para retornar o número previsto de locações;

13 - O resultado do teste foi salvo no arquivo 'Resultado.json'.
