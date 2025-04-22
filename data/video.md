# Sumário

- [00:00 Introdução](#introdução)
- [01:00 Uma breve retrospectiva](#uma-breve-retrospectiva)
- [02:00 Lançamento do DeepSeek R1](#lançamento-do-deepseek-r1)
- [04:00 O futuro próximo das IAs](#o-futuro-próximo-das-ias)
- [07:30 Modelos Destilados de IA](#modelos-destilados-de-ia)
- [10:20 Quais os preços dos DeepSeek?](#quais-os-preços-dos-deepseek?)
- [14:00 Explorando o modelo](#explorando-o-modelo)
- [16:00 Fazendo um jogo com Streamlit](#fazendo-um-jogo-com-streamlit)
- [18:50 Como funciona o DeepSeek Local](#como-funciona-o-deepseek-local)
- [24:00 Como rodar o DeepSeek localmente?](#como-rodar-o-deepseek-localmente?)
- [28:22 Finalização](#finalização)

---
## Introdução
**[00:00]**

esse aqui é um vídeo muito especial que
a gente preparou para vocês contendo
toda a informação que o nosso time
conseguiu juntar sobre o Deep seic o
modelo de linguagem aberto chinês que
foi lançado recentemente responsável por
fazer o Mercado de Ações de Big Tex
norte-americano perder mais de 1 trilhão
de valor de mercado em apenas um dia e
até o final dessa masterclass você vai
ter entendido Por que que esse modelo é
tão especial e Que mudanças ele vai
trazer pro mercado de Inteligência
Artificial daqui pra frente você vai
entender a princip qual diferença entre
o modelo Deep seic V3 que é uma versão
mais tradicional comum parecida com o
que a gente utiliza todos os dias e o
rsc R1 que é o responsável por fazer o
mercado ter todo esse reboliço que seria
um modelo de raciocínio vai entender
como utilizar ele no teu navegador e
aproveitar ao máximo dessa
funcionalidade de pensamento explícita
que esse modelo tem e a parte que eu
julgo mais importante eu vou ensinar
vocês a como rodar o d psic R1 e os
modelos que foram treinados a partir
deles diretamente da sua máquina de
maneira 100% offline e sem censura Então

---
## Uma breve retrospectiva
**[01:00]**

bora lá todo esse rebuliço do mercado
começou aqui no dia 26 de dezembro posso
dizer quando foi apresentado o dips V3
que ele é um modelo de linguagem com
características para nós usuários
semelhante ao que seria chat GPT 4 o ou
um Cloud 3.5 sonet no sentido de que a
gente faz perguntas e obtém uma resposta
Direta do modelo e a parte interessante
é que esse modelo foi apresentado com
uma quantidade de parâmetros
relativamente média uma arquitetura não
tão comum que a gente chama de mixture
of experts diferente de modelos
tradicionais aqui como o lama ou quen
que tem uma arquitetura densa e
acredita-se que o chat GPT 4 o e o clou
3.5 Sony também tem um arquiteturas como
essa mas não se sabe porque são empresas
fechadas e ele apresentou aqui bench
Marks que são na maioria das vezes até
superiores aos principais modelos de
mercado aqui o da o cloud 3.5 e o 4 o
mas a parte interessante aqui que esse
modelo ele é de código fonte aberto e
foi treinado de uma forma bem diferente
alguns dias depois eles também lançaram
um aplicativo nas principais app Stores
do mundo mas o reboliço mesmo do mercado

---
## Lançamento do DeepSeek R1
**[02:00]**

aconteceu aqui no dia 20 de janeiro
quando eles lançaram o modelo R1 o R1 é
uma llm que se compara ao modelo mais
poderoso do mundo que a gente tinha
consciência até agora que era o open ai
all one Qual que é a diferença quando a
gente usa o chat GPT normalmente aqui no
modelo 4 o eu faço uma pergunta para ele
ele automaticamente me dá uma resposta
ele começa a Gerar tokens de saída a
partir daqui então se eu peço para ele
aqui Escreva um código em Python para
resolver equação de basca ele
automaticamente começa a me dar as
respostas aqui diretamente no prompt o
modelo onean de raciocínio ele vai
introduzir uma etapa de reflexão sobre
aquele problema antes de nos dar as
resposta então reparem que ele não tá
escrevendo mas ele está pensando
anteriormente essa aqui foi uma técnica
desenvolvida pela Open a para poder
resolver problemas que os outros modelos
estavam falhando por exemplo de
desenvolver código melhor algumas
equações de matemática problemas Gerais
aqui que envolviam um raciocínio mais
profundo raciocínio lógico onde os os
modelos tinham muita dificuldade
cometiam erros até básicos que nós seres
humanos não cometeriam e até esse
momento o o1 era dominante nessa
categoria só que ele tinha um sério
problema ele era extremamente caro para
vocês terem uma ideia que rodar o o1
custava $0 para cada milhão de tokens de
saída em comparação aqui com 4 o que
custava seis vezes menos e o paper que o
deeps lançou ele aponta algumas mudanças
na forma como esses modelos foram
treinados na própria arquitetura e eles
conseguiram atingir esses mesmos
resultados gastando uma pequena fração
do que a gente acreditaria que seria
necessário para treinar um modelo top de
linha como o owan e o fato desse modelo
ter atingido uma performance semelhante
a all one custando 50 vezes menos o
deeps que ainda ter dominado o ranking
de downloads na Apple Store em vários
países nos últimos dias fez com que as
ações do mercado americano abrissem uma
queda bizarra por exemplo a NV aqui na
segunda-feira do dia 27 abriu em queda
de mais de 10% então o mercado começou a
pensar cara talvez não seja necessário

---
## O futuro próximo das IAs
**[04:00]**

todo esse investimento bizarro que tá
sendo feito em placas de vídeo para
treinar modelos tão poderosos porque uma
galera lá na China com muito menos
capital conseguiu ter resultados
semelhantes ao que a gente tem feito
aqui gastando muito menos então o
mercado pensou talvez não seja
necessário fazer esses investimentos
bizarros que TM sido feitos em data
Centers com placas de vídeo de ponta e s
focar em outras arquiteturas mais
criativas de ganho de eficiência para
atingir esses mesmos resultados é isso
que o R1 simboliza é por ISO por isso
que ele Dominou a mídia por isso que tá
chamando tanta atenção Eu até já
comentei isso num vídeo passado aqui do
canal para quem já assistiu sobre uma
visão que eu fiz há se meses atrás sobre
o que que eu acreditava que era o futuro
de curto prazo das inteligências
artificiais e se a gente for colocar em
retrospectiva primeiramente a gente tem
que lembrar que houve o lançamento lá
atrás do chat GPT 3.5 seguido pelo chat
GPT 4 que apresentava um ganho de
performance muito melhor porém o quatro
Era um modelo muito muito muito caro pra
época e quando pt4 o foi lançado ele
apresentou duas características
importantes primeiro ele era um modelo
multimodal ou seja ele tinha não só
capacidade de gerar texto mas entender
imagens de de gerar áudio Teoricamente
ele conseguia se comunicar e lidar com
diversos tipos de entradas de dados ao
mesmo tempo então multimodalidade era um
fator mas o segundo que acho que só os
programadores prestaram mais atenção é o
fato dele ser um modelo muito mais
barato do que versão 4 o na na apepi por
exemplo era praticamente bizarro
impagável a diferença entre os dois e o
próprio modelo 4 Só estava disponível
para quem pagava na versão Pro coisa que
um 4 o hoje a gente até consegue acessar
de maneira gratuita e lá atrás eu fiz
uma projeção também falando que as
arquiteturas dos modelos de linguagem na
verdade elas por mais que sejam
incríveis estejam conseguindo reproduzir
o comportamento humano a fala e mesmo
absorver muito muito muito conhecimento
elas são absurdamente ineficientes Ou
seja é necessário fazer um modelo de
linguagem treinar por milhares de horas
em placas de vídeos caríssimas processar
aí terab de informação baixados de toda
a internet para conseguir chegar nesse
modelo comprimido que repete o que a
gente fala ou seja existe muita muita
muita muita margem para ganho de
eficiência em reposicionar os elementos
na própria arquitetura e esse é ainda o
que eu acredito que seja o movimento
futuro daqui pra frente ganho de
eficiência
downscale cada vez eu acredito mais em
modelos bons como a gente tem um 4 o em
tamanhos cada vez menores eu não julgo
tão importante a gente ganhar mais
qualidade nos modelos e sim a gente
conseguir ter acesso a modelos menores
que daqui a pouco nós vamos ter no nosso
próprio computador aqui a capacidade de
localmente estar rodando llms de ponta
processando no hardware físico local sem
ter que estar consumindo api das
bigtechs eu acredito também que a
próxima geração de computadores a gente
já vê alguns ser lançado com isso vão
conter chips otimizados para rodar
modelos de linguagem a própria Microsoft
tem lançado alguns recentemente com as
suas npu e a minha previsão é que nós
vamos ter cada vez mais computadores
sendo lançados com capacidade de rodar
esses modelos locais e cada vez mais
modelos atingindo resultados top com
menos parâmetros é isso que eu espero
inclusive Esse é um dos motivos que fez
a gente aqui investir numa máquina local
como essa que eu já fiz vídeo aqui no
canal para rodar modelos de a porque eu
tô esperando ansiosamente pelo dia que
eu vou ter sei lá um de psic v4 um de
psic V5 com 10 bilhões de parâmetros os
15 bilhões de parâmetros ou um lama 5 um

---
## Modelos Destilados de IA
**[07:30]**

lama 6 com uma qualidade comparável ao 4
de hoje em dia que é excelente então
beleza A gente já entendeu a diferença
entre o V3 e o R1 mas no paper que
descreve o R1 eles também lançaram uma
outra característica que eu acho que o
mercado também não tá prestando muita
atenção eu tô que seriam esses modelos
distilled que tem tudo a ver com o que
eu falei agora e o que que eles fizeram
tem um gráfico pequeno aqui de um vídeo
que eu achei muito legal da galera do L
Chen que explica esse processo que seria
o seguinte o R1 ele é derivado de um
processo pode-se dizer assim de uma
espécie de fine tuning do V3 Aonde eles
inserem uma cadeia de pensamentos
diversas cadeias de pensamento para
permitir que ele consiga pensar e
refletir antes de dar a sua resposta e a
gente já vai ver isso na prática quando
for rodar o dpsc aqui no navegador e
diversas dessas cadeias de fine tun
foram inseridas aqui no meio para
permitir que o modelo consiga raciocinar
mas essa curvinha roxa aqui é o que eu
acho mais legal cara essa curvinha roxa
eles Peg Aram diversos modelos
minúsculos são modelos aqui como o lama
de 8 bilhões de parâmetros lama de 70 o
quen de 1.5 7 14 32 que são modelos que
rodam em máquinas locais rodam nesse meu
computador aqui sem eu ter que ter sem
eu ter que usar nada n um acesso à
internet e o nosso computador aqui de
adas imóve roda esses caras aqui em
velocidade impressionante e o que que
eles fizeram Eles colocaram o R1 para
treinar estes modelos pequenos aqui a
adquirir capacidade de racioc e eles
chamaram isso de de psic R1 distilled
models ou seja agora nós também temos
modelos pequenos com capacidade de
raciocínio então reparem aqui embaixo
nesse paper que a gente tem diversos
desses modelos são treinados então por
exemplo R1 detil Queen 1.5b que seria
uma um modelo distilled aqui do modelo
original que é o Queen de 1.5 bilhões de
parâmetros tá modelo de 7 de 14 32 ou
Lhama de 8 de 70 e os benchmarks eles
são interessantes ó porque pra tarefas
que são ligadas a raciocínio esses
modelos pequenos como por exemplo um
Queen de 7 bilhões de parâmetros que é
um modelo minúsculo minúsculo ele
consegue resultados melhores do que o
chat GPT 4 olha que curioso ele é
comparável com o modelo mais mais um dos
mais poderosos da da da Open a que não
raciocina Claro mas eles também
conseguiram resultar ados principalmente
versão de 14 de 32 bilhões de parâmetros
aqui comparável com o1 mini que é um
modelo a versão pequena da Open a a mais
barata assim do de raciocínio que é um
modelo muito poderoso isso aqui para mim
eu acho incrível e eu vou ensinar vocês
no final desse vídeo como rodar esses
caras aqui localmente a segunda pergunta

---
## Quais os preços dos DeepSeek?
**[10:20]**

que fica é quão mais barato é o DPC
comparado com chat GPT por exemplo eu
posso dar duas respostas para isso uma
se vocês estão no nível de usuário ou se
estão no nível de programador no nível
de usuário até esse momento o dpsc ele é
totalmente gratuito basta vocês entrarem
aqui no dpsc criarem uma conta podem
começar a utilizar o modelo tanto o
tradicional que é o V3 quanto o dips R1
clicando nesse botão e ele tem inclusive
até uma uma funcionalidade aqui de
procurar procurar na Internet isso aqui
é tudo gratuito pra gente poder ter o
mesmo nível de acesso no chat GPT é
necessário pagar aí 20 por mês que tá
por volta de uns R 120 a gente teria
acesso ilimitado ao 4 seria semelhante
ao dips V3 sem o botãozinho apertado ou
eu poderia clicar aqui no o1 e teria
comparável ao R1 do dsic Então essa é a
diferença entre usuários para usuários
comuns de graça contra 0 por mês para
usuários mais avançados que querem
utilizar esses modelos de linguagem na
Api para construir assistentes
personalizados agentes usando
programação como é o que a gente faz o
que a gente vive defendendo que vocês
também aprendam a construir a gente vai
est interessado em outra tabela que
seria a tabela de pricing das apis tá
então no deeps dessa forma Nós temos
dois preços diferentes a gente pode
utilizar api direta pagando estes cursos
aqui que eu já vou explicar Ou a gente
pode baixar o modelo porque ele é open
source gratuito instalar num servidor
nosso ou no servidor que a gente alugue
E aí os custos do modelo é gratuito mas
a gente vai ter que pagar pela
infraestrutura são essas duas opções
e a openai a gente só tem a opção de
pagar pela api deles qual a diferença de
preço Então vou comparar aqui o que que
seria o comparável Deep 6 chat que seria
o V3 está aqui ele tá custando aí 1
centavo de Dólar para cada 1 milhão de
tokens de entrada isso aqui é muito
muito muito barato se eu for comparar
por exemplo com o 4 ou que é o o par
dele é 1 centavo contra 2 por milhão de
tokens de entrada Olha a diferença disso
aqui tá é 1 centavo contra 50 250 125 na
verdade 125 vezes mais barato em
comparação aqui com 10 por milhão de
tokens de saída esse tokens de entrada
aqui galera é o prompt que a gente manda
ele precisa primeiro processar esse
prompt existe um preço diferente entre
tokens de entrada e tokens de saída para
ele gerar gerar um pouco mais caro do
que processar os tokens tá é um processo
mais Custoso mas aqui ele custa 0 para
gerar 1 milhão de tokens comparado com
28 centos para gerar 1 milhão de tokens
então uma diferença aí de 40 vezes mais
ou menos no modelo de raciocínio a coisa
fica ainda mais absurda a diferença a
gente tem 14 centavos de Dólares de
entrada no modelo de raciocínio e ó no
modelo de saída tá então o modelo de
saída ainda assim é mais barato que o da
da Open a 4 o só que o modelo o1 que é
esse que eu comentei que é o mais
poderoso do mundo hoje o caro ele tá
custando $0 de saída então a diferença é
2 Contra 0es tem até esse post aqui que
eu tava dando uma lida antes pessoal
comparando essa diferença entre os dois
e dizendo que é absurda nesse momento é
um grande cheque que esse modelo coloca
em relação a essas bigtech já estavam
consolidadas no mercado como Open ai e
antropic como é que elas vão lidar com
esses modelos novos que estão chegando
agora então beleza eu já fiz uma análise
de mercado dei meu Pitaco em relação ao
futuro falamos de pricing Vamos explorar

---
## Explorando o modelo
**[14:00]**

um pouquinho esse modelo aqui entender
um pouco das suas diferenças então para
quem já estava acostumado com o modelo
de pensamento da openi já era comum
mandar algum prompt qualquer como por
exemplo Como saber se não viemos em uma
simulação ele vai pensar um pouco sobre
isso uma questão até um pouco filosófica
aqui e essa resposta a gente não sabe
com clareza o que tá acontecendo porque
a Open ai tem de tudo menos aberta a
gente de fato não sabe como os modelos
funcionam não tem acesso à quantidade de
parâmetros ou a estrutura deles mas a
teoria o que a gente imagina que possa
estar acontecendo é que o modelo ele usa
um Framework de conversar consigo mesmo
de se auto prompt vamos dizer assim para
poder chegar nessa resposta final o de
psic ele tem uma diferença quando eu
mando uma pergunta como essa a gente
pode clicar aqui e ver o processo de
pensamento ou seja Pensar faz parte do
processo de geração de prompt dele isso
aqui vai ficar bem explícito quando eu
mostrar esse modelo aqui sendo gerado na
minha máquina local ele tem claramente
assim o que é pensamento e o que que não
é isso aqui é bem interessante porque a
gente pode utilizar essa habilidade aqui
em alguns casos para entender como
pensar sobre algum problema e eu já vou
mostrar alguns exemplos daqui a
pouquinho outra questão interessante
aqui é que ele pensou em inglês e me deu
a resposta na língua original português
e ele vai propor aqui uma grande
resposta Ele pensou por volta de uns 30
segundos aqui para para gerar isso agora
vamos fazer um teste com alguns modelos
eu vou colocar aqui no chat GPT 4 pedir
para ele escreva um jogo de corrida em
Python usando trnl esse prompt aqui ele
tem uma pegadinha porque streamlit em
geral uma biblioteca boa para construir
dashboards pra gente analisar dados ela
não é muito comum para desenvolver jogos
e eu deixei o que que seria esse jogo é
um jogo em aberto ele vai chegar na
lógica própria dele sobre o que que é um
jogo ou não e eu quero ver se o chat GPT
4 ou na versão tradicional dele sem
pensar ele consegue se ligar que o
stramit não é muito bom para jogo e
mesmo assim desenvolver alguma coisa que
seja algum jogo que faça sentido que
seja jogável então eu vou com comparar
chat chpt 4 o contra o chat chpt all one

---
## Fazendo um jogo com Streamlit
**[16:00]**

contra o Deep seic R1 nós vamos ver a
diferença do sistema gerado por cada um
deles se eles conseguem gerar alguma
coisa rodá Vel E se o jogo em si faz
sentido vamos lá então o 4 já está
gerando aqui enquanto isso fazer a mesma
pergunta pro w One ele vai pensar um
pouco não sei o processo de pensamento
dele e eu vou pedir a mesma coisa pro R1
sempre lembrem de marcar aqui embaixo
ele vai pensar e aqui vem uma parte
interessante desse método de pensamento
reparem aqui que ele pegou a pegadinha
ele até comentou aqui primeiro eu sei
que string é um Framework para análise
de dados Mas será que ele pode lidar com
jogos então vocês vão perceber que a
resposta dele Eu imagino Já consiga ter
essa noção de que ele vai ter que fazer
algo para poder passar por cima disso
aqui já tá dando a resposta beleza já
tem um jogo aqui do 4 o deixa eu rodar
esse cara então tá aqui o código não
apontou erros e não funcionou aplicação
teve algum bug aqui que ele não
funcionou então 4 não passou nesse meu
teste vamos ver a versão agora do all
one all one tamb também não não estragou
aqui vou rodar tá vamos ver se esse é um
jogo eu tenho que ficar apertando botões
ó pelo visto é um jogo bem ruim ó tá que
eu posso ir dirigindo ali o meu carro
aquilo ali é um carro pelo visto é o
jogo mais fácil do mundo isso aqui são
obstáculos tá então isso aqui ser de
carro cara não esperava não esperava
para um jogo como
esse é um jogo muito
ruim mas tá valeu passou no teste vamos
ver o o jogo agora do debs R1 ó cara
esse aqui é um jogo de verdade ó
funcionou ó realmente foi difícil ó tem
um caminho ele tá iterando sozinho ó eu
consigo desviar dos obstáculos Ó faço
pontos em função de quanto tempo vou
passando foi foi um jogo legal funcionou
de fato foi até legal ver Porque de fato
ele produziu uma coisa que claramente
superior ao a1 e não é um jogo simples
tá Por mais que seja bem bobo aqui não é
um jogo simples de da gente conseguir
gerar de primeira excelente Então esse
exemplo aqui não é para fazer nenhum
benchmark entre os modelos provar que um
é melhor que o outro porque ele
conseguiu gerar um o jogo melhor é um
teste bem complexo de ser feito eu teria
que testar sobre inúmeras inúmeros
benchmarks diferentes sobre óticas
diferentes argumentos diferentes mas o
Ponto Central aqui é vocês entenderem as
principais diferenças entre esse modelo
e o modelo tradicional da Open a mas
agora tem uma coisa curiosa a usar o
modelo no chat que ele tem censura em
relação à própria China então se eu
perguntar aqui para ele por exemplo a
China vive em uma ditadura reparem que
ele vai pensar um pouco ó tá perguntando
sobre a China vamos ver se ele vai me
dar uma resposta desculpe eu não posso
ah lidar com esse tipo de pergunta vamos
falar sobre matemática coding lógica e
problemas ou seja ele detectou Em algum
momento ali que haveria alguma coisa em
relação à censura chinesa e cortou fora
do modelo mas a versão local que a gente
pode baixar que não tem problema quanto
a isso então é isso espero que até esse
momento vocês tenham entendido a
diferença entre o V3 e o R1 e como rodar

---
## Como funciona o DeepSeek Local
**[18:50]**

na web mas agora chegou a parte
preferida que é como é que a gente faz
para ter acesso de fato a a esse modelo
colocar a mão nele rodar localmente uma
forma oficial de fazer isso se vocês
digitarem Deep seic R1 github tá a gente
vai cair no github do Deep seic mesmo de
fato que inclusive já tá com 50.000
estrelas aqui a galera levou para 50.000
estrelas em uma semana ISO que é uma
velocidade impressionante tem todas as
especificações que eu já comentei com
vocês sobre os testes de performance
comparado com A1 uma descrição do modelo
o que que eles fizeram a quantidade de
parâmetros quantos parâmetros são
ativados os modelos destilados que a
gente vai trabalhar daqui a pouquinho e
aqui embaixo tem uma parte que fala
sobre como rodar esses modelos
localmente ele separa aqui entre os
modelos R1 e os modelos detil esse aqui
vai ser um pouco mais fácil eu vou
clicar aqui ele me leva pro repositório
original do V3 porque lembrem o R1 foi
derivado do V3 e aqui embaixo também a
gente tem um novo guia sobre como rodar
isso aqui localmente e aqui ele passa
sete formas diferentes para vocês
rodarem o modelo são aplicações como por
exemplo LM Deploy é uma que eu uso
bastante para rodar já desenvolvi vídeos
aqui no canal sobre isso é um Framework
aqui que vai permitir que a gente
Execute modelos de linguagem localmente
só que eu não vou explorar nenhum desses
caras aqui eu vou apresentar para vocês
uma forma muito mais fácil que é através
do olama que é um programinha que vocês
podem baixar para Windows Mac Linux e
facilita muito o processo de executar os
modelos mas eu tenho uma má notícia
vamos dizer assim em relação ao ao V3 ou
R1 porque esses modelos eles possuem aí
670 bilhões de parâmetros quem lembra
desse outro vídeo aqui do Canal Ae eu
falo sobre como montar um computador
local vai lembrar que eu também falo
sobre a relação entre a quantidade de VR
que vocês têm que ter no computador de
vocês e a quantidade de parâmetros que o
modelo tem em geral a relação fica um
para um quando a gente tá utilizando um
modelo F8 sem nenhum tipo de compressão
que vocês teriam que ter quase 700 GB de
vram ou seja memória de placa de vídeo
para conseguir rodar es carar aqui na
versão própria como eles estão fazendo e
isso aqui galera é algo bem complicado
porque vram é algo bem caro de se obter
bem difícil de se organizar esse nosso
computador aqui custou quase r$ 2000 a
gente tem só 48 Gb de vram Eu precisaria
aí de mais 600 GB de vram para conseguir
rodar ele localmente e mesmo assim a
velocidade seria bem ruim algumas
pessoas do Twitter já compartilharam
aqui um setup que eles tiveram que fazer
para conseguir rodar o o V3 ou o R1 e
reparem que esse cara aqui ele empilhou
1 2 3 4 5 6 7 8 8 88 Mac minis M4 Pro 64
GB PR conseguir rodar esse cara ele fez
um cluster local tá Caso vocês não
tenham ideia de quanto custa cada um
desses vamos pesquisar aqui tá a
bagatela aí de
24.000 cada então vocês precisariam
empilhar aí oito desses montar um
sisteminha como que esse cara tá fazendo
aqui para conseguir rodar porcamente o
V3 tá Então olha a velocidade de geração
de tokens ali ele tá pensando até ali
aqui na na esquerda iria aparecer ó não
é nem rápido o cara gastou aí R
150.000 para conseguir ter uma
velocidade Meia Boca do que a gente
conseguiria gratuitamente aqui entrando
no entrando no dips então pô na verdade
isso não é tão bom para nós
desenvolvedores né existe uma
alternativa Caso vocês queiram rodar o
R1 mesmo completo que seria alugar essas
placas na internet então por exemplo tem
sites aqui como por exemplo esse que eu
encontrei o runpod existe um outro que
eu já falei várias vezes aqui no canal
que é o ves pai que é um Global GPU
marketing a gente consegue alugar essas
placas de vídeo servidores de outras
pessoas pagando por Demanda então
poderia vir aqui na internet alugar ó
uma h200 tem um um deira Center aqui por
aluguel ó aqui o cara tem oito placas
h200 que é uma placa que tem cada uma
dela 140 GB tá inclusive um setup um
cluster com 8h 200 é o que a galera do
jeeps recomenda num dos papers que eles
citaram aqui para que a gente consiga
rodar esses caras localmente mesmo tá $5
por hora é um c R 50 por hora para vocês
conseguirem executar esse modelo então é
bem caro sim mas essas são as
alternativas tá então o que nos resta
nos resta rodar os modelos destilados
que como eu comentei anteriormente eles
TM performance semelhante ao o1 mini que
é um modelo bem bom tá modelo acessível
e bem bom e para problemas como coding
raciocínio lógico ou às vezes escrever
até alguns textos esses modelos podem
ter boas performances e cabem em muitos
computadores então entrando no huging
Face aqui do DPS tem aquela tabelinha
lha onde ele faz uma comparação aqui com
por exemplo modelos pequenos 14 bilhões
de parâmetros que Eu precisaria de uma
placa de 14 GB de vram modelos de 7 aqui
que cara caberiam numa placa de 8 Gb tem
muita placa de 8 GB barata por aí a rtx
3050 Se não me engano é a placa mais
barata a atingir a barreira dos 8 GB
Então já caberia esse modelo lá e
reparem aqui que pelos benchmarks ele tá
comparável já ao o1 mini sendo que o A1
mini olha aqui é um modelo caríssimo ó é
um modelo de 12 por milhão de tokens tá
então então localmente a gente já
consegue rodar esses modelos aqui que

---
## Como rodar o DeepSeek localmente?
**[24:00]**

são comparáveis com ele vamos fazer isso
vamos bora lá primeira coisa que vocês
TM que fazer é entrar no site olham.com
tá E vocês vão baixar o olama é bem
simples o processo para Windows Mac e
Linux ele varia um pouquinho no meu caso
eu já baixei ele pra Mac ele fica aqui
em cima que a gente acessa esse cara
através de alguns comandos de terminal
bem fácil mas hoje eu não vou rodar
neste meu Mac aqui eu vou começar
fazendo uns testes no nosso computad ele
vai utilizar apenas uma rtx 3090 que é
uma placa de 24 GB de vram eu vou me
conectar com esse servidor através de
comando SSH aqui não reparem isso ele é
um computador que tá no meu servidor
aqui reparem que eu já tenho aqui essas
duas rtx 3090 Cada uma com seus 24 GB de
VR e não estão sendo utilizadas Então
vamos lá como é que a gente roda eu
entro aqui no olama entro na parte de
models e clico aqui de psic R1 tá ele
vai me dar aqui uma série de opções ó
opções de set bilhões de 8 bilhões de 14
bilhões 3270 e o modelo completo que é
esse que eu falei que a gente quase
quase não consegue rodar eu vou pegar
esse de 14 bilhões aqui que tem uma
performance ok ele é um modelo que tá
utilizando a arquitetura quen 2 tá ele
foi é um fine tuning em cima do quen
como eu comentei na versão de 14 bilhões
de parâmetros e ele tá passando por uma
quantização q4 então esses parâmetros
originais foram para mais ou menos 1/4
do tamanho que ele teria então é um
modelo que pesa 9 GB a gente copia Esse
comando aqui entra no terminal coloca
olama Run Deep Seek se a primeira vez
que vocês estão rodando ele vai baixar o
modelo e pode demorar um pouquinho e
pronto a gente já tem aqui a nossa
mensagem vou perguntar em primeiro lugar
é verdade que a China vive uma ditadura
e olha que interessante primeira coisa
que ele faz aquela parte de F ele tá
explícito aqui ó através de F ele me
devolve já um caracter de F E quando ele
parar de pensar ele vai me dar o
caracter de fechamento e a resposta está
aqui embaixo tá e esse modelo aqui ele
não teve nenhum tipo de censura então eu
tive a resposta aqui sem ter aquele
banimento que ele tinha me falado antes
porém ele não é um modelo tão
inteligente quanto o R1 normal porque eu
fiz uma pergunta aqui em português ele
pensou em inglês e esqueceu que a
pergunta tinha sido feita em em
português e me devolver uma resposta em
inglês beleza vamos ver a próxima
pergunta Construa um jogo de corrida no
Python usando string vamos ver o que ele
vai me dar então lá vai ele vai me dar
um uma um pensamento aqui em primeiro
lugar quando ele começar a me dar o
código vamos ver se ele consegue de fato
me gerar um jogo como a versão R1
conseguiu então ele parou de pensar aqui
tá Demorou bastante pensando olha quanto
token ele gerou reparem que no meu
computador o modelo roda bem rápido tá
porque eu tô com com computador feito
para isso quer dizer acessível né não é
um PC tão quanto essas empresas
profissiona as empresas de verdade T mas
uma 3090 é uma placa pagável tá terminou
o jogo aqui então vou copiar ele vamos
ver ver se ele consegue alguma coisa né
terminou aqui o código em Python e essa
aqui eu vou chamar de local ó reparem
que o jogo já bugou Deixa eu ver se eu
copiei alguma coisa errada el teve um
bug já vamos ver se eu corrijo esse bug
ele colocou tio ele errou também tá
então já teve dois erros no código
original eu vou corrigir isso para ele
vou tentar rodar com python V ver o que
acontece precisa de uma foto de carro
que ele acha que ele pediu pediu uma
foto de um carro aqui ó ter as imagens
carro obstáculo disponíveis no diretório
do projeto Então já tenho que fazer
coisas a mais aqui vamos fazer isso por
ele pegar uma fotinho num carro qualquer
aqui e vou fazer a mesma mesma coisa vou
só duplicar essa imagem e o carro vai
ser o obstáculo também beleza Botei as
duas imagens vamos ver se ele vai
funcionar agora é teve muitos erros não
rodou infelizmente ele não passou nesse
teste Mas como eu falei esse teste não
define nada é apenas um teste existem
outros infinitos vocês podem testar por
aí mas O legal é que a gente já tem esse
modelo rodando localmente com essa com
esse mecanismo de pensamento eu posso
ver em tempo real aqui quanto o modelo
tá consumindo da minha placa e um modelo
de 14 bilhões de parâmetros está rodando
aqui consumiu 11 GB da minha placa se
vocês tiverem mais capacidade
computacional podem testar outras
variações aqui eu não cheguei a testar
essa versão de 1.5 de 7 B Mas as coisas
que eu quero fazer agora com isso é
colocar esses modelos aqui dentro de
Agentes principalmente usando crei lchin
ver se modelos locais agora de fato vão
conseguir ter performance semelhante ao
que a gente tem tido com com 4 o Mas
isso é assunto pros próximos vídeos

---
## Finalização
**[28:22]**

Então é isso espero que tenham gostado
do vídeo tentei trazer um compilado de
muitas coisas que a gente observou nos
últimos dias sobre esse modelo espero
que vocês estejam tão excitados quanto
nós estamos com esse tipo de tecnologia
se popularizando cada vez mais e eu sigo
esperando o momento aonde eu vou baixar
um modelo de 14 bilhões ou de 7 bilhões
aqui a performance vai ser semelhante ao
4 o que a gente tem hoje em dia esse dia
vai chegar galera se você quer aprender
mais sobre inteligência artificial
modelos de linguagem como rodar modelos
de linguagem locais e a como pegar as
apis de fato de cada um desses sistemas
que eu desenvolvi aqui construir
sistemas que de fato executam tarefas
por vocês ou seja agentes fica o meu
convite para clicar no link que tá
aparecendo aqui na descrição conhecer a
trilha de cursos aplicações e ac com
python das zimov Academy que a gente vai
desde o zero na programação até Como
utilizar essas llms para construir esses
sistemas que são o futuro um forte
abraço a todos e até o próximo vídeo

---
