# ✈️ Análise dos dados

## ❓ Qual(s) a(s) companhia(s) que mais registram atrasos?  
- Analise qualitativamente e quantitativamente.

## 🛫 A rota ou aeronave podem influenciar nos atrasos?

## 📈 Existe algum padrão ou tendência nos atrasos?  
- Se sim, o que pode ser feito para reduzi-los?

## ❓ Qual(s) a(s) companhia(s) que mais registram atrasos?  
- Analise qualitativamente e quantitativamente.

## 🕒 Média de atraso - partida  
### 🔍 Análise Qualitativa e Quantitativa

- Classifiquei em três grupos (Baixo Atraso, Médio Atraso e Alto Atraso):
  - **Baixo Atraso**: de 0 min a 10 min
  - **Médio Atraso**: de 11 min a 15 min
  - **Alto Atraso**: a partir de 16 min

- Existem 16 empresas na base de dados e as classificamos das que mais se atrasam para as que menos se atrasam:  
  **F9, EV, YV, FL, WN, 9E, B6, VX, OO, UA, MQ, DL, AA, AS, HA, US**

## 🕒 Média de atraso - chegada  
### 🔍 Análise Qualitativa e Quantitativa

- Classifiquei em quatro grupos (Chegada Antecipada, Baixo Atraso, Médio Atraso e Alto Atraso):
  - **Chegada Antecipada**: a partir de -0
  - **Baixo Atraso**: de 0 min a 10 min
  - **Médio Atraso**: de 11 min a 15 min
  - **Alto Atraso**: a partir de 16 min

- Existem 16 empresas na base de dados e as classificamos das que mais se atrasam para as que menos se atrasam:  
  **F9, FL, EV, YV, OO, MQ, WN, B6, 9E, B6, UA, US, VX, DL, AA, HA, AS**

## 🛫 A rota ou aeronave podem influenciar nos atrasos?  
- A rota ou aeronave não influencia - Companhia F9 e FL  
  - Peguei duas amostras, companhias que mais se atrasam e verifiquei se haveria uma rota alternativa que levasse a atrasos e identifiquei que ambas as Companhias fazem sempre a mesma rota:  
    - Mesma companhia  
    - Origem e Destino  
    - Distância  

## 📊 Existe algum padrão ou tendência nos atrasos?  
- Se sim, o que pode ser feito para reduzi-los?

### 📌 Quais os Padrões encontrados?  
- **Primeiro padrão e tendência:**  
  Quando há atraso na partida possivelmente terá atraso na chegada, portanto o gráfico ao lado representa forte correlação nos atrasos de partida e atrasos de chegada, independente do destino.

- **Segundo padrão e tendência:**  
  Pode-se perceber que nos meses de junho, julho e dezembro, períodos possivelmente de férias, há maiores atrasos. Possivelmente pelo maior fluxo de pessoas e maior demanda.  
  O gráfico representa os atrasos em minutos por mês, referente aos Atrasos de Partida.  
  Podem ser tomadas medidas para melhor lidar com um fluxo maior ou uma demanda maior, como o uso de mais aviões.
