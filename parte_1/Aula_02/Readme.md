# Aula 02: Por onde começar

Video da aula: [COLOCAR]

ATENÇÃO, AINDA NÃO HÁ PREVISÃO DE QUANDO O CURSO VAI COMEÇAR. Devido à minha rotinha de trabalho, esse curso não vai começar tão cedo. Se você topou com alguma parte dele por acidente, volte em 2025+1.


Identificar e definir a ordem de prioridade de realização de subtarefas é importante não apenas para ter uma melhor eficiência: a o próprio sucesso de realização de uma tarefa depende disso. Para entender melhor como definir essa ordem, temos que entender o que precisamos para realizar uma subtarefa e o qual vai ser o resultado dela. Com isso vamos também conhecer dois conceitos interessantes em programação: entrada e saída.

## O que é preciso para arrumar um quarto?

Essa pergunta parece idiota e a resposta ainda é pior: é necessário um quarto. Você não pode arrumar um quarto sem que haja algum quarto para ser arrumado. Um quarto então é a "entrada" do probelma de arrumação de quarto. Você pode também pensar que precisa de material de limpeza e que o quarto esteja sujo, bem, essa nossa analogia é bastante aberta e isso nãoestaria incorreto, mas vamos tomar só o quarto como entrada aqui, afinal você só vai conseguir definir se o quarto realmente precisa ser limpo e que materiais você vai precisar depois de olhar ele. E em geral a maioria dos algoritmos começa justamente com isso, com a verificação da validade da entrada e em níveis mais baixos de programação com a requisição de memória ao S.O. para realizar determinadas operações (mas não vamos nos preocupar com isso agora)

## Pensando nas subtarefas:

Arrumar o quarto consiste em uma série de tarefas menores, como arrumar a cama, levar a roupa suja para fora, varrer o chão, organizar a mesa, tirar poeira dos móveis... Algumas dessas subtarefas tem suas próprias subtarefas: tirar objetos que não pertencem à escrivaninha dela, alinhas os objetos que pertencer à ela, bater a poeira, passar pano... E algumas dessas tarefas se intercalam: tecnicamente você tem que passar o pano na escrivaninha no meio da arrumação delas. Essa análise nos dá uma pista boa de quais subproblemas serão resolvidos primeiro.

## Impedimentos e entradas requeridas:

Se o chão do quarto está entulhado de coisas, talvez seja impossível ou inviável chegar até a escrivaninha para arrumar ela. Para passar pano no chão, temos que varrer antes ou o excesso de poeira vai virar um barro com a agua do pano. Algumas subtarefas são impossíveis de serem executadas sem que alguns problemas sejam resolvidos antes, outras exigem que a entrada satisfaça certas condições.

## Resultado de ações:

Ao bater o pó dos móveis, a poeira vai para o chão. O resultado dessa ação não é apenas um móvel limpo, mas um chão empoeirado. O resultado de varrer o chão é um chão não empoeirado. O resultado de algumas tarefas podem afetar mais de um elemento e até fazer com que um elemento já tratado, volte ao seu estado inicial. 





