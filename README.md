[![author](https://img.shields.io/badge/author-MauricioEloy-red.svg)](https://www.linkedin.com/in/mauricio-eloy) [![](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-365/) [![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/MauricioEloy/Portifolio/issues)

<p align="center">
<img src="LOGO.png" >
</p>

# <span style="color:blue">Ciência de Dados</span>

**Mauricio Eloy**<br>

---
###### Contatos:
*email:* profmauricioeloy@gmail.com | mauricioeloy@usp.br

*LindedIn*: https://www.linkedin.com/in/mauricio-eloy/


---


## <span style="color:blue">Solução Inicial</span>
### <span style="color:blue">Passo-a-passo</span>

Toda a solução foi obtida utilizando-se de bibliotecas e ferramentas open source​.

Utilizou-se da linguagem de programação Python como kernel no Jupyter Notebook.

Foi utilizado o ambiente local para a execução dos códigos, mas você pode reproduzir na nuvem se preferir, uma opção é o Google Colaboratory.

Independente do ambiente que escolher você precisará da a versão 3.8.5 do Python e das bibliotecas utilizadas na solução instaladas.

Caso você opte por reproduzir a solução localmente eu sugiro que instale a distribuição Anaconda Python (https://www.anaconda.com/products/individual).

Instalando esta distribuição você trará para o seu ambiente grande parte das bibliotecas utilizadas nesta solução.

---
## <span style="color:blue">Próximos Passos</span>

### <span style="color:blue">Análise_ML</span>

1. Entender com os envolvidos no problema se na frase ```true_class - A classe verdadeira (se nula, assumir o pred_class)```, tanto ```NaN``` quanto $0$ são considerados nulos;

2. Dependendo da resposta do item anterior a abordagem utilizada deve ser reestruturada.

OBS: um dos pontos falhos nesta solução inicial é a a utilização de variáveis de vazamento para o treinamento do modelo.

### <span style="color:blue">NLP</span>

1. Melhorar a estrutura dos dados de entrada no modelo, utilizando-se de técnicas de PNL para "faxinar" os dados;

2. Fazer stacking de modelos para verificar se obtemos uma melhora significativa;

3. Obter os melhores hiperparâmetros dos melhores modelos para verificar se obtemos uma melhora significativa;

4. Colocar o modelo obtido dos passos anteriores em produção.

OBS: um dos pontos falhos nesta solução inicial é a não padronização da vetorização dos dados, que em cada situação gera uma dimensão diferente, este é uma das principais correções a serem realizadas.