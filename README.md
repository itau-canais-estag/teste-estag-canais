# teste-estag-canais123122321312312

![alt text](https://static.vecteezy.com/system/resources/previews/003/326/613/non_2x/software-engineering-concept-for-website-and-mobile-site-vector.jpg)

Olá! Para seguirmos com o nosso processo seletivo do nosso programa de estágio, precisamos que você solucione o problema de lógica abaixo:

Primeiro, clone esse projeto na sua máquina e crie uma outra branch com seu nome a partir dela. Ex.: teste/joao_da_silva (ler documentação - https://rogerdudler.github.io/git-guide/)

A partir de uma entrada de arquivo TXT, como o contido neste repositório, com dados no seguinte formato: 

 "{\"id_transferencia\":1,\"valor_transferencia\":\"500\",
 \"tipo_transferencia\":\"PIX\",\"nome_emissor\":\"joao\",
 \"agencia_emissor\":\"001\",\"conta_emissor\":\"1234\",
 \"cpf_emissor\":\"123.123.123-12\",\"nome_receptor\":\"maria\",
 \"agencia_receptor\":\"002\",\"conta_receptor\":\"1335\",
 \"cpf_receptor\":\"112.113.114-15\"}" 

Desenvolva um algoritmo que execute operações de transferência bancária obedecendo os seguintes critérios: 

1. Toda transferência deverá ser feita entre um emissor e um receptor;
2. Operador e receptor iniciam a operação com um saldo de R$ 0,00;
3. As transferências deverão ser executadas de acordo com o seu tipo, sendo 3 os seus tipos: PIX, TED e DOC;
4. O limite de valor máximo permitido para uma transferência via PIX é de R$ 5 mil; 
5. Transferências via TED só são permitidas para valores acima de R$ 5 mil e até R$ 10 mil; 
6. Transferências via DOC só são permitidas para valores acima de R$ 10 mil; 
7. Não serão permitidas transferências para a mesma conta, mas um emissor pode transferir para ele mesmo se for uma conta diferente;
8. As entradas deverão estar sempre com todos os dados preenchidos.

Ao final da operação, uma mensagem deverá ser exibida: 

1. Se a transferência for bem sucedida, exibir mensagem de sucesso com o saldo do emissor e do receptor após a transferência, de acordo com o modelo:

**Sua transferência foi realizada com sucesso!<br> 
Saldo do emissor: R$ X,XX<br>
Saldo do receptor: R$X,XX**<br>

4. Se a transferência não for completada, exibir mensagem de erro explicando o motivo, vide exemplo: 

**Sua transferência não foi completada pois (escrever o motivo)**

Escolha, dentre as opoções de linguagens de programação abaixo, qual se sentir mais confortável em desenvolver o algoritmo e pense nos casos de teste descritos acima! 

1. Java
2. Python
3. Swift
4. Kotlin
5. Typescript 
6. C, C++/C#

Ao finalizar o seu desafio, crie um pull request para essa branch, seguindo o passo a passo descrito no link - https://www.webdevdrops.com/como-criar-um-pull-request-no-github-passo-a-passo/

Boa sorte! 

