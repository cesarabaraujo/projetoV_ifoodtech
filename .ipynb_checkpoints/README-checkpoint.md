# Módulo: Técnicas de programação I (PY) #
Oferecido por: 
 <i class="fas fa-laptop"></i> 📔 AdaTech e Ifood <i class="fas fa-laptop"></i> 📔


**Professores:**
<i class="fas fa-laptop"></i> 📔 Carlos Stefano Filho & Rudiney Casali <i class="fas fa-laptop"></i> 📔


**Participação**

⭐ O grupo é composto por 6 integrantes, trabalhamos via Git/GitHub e podemos ver a participação conforme a quantidade de commits realizadas no Projeto.


**Grupo 02**  

Composto por: 
⭐César Augusto<br>
⭐Eduardo Carvalho<br>
⭐Iago Mansur<br>
⭐Leonardo Henrrique<br>
⭐Myrna Martinelli<br>
⭐Ruan Faria<br>


⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐


<center><h3>Projeto Vem Ser Tech 2023 - <DS> Turma 1105<h3></center>

**Objetivo e Orientações do Projeto**<br> Realizar uma análise exploratória de dados utilizando um Conjuto de Dados de livre escolha.
Estruture sua análise criando um storytelling: Uma história contada com informações, gráficos, imagens e medidas estatísticas, associando dados a fatos em uma linha do tempo.
Podendo incluir quantas bases considerar necessário e filtrar as informações mais relevantes para sua história.  
  
**Banco de Dados**
  
<a href="https://raw.githubusercontent.com/cesarabaraujo/projetoV_ifoodtech/main/Clean_Ads_Data.xlsx" class="btn" target="_blank">Link para o Banco de Dados</a>

O Banco de Dados é relacionado a campanhas de Anúncios (Advertising).
Nele está disponível os vários tipos de Ads e as principais métricas.


⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐


**Introdução sobre o Projeto**

Realizamos toda a tratativa dos dados, com vários trechos de códigos relevantes ao aprendizado e entendimento do comportamento dos dados.


**Etapa 1. Pré-Processamento dos Dados**

No pré-processamento foram observadas as seguintes características:
- Apenas a coluna "AD Size" tem um valor nulo em comparação com as outras;
- Temos 25857 observações não nulas;
- Os tipos das variáveis são condizentes com o que representam.
- 75% ou mais das taxas gira em torno tem o valor de 0.35
- Temos alguns valores zerados
- 25% dos dados apresentam um CPC de 0.4999 que é mais de 4 vezes o valor que separa 50% dos dados. O que ocorre nesses casos e como evitar?


**2. Identificação e Tratamento de Outliers**

Na etapa de tratamento dos Outliers foram observadas as seguintes características:
- Todos as colunas numéricas contam com uma grande quantidade de outliers;
- Avaliando os gráficos, embora os outliers estejam destacados parecem fazer sentido, já que muitos estão apenas relacionados com as escolhas feitas pela equipe responsável pelas propagandas (ao gastar mais, é natural aumentarmos o valor de várias outras colunas);
- CTR parece uma concentração de valores com apenas alguns outliers;
- A maior parte das distribuições das variáveis quantitativas se aproxima de uma destribuição uniforme;
- Os outliers parecem ter um padrão e também parecem estar em destribuição uniforme, porém em quantidades menores é menos visível;


**Etapa 3. Perguntas de Negócio**

Abaixo foram respondidas algumas perguntas importantes:

- Qual plataforma teve mais impressões?

![Resultado 1](Imagens/output1.png)
![Resultado 2](Imagens/output2.png)


- Qual formato teve maior quantidade de clicks?

![Resultado 3](Imagens/output3.png)
![Resultado 4](Imagens/output4.png)

Acima podemos observar:
+ Vídeo é a melhor plataforma tanto relação formato vídeo quanto o formato display, mas a frente iremos investigar se isto também ocorre em relação ao CPC;
+ App é a única plataforma que display é melhor que vídeo;


- Qual a melhor plataforma em relação ao CPC?

![Resultado 5](Imagens/output5.png)

Acima podemos observar:
+ Apesar do vídeo apresentar impressões e clicks superiores, o custo por click é muito próximo entre as plataformas


- Qual o melhor formato em relação ao CPC?

![Resultado 6](Imagens/output6.png)


- Qual o melhor dia da semana em relação ao CPC?

![Resultado 7](Imagens/output7.png)


- Qual o melhor horário em relação ao CPC?

![Resultado 8](Imagens/output8.png)


- Qual foi a variação do custo por Click?

![Resultado 9](Imagens/output9.png)


- Qual horário tem maior disponibilidade e menor custo?

+ Horário com maior disponibilidade: 21
+ Horário com menor custo: 23

- Qual melhor horário em relação ao CPC/Clicks??

![Resultado 10](Imagens/output10.png)
![Resultado 11](Imagens/output11.png)


- Qual o melhor dia da semana em relação aos Clicks?

![Resultado 12](Imagens/output12.png)



⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐


## Como Usar

Para utilizar este projeto, siga estes passos:

1. Clone o repositório em seu ambiente local.
2. Certifique-se de ter Python instalado.
3. Execute os arquivos Python correspondentes a cada funcionalidade para interagir com o sistema.


## Requisitos

- Python 3.x


## Contribuições e Feedback

Contribuições são bem-vindas! Se encontrar erros ou tiver sugestões para melhorar o projeto, fique à vontade para criar issues ou enviar pull requests.


## Licença

Este projeto é licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.