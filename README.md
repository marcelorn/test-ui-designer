# Teste UI Designer - Aplicação de Previsão do Tempo

Você foi contratado para elaborar o design da aplicação de previsão do tempo para um cliente e deve entregar para a equipe de desenvolvimento responsável as informações necessárias para implementação da aplicação de forma a atender aos requisitos descritos abaixo. A equipe de Frontend tem experiência em ReactJS e Material-UI e espera receber as informações de design para iniciar o desenvolvimento.

## Descrição da Aplicação

O objetivo é prover ao usuário uma interface em que ele possa visualizar as informações de previsão do tempo para pontos georreferenciados em um mapa. No mapa serão exibidos os pontos em que existe previsão do tempo disponível e o usuário poderá selecionar o ponto para visualizar a previsão do tempo para 7 dias, que aparece sobre o mapa. O usuário poderá trocar o ponto e assim visualizar as previsões de diferentes regiões do mapa.
A aplicação também disponibiliza um dashboard com informações mais detalhadas da previsão do tempo diária (7 dias) e horária (48 horas), a partir de gráficos, onde o usuário poderá verificar o comportamento das variáveis ao longo do tempo de forma visual. O dashboard detalhado pode ser acessado a partir do mapa e o usuário poderá retornar ao mapa a partir do dashboard.

## Requisitos:
* A tela principal da aplicação deve ser um mapa com botões de navegação (busca por locais ou pontos de previsão, zoom, modo mapa ou satélite, etc).
* Os pontos com previsão do tempo devem estar marcados no mapa e ter um nome associado que pode ser buscado pelo usuário.
* Ao selecionar um dos pontos de previsão a informação de previsão para 7 dias deve ser exibida.
* A previsão do tempo para 7 dias deve ser exibida sobre o mapa em um formato intuitivo e resumido, contendo as seguintes informação:
  * Data da previsão
  * Temperatura Máxima e Mínima (ºC)
  * Precipitação Máxima e Mínima (mm)
  * Chance de chuva (sem chuva, baixa, moderada, alta e altíssima)
  * Velocidade do vento (km/h)
* Além da informação de previsão do tempo, seria interessante apresentar um resumo da semana com as informações de:
  * Chuva acumulada (total da semana)
  * Dias com chuva
  * Maior volume de chuva registrado
* A partir da tela de mapa deve ser possível o usuário acessar a previsão detalhada para os pontos de previsão através de um dashboard com gráficos/tabelas.
* No dashboard de mapa estará disponível 2 tipos de previsão:
  * previsão diária para 7 dias
  * previsão horária para 48 horas
* Os dados da previsão detalhada deve incluir as seguintes variáveis:
  * Temperatura
  * Precipitação
  * Umidade relativa do ar
  * Temperatura de ponto de orvalho
  * Velocidade do vento
  * Direção do vento

## Notas
A expectativa da equipe é receber as informações abaixo:
* Fluxos mostrando a jornada do usuário;
* Wireframes, mockups e protótipos de alta fidelidade;
* Design baseado em componentes do Material-UI;
* Aplicação de princípios de usabilidade.

## Compartilhando o Resultado
Depois de finalizar o trabalho, coloque o resultado em um repositório git privado (GitHub, BitBucket e GitLab oferecem repositórios privados para contas gratuitas) e dê permissão de acesso à pessoa responsável pelo processo de seleção.
