# Piano

O piano foi baseado no Arduino UNO utilizando os PWMs (Pulse Width Modulation) da placa para simularem um piano sendo que todas as notas básicas podem ser tocadas nele, seguindo a ordem: DÓ, RÉ, MI, FA, SOL, LÁ, SI, DÓ. (Esquerda para direita)

![Alt Text](https://github.com/lucasquental/Piano/blob/master/imagem%201%20git.png)

#Esquema montado no TinkerCad

Como podemos ver, os botões são alinhados e configurados para reproduzir determinada frequência.

![Alt Text](https://github.com/lucasquental/Piano/blob/master/imagem%202%20git.png)

#Código de leitura do piano

Ao analizarmos o codigo podemos ver melhor a assiciaçao entre os botões e as frequências.
O código, primeiramente define as frequências correspondentes às suas respectivas notas musicais e depois as guarda dentro de um vetor chamado "notas". Após as definições são designados os respectivos valores a cada botão, configurando-os como input,e então o código 
verifica se há algum input. Caso haja o código manda um sinal ao buzzer para que reproduza a frequência anteriormente designada, caso contrário não sairá som nenhum.


![Alt Text](https://github.com/lucasquental/Piano/blob/master/Imagem%20real%20git.jpg)

#Imagem real do projeto

Como podemos ver também no video a seguir as frequêcias por estarem muito próximas apenas parecem ser as mesmas, porém se prestarmos atenção conseguiremos diferenciar as frequências.

![Alt Text](https://github.com/lucasquental/Piano/blob/master/Video%20teste.mp4)
#Video de teste

Ao final, com uma adaptação do código, foi possível até reproduzir pequenos trechos de músicas com o buzzer utilizando o mesmo padrão de designação de frequêcias ,apenas alterando-as e colocando em ordem a saida das notas.

![Alt Text](https://github.com/lucasquental/Piano/blob/master/imagem%203.jpg)
