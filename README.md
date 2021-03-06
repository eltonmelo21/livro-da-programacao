## Nota do tradutor

<i>Esta é uma tradução livre de <b><a href="http://eloquentjavascript.net/1st_edition/chapter6.html">The Book of Programming</a></b>,<br/>
que apareceu na primeira edição do <b><a href="http://eloquentjavascript.net">Eloquent JavaScript</a></b>.

Na verdade, não é bem um livro: trata-se de um bem humorado<br/>
"texto zen apócrifo", atribuído ao fictício mestre Fu-tzu.

Se você quiser conhecer as verdadeiras obras clássicas,<br/>
como o <b>Wu-wen kuan</b> e o <b>Hsin-hsin Ming</b>,<br/>
consulte este <b><a href="http://www.sacred-texts.com/bud/zen/">outro site</a></b>.</i>

<hr/>

# O Livro da Programação

## Os Dois Aspectos

Abaixo da superfície da máquina, o programa se move.<br/>
Sem esforço, ele se expande e se contrai.<br/>
Em grande harmonia, os elétrons se dispersam e se reagrupam.<br/>
As formas sobre o monitor são apenas ondulações sobre a água.<br/>
A essência permanece invisivelmente abaixo.

Quando os criadores construíram a máquina,<br/>
eles colocaram o processador e a memória.<br/>
Destes surgem os dois aspectos do programa.

O aspecto do processador é a substância ativa. É chamado de <i>controle</i>.<br/>
O aspecto da memória é a substância passiva. É chamado de <i>dados</i>.

Os dados são feitos apenas de bits, mas assumem formas complexas.<br/>
O controle consiste apenas de instruções simples, mas realiza tarefas difíceis.<br/>
Do pequeno e trivial, surge o grande e complexo.

A fonte do programa são os dados. O controle surge disso.<br/>
O controle passa a criar dados novos.<br/>
Um nasce do outro, o outro é inútil sem o um.<br/>
Este é o ciclo harmonioso dos dados e do controle.

Por si mesmos, os dados e o controle não têm estrutura.<br/>
Os programadores do passado moldaram seus programas a partir desta substância bruta.<br/>
Ao longo do tempo, os dados amorfos cristalizaram-se em tipos de dados<br/>
e o controle caótico foi restrito ao controle de estruturas e funções.<hr/>

## Ditados Curtos

Quando um aluno perguntou a Fu-Tzu sobre a natureza do ciclo dos dados e do controle, Fu-Tzu respondeu:<br/>
"Pense em um compilador, compilando a si mesmo".

Um aluno perguntou: "Os programadores do passado usavam apenas máquinas simples e sem linguagens de programação, mas eles criaram  programas bonitos. Por que usamos máquinas complicadas e linguagens de programação?"<br/>
Fu-Tzu respondeu: "Os construtores do passado usavam apenas gravetos e argila, mas eles construíram cabanas bonitas."

Um eremita passou dez anos escrevendo um programa.<br/>
"O meu programa pode computar o movimento das estrelas em um computador 286 com MS-DOS", anunciou orgulhosamente.<br/>
"Ninguém mais tem um computador 286 nem usa MS-DOS", respondeu Fu-Tzu.

Fu-Tzu escreveu um programinha cheio de <i>global state</i> e atalhos duvidosos. Ao lê-lo, um aluno perguntou:<br/>
"Você nos advertiu contra usar estas técnicas, mas eu as encontro no seu programa. Como pode isso?"<br/>
Fu-Tzu disse: "Não há necessidade de procurar uma mangueira d'água quando a casa não está em chamas."<br/>
<i>(Isso não deve ser lido como um encorajamento à programação desleixada, mas como uma advertência contra a adesão neurótica a regras de ouro.)</i><hr/>

## Sabedoria

Um aluno estava reclamando a respeito dos números digitais.</br>
"Quanto eu tiro a raiz de dois e então a elevo ao quadrado de novo, o resultado já fica impreciso!"<br/>
Ao ouvi-lo, Fu-Tzu riu. "Aqui está uma folha de papel. Escreva para mim o valor preciso da raiz quadrada de dois."

Fu-Tzu disse: "Quando você corta contra a fibra da madeira, muita força é necessária.<br/>
Quando você programa contra a fibra de um problema, muito código é necessário."

Tzu-li e Tzu-ssu estavam se gabando sobre o tamanho dos seus últimos programas.<br/>
"Duzentas mil linhas", disse Tzu-li, "sem contar os comentários!"<br/>
"Capaz", disse Tzu-ssu, "o meu já tem quase <i>um milhão</i> de linhas."<br/>
Fu-Tzu disse: "O meu melhor programa tem quinhentas linhas".<br/>
Ao ouvir isso, Tzu-li e Tzu-ssu foram iluminados.

Um aluno estava sentado imóvel atrás de seu computador por horas, franzindo sombriamente a testa.<br/>
Ele estava tentando escrever uma solução bonita para um problema difícil, mas não conseguiu encontrar a abordagem correta.<br/>
Fu-Tzu bateu atrás da cabeça dele e gritou: "Digite algo!"<br/>
O aluno começou a escrever uma solução feia.<br/>
Depois de terminar, ele subitamente compreendeu a solução bonita.<hr/>

## Progressão

Um programador principiante escreve seus programas do modo como uma formiga constrói a sua colina,<br/>
uma peça de cada vez, sem pensar na estrutura maior.<br/>
Seus programas serão como a areia fofa.<br/>
Eles podem ficar de pé por um tempo, mas crescendo demais, eles desmoronarão.<br/>
<i>(Referindo-se ao perigo da inconsistência interna e da estrutura duplicada em um código desorganizado.)</i>

Percebendo esse problema, o programador começará a gastar muito tempo pensando na estrutura.<br/>
Seus programas serão estruturados rigidamente, como esculturas na rocha.<br/>
Eles são sólidos, mas quando precisarem mudar, violência precisa ser aplicada a eles.<br/>
<i>(Referindo-se ao fato de que a estrutura tende a colocar restrições na evolução de um programa.)</i>

O mestre programador sabe quando aplicar a estrutura e quando deixar as coisas na sua forma simples.<br/>
Seus programas são como a argila, sólidos porém maleáveis.<hr/>

## Linguagem

Quando uma linguagem de programação é criada, lhe é dada a sintaxe e a semântica.<br/>
A sintaxe descreve a forma do programa, a semântica descreva a função.<br/>
Quando a sintaxe é bonita e a semântica é clara, o programa será como uma árvore majestosa.<br/>
Quando a sintaxe é desajeitada e a semântica confusa, o programa será como um arbusto espinhento.

A Tzu-ssu foi pedido que escrevesse um programa em uma linguagem chamada Java, que tem uma abordagem muito primitiva com as funções.<br/>
Todas as manhãs, quando se sentava na frente do seu computador, ele começava a reclamar.<br/>
Ele xingava o dia inteiro, culpando a linguagem por tudo o que ele fazia de errado.<br/>
Fu-Tzu escutou por um tempo e então o censurou, dizendo: "Toda linguagem tem o seu próprio caminho.<br/>
Siga a forma dela, não tente programar como se você estivesse usando uma outra linguagem."
