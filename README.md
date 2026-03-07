# Ponderada sobre camada física do modelo TCP/IP

## Vídeo demonstrativo: [link]()

## PARTE 1: Rede com HUB e análise de propagação do sinal 

O cenário pode ser encontrado no arquivo [cenario1.pkt](./cenario1.pkt).

<img src="./img/cenario1.png">

### Tarefas

* **Teste conectividade com ping entre todos**

<img src="./img/ping.png">

* **Envie uma Simple PDU do PC0 para PC2**

<img src="./img/pdutest.png">

* **Observe a simulação completa**

<img src="./img/simulacao.png">

### a) Por que todos os nós recebem o quadro inicialmente dentro de um hub?

### b) Explique como isso se relaciona ao conceito de meio compartilhado com desempenho real na camada física.

## PARTE 2: Rede com SWITCH e comparação física

### Tarefas

<img src="./img/cenario2.png">

* Aguarde a estabilização das portas.

<img src="./img/estabilizacao-portas.png">

* Teste conectividade.

<img src="./img/ping2.png">

* Envie novamente uma Simple PDU do PC0 para PC2.

<img src="./img/pdu2.png">

* Observe a simulação.

<img src="./img/simulacao2.png">

### a) Compare o fluxo do sinal elétrico no switch versus hub.

### b) Por que agora a PDU não é propagada para todos os nós da mesma forma?

### c) O switch elimina o meio físico compartilhado? Justifique tecnicamente.