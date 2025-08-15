# Case_Credito_Bancario

Temos um cenário onde uma empresa decide adotar modelos preditivos de crédito bancário. Porém, a mesma foi questionada do por quê adotar esse novo modelo.
Os clientes querem uma explicação clara, específica e concreta de como iria funcionar este modelo.
Com isso, fomos orientados a desenvolver um dataset de crédito bancário onde eu vou mostrar como foi feito os códigos e a biblioteca LIME.

Primeiro, fiz as instalações das bibliotecas que eu utilizei, além do modelo que escolhi usar (neste caso, foi o Modelo de Regressão Linear)
<img width="660" height="114" alt="image" src="https://github.com/user-attachments/assets/4455dbe8-69e7-4b1d-8f31-8ed95ccc528e" />

Depois, gerei os dados e executei o comando para salvar no arquivo csv:
<img width="851" height="674" alt="image" src="https://github.com/user-attachments/assets/daa84d8f-cfdd-4009-b7c2-5b08f853fb59" />
Nesse código, coloquei o histórico de inadimplência da empresa, ou seja, as pendências financeiras que ela possui com os clientes, utilizando 100 linhas.
Observação: o "size" dentro do código significa linhas e, o número depois do igual (=), quer dizer a quantidade de linhas.

Aqui, eu fiz tanto o treino como o teste com as variáveis X e Y, com o Modelo de Regressão Linear:
<img width="777" height="251" alt="image" src="https://github.com/user-attachments/assets/65249e01-b79d-407c-9b5e-431374291247" />

Fiz uma previsão referente ao limite do cliente que ele pode usar. A variável X para teste é a "Renda" e o "Limite_credito" e a Y usada para teste e previsão é o "Score_Credito"
<img width="1024" height="744" alt="image" src="https://github.com/user-attachments/assets/d7e02d5c-205a-4c5d-9a9a-3245b0cc130a" />

Aqui, usei o comando para instalar freeze no intuito de capturar todo o desenvolvimento dos códigos e instalei as bibliotecas:
<img width="914" height="723" alt="image" src="https://github.com/user-attachments/assets/e7b1dc27-2897-49af-86c2-484a06f9c390" />

Instalei o LIME no intuito de trazer explicações claras sobre esse novo modelo e como ele tomou essa decisão. Vou mostrar tanto ele sendo instalado como ele sendo executado:
<img width="1197" height="434" alt="image" src="https://github.com/user-attachments/assets/87a8715e-4ecd-43da-a16a-8e139cac31f2" />
<img width="1852" height="671" alt="image" src="https://github.com/user-attachments/assets/561b2380-c1c3-4133-889c-8f72d6c35988" />

Como nos foi passado, poderia ter o uso de IA para nos ajudar a fazer o dataset, emtão, utilizei IA para ter um norte de como fazer o trabalho. Esse basicamente foi o meu trabalho, espero que goste!
