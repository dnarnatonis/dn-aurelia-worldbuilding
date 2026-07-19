---
title: "Chronicle System — Cap. 10: Guerra"
category: "Chronicle System"
tags: [reference, rules, chronicle-system, warfare, units, orders, siege, formation]
related_concepts: [unit, commander, discipline, order, siege weapon, formation, glory]
source: "Sword Chronicle (Green Ronin, 2020), Cap. 10, pp. 151–169"
---

# Cap. 10 — Guerra

As regras de guerra são uma extensão natural do sistema de combate ([[09-combate]]), permitindo ao Narrador mudar a perspectiva dos personagens e suas lutas individuais para os movimentos e heroísmos de exércitos inteiros — **sem que o jogo degenere num wargame**.

## Escala

Batalhas envolvem **unidades** de **100 soldados** cada. Quando o jogo "aproxima o zoom" nos PCs, eles não enfrentam unidades inteiras, mas **esquadrões** de 10 homens.

> **Combates com 20 combatentes ou menos: use as regras normais de combate.** Para engajamentos maiores, use o modo apresentado aqui.

- Cada espaço equivale a **10 jardas quadradas** — área que comporta facilmente 100 soldados a pé, ou cerca de **20 cavalos e cavaleiros**
- **1 battle round = 10 combat rounds = um minuto**

## Comandantes

Sem um líder claro, um exército corre risco de colapso ou debandada. **Geralmente o personagem de maior Status é o comandante.**

- Um comandante emite **ordens iguais ao seu rank de Warfare**
- **Subcomandantes** — oficiais, ajudantes, conselheiros — emitem **uma ordem cada**
- Pode-se ter **um subcomandante para cada duas unidades completas** do exército

> Comandante com Warfare 4 e dois subcomandantes: **6 ordens por battle round**.

### Emitindo ordens

Toda ordem exige um **teste de Warfare** contra a **Discipline** da unidade, mais modificadores conforme a ordem.

- **Sucesso** — a unidade executa a ordem
- **Falha** — a unidade não recebe ou se recusa a executar. **Mas se já foi comandada, seguirá as standing orders**
- **Critical failure** — a unidade **não age e não segue as standing orders**

> **Cada nova ordem além da primeira dada a uma mesma unidade no mesmo battle round soma +3 à Difficulty.** Standing orders vigentes de rounds anteriores não somam. Portanto, se precisar dar múltiplas ordens a uma unidade, **dê as mais importantes primeiro**.

### Ativando unidades

Ao receber com sucesso sua primeira ordem, a unidade fica **ativada**. **Até ser ativada, ela não age.** Uma vez ativada, ela **segue a primeira instrução a cada battle round** até cumprir o objetivo, quebrar, ou receber nova ordem.

### Sem comandantes

Quando uma força perde a estrutura de comando, ela **se desintegra rapidamente**: cada unidade cai para **Disorganized** e segue a última ordem recebida. Dali em diante, **toda a força tem apenas uma ordem por round** até que cada unidade esteja Routed ou Destroyed.

> Qualquer personagem que se una ao exército e tenha ao menos **Status 2** pode assumir o comando.

## Heróis

Indivíduos notáveis que influenciam a batalha pela mera presença. Podem reagrupar tropas, liderar cargas ou atacar unidades. **Diferem de comandantes por terem mais liberdade e agirem independentemente de uma unidade.**

- **Heróis não somam ordens ao comandante**
- Um exército pode ter **um herói por rank de Status do comandante** — preenchidos primeiro por PCs, depois por NCs importantes
- Agem durante os **passos de ação dos jogadores**, mas podem se **acoplar** a unidades para melhorá-las

## Vitória e derrota

As consequências vão além das vidas perdidas. Uma derrota desastrosa pode aleijar uma casa:

- O saque de um castelo ou vila faz perder os recursos investidos naquele holding
- Inimigos ocupando suas terras reduzem seus domínios e os recursos neles investidos
- Um exército que marcha pelos seus campos queimando colheitas e assassinando camponeses custa **Population e Wealth**

> Cada batalha que você trava, se precisar travá-la, **põe em risco tudo o que lhe é caro**.

---

## Componentes das unidades

### Abilities

As abilities de uma unidade são **independentes** dos lutadores que a compõem: refletem sua eficácia como **força coletiva** — treino, trabalho em equipe e disciplina.

Toda unidade começa com **rank 2** em cada ability. O **tipo** define quais podem ser melhoradas; o **training** define quanto ([[05-casa-e-terras]]).

```
Defense  = Agility + Athletics + Awareness
Health   = Endurance × 3
Movement = 40 jardas (sprint = 4×; −10 jardas por ponto de Bulk)
```

### Equipando unidades

No campo, os tipos específicos de arma e armadura são desnecessários — presume-se variedade. Se a unidade tem dois ou mais tipos, **escolha o pacote preferido** entre os tipos listados.

**Ataques de Marksmanship:** armas **Close Range** alcançam **20 jardas**; **Long Range**, **200 jardas**.

#### Equipamento inicial

| Tipo | AR | AP | Bulk | Dano de Fighting | Dano de Marksmanship |
|------|----|----|------|------------------|----------------------|
| Archers | 2 | −1 | 0 | Athletics −1 | Agility +2; Long Range |
| Cavalry | 5 | −3 | 2 | Athletics +3 | — |
| Criminals | 1 | 0 | 0 | Athletics +1 | — |
| Engineers | 2 | −1 | 0 | Athletics −1 | — |
| Garrison | 3 | −2 | 0 | Athletics +1 | — |
| Guerillas | 1 | 0 | 0 | Athletics | Agility +1; Close Range |
| Infantry | 3 | −2 | 0 | Athletics +1 | — |
| Mercenaries | 4 | −2 | 1 | Athletics +1 | — |
| Peasant Levies | 0 | 0 | 0 | Athletics −1 | Athletics −1; Close Range |
| Personal Guards | 6 | −3 | 2 | Athletics +1 | — |
| Raiders | 2 | −1 | 0 | Athletics +1 | — |
| Sailors | 0 | 0 | 0 | Athletics +1 | — |
| Scouts | 2 | −1 | 0 | Athletics | Agility; Long Range |
| Special | 2 | −1 | 0 | Athletics | Agility; Close ou Long Range |
| Support | 0 | 0 | 0 | Athletics −1 | — |
| Warships | 5 | — | — | Athletics +1 | Agility +1; Long Range |

#### Upgrades de equipamento

Gastando **permanentemente** pontos do recurso **Wealth**, cada ponto aumenta o **AR**, o **dano de Fighting** ou o **dano de Marksmanship** da unidade. **Cada componente só pode ser melhorado uma vez.**

| Tipo | AR | AP | Bulk | Dano de Fighting | Dano de Marksmanship |
|------|----|----|------|------------------|----------------------|
| Archers | 3 | −2 | 0 | Athletics | Agility +3; Long Range |
| Cavalry | 9 | −5 | 3 | Animal Handling +5 | — |
| Criminals | 4 | −2 | 1 | Athletics +2 | — |
| Engineers | 5 | −3 | 2 | Athletics | — |
| Garrison | 5 | −3 | 2 | Athletics +2 | — |
| Guerillas | 3 | −2 | 0 | Athletics +1 | Agility +2; Close Range |
| Infantry | 4 | −2 | 1 | Athletics +2 | — |
| Mercenaries | 5 | −3 | 2 | Athletics +3 | — |
| Peasant Levies | 2 | −1 | 0 | Athletics | Athletics; Close Range |
| Personal Guards | 10 | −6 | 3 | Athletics +2 | — |
| Raiders | 5 | −2 | 2 | Athletics +2 | — |
| Sailors | 2 | −1 | 0 | Athletics +2 | — |
| Scouts | 3 | −2 | 0 | Athletics +1 | Agility +1; Long Range |
| Special | 6 | −3 | 2 | Athletics +1 | Agility +1; Close ou Long Range |
| Support | 2 | −1 | 0 | Athletics | — |
| Warships | 10 | — | — | Athletics +4 | Agility +3; Long Range |

### Equipamento especial

Exige gasto **permanente** do recurso indicado.

**Boiling Oil / Water** — *½ Wealth por uso*
Lançados de catapulta ou despejados das muralhas.
- **Água fervente:** 5 de dano, **ignorando AR**
- **Óleo fervente:** 10 de dano, ignorando AR. Se a unidade atingida sofrer um **ataque de fogo no mesmo round**, as chamas causam **+1 de dano por round durante 1d6 battle rounds**. Unidades em debandada por esse ataque arriscam **espalhar o fogo**: a cada vez que passam por outra unidade, há **1 chance em 6** de propagação, causando 1 de dano

**Mantlets** — *1 Wealth por uso*
Escudo pesado e reforçado montado num chassi com rodas. **−10 jardas de Movement**, mas **+5 de Defense contra ataques de Marksmanship**.

**Ram, Battering** — *1 Land*
Tronco derrubado, desgalhado e encimado por uma cabeça de aço ou ferro. Pode equipar **uma unidade não-cavalaria e não-navio**. Enquanto equipada, **a unidade não pode atacar**, mas ganha **+2D** em testes de Athletics para arrombar portas e portões. **Conta como Destroyed se a unidade que o carrega for Routed ou Destroyed.**

**Ram, Covered** — *2 Land*
Aríete instalado num chassi com rodas, coberto por uma copa que protege a equipe. Exige **uma unidade de engenheiros mais outra** não-cavalaria, não-navio. Deve ser rolado até a posição (movimento de 10 jardas).
- **Athletics 8** para arrombar portas e portões
- **20 Health, AR 8**
- Unidades operando-o ganham **+5 de Defense**
- Reduzido a 0 Health, é **Destroyed**

**Scaling Ladders, Ropes, and Grapples** — *½ Wealth por unidade armada*
Enquanto equipada, **a unidade não pode atacar**. Em posição, todas as unidades escalando ganham **+1D** em Athletics.
> Uma unidade defensora pode receber ordem de **limpar as escadas** — cada ordem anula o equipamento de escalada de uma unidade, mas quem executa sofre **−5 de Defense contra Marksmanship**.

**Sage's Fire** — *5 Wealth por unidade armada* · **Restrito**
Na maioria dos casos é segredo de Estado ou controlado por alquimistas que não partilham seus segredos — análogo ao Fogo Grego histórico, cuja receita verdadeira se perdeu por ter sido igualmente bem guardada.

Fluido espesso e nocivo. O fogo antigo é ainda pior que o recém-fabricado: sabe-se que ignita ao menor distúrbio. **Só se apaga sufocando-o completamente.** Flutua na água, criando poças de chama — daí ser arma popular em engajamentos navais. **Gruda na carne enquanto queima.**

- **+3 à Difficulty** de qualquer ordem à unidade portadora
- **Nenhum outro ataque é possível** até usá-lo
- Uma unidade armada que sofre dano tem **1 chance em 6** de que ele erupte, afetando-a
- Ordenado o ataque, a unidade faz um teste de **Marksmanship**. **Falha** faz o fogo atingir um espaço adjacente de 10 jardas; **Critical failure** faz o fogo afetar a própria unidade
- Num acerto: **7 de dano** (ignorando armadura, com dano extra por grau) no primeiro round **e a cada round por 2d6 rounds**
- Unidades em debandada arriscam espalhá-lo: **3 chances em 6** por unidade atravessada, causando **3 de dano por round durante 1d6 rounds**

**Siege Tower** — *2 Wealth por unidade armada*
Torre de madeira fortificada sobre rodas, puxada por cavalos ou escravos. Move **10 jardas por round** e comporta **uma unidade**, concedendo-lhe **+5 de Defense**. Alcançando as muralhas, **a unidade não precisa testar Athletics para escalar**.
- **AR 8, 20 Health.** Reduzida a 0, **a torre e a unidade dentro dela são Destroyed**

**Turtle** — *1 Wealth por unidade armada*
Chassi robusto de madeira com topo arredondado sobre seis a oito rodas enormes. Comporta **uma unidade** não-cavalaria, não-navio.
- Movement reduzido a **10 jardas**, mas **+10 de Defense**
- **A unidade não pode atacar** enquanto protegida
- Sair da tartaruga exige **uma ordem de movimento**

### Discipline

É a **Difficulty do teste de Warfare** para emitir ordens e retomar o controle. Tropas inexperientes são mais difíceis de controlar que veteranas, e certos tipos são menos controláveis que outros.

---

# Anatomia de uma Batalha

| Passo | |
|-------|--|
| 1 | Battlefield |
| 2 | Unit and Leader Placement |
| 3 | Parlay and Terms |
| 4 | Initiative |
| 5 | Siege Weapons |
| 6 | First Player Actions |
| 7 | Orders |
| 8 | Second Player Actions |
| 9 | Resolve Standing Orders |
| 10 | Repeat (4–9) |
| 11 | Resolution and Consequences |

## Passo 1 — O Campo de Batalha

Cinco componentes: **scope, terrain, visibility, weather e fortifications**.

### Scope

O tamanho efetivo da área. Deve ser **proporcional aos exércitos envolvidos**. Com miniaturas, ao menos **10 polegadas quadradas por quatro unidades de cada lado**.

> **Se uma unidade se mover além do escopo, remova-a do jogo.**

### Terrain

Provavelmente o componente de maior influência sobre o resultado. **Regra prática: um tipo de terreno para cada quatro unidades envolvidas** — quanto mais traços de terreno, mais complicado o engajamento.

> Um comandante pode **gastar 1 Destiny Point para ignorar os efeitos do terreno numa ordem**.

| Terreno | Efeitos |
|---------|---------|
| Coast | Enables warships |
| Community, Hamlet | Slow movement |
| Community, Small Town | Cover (+1 Defense), slow movement |
| Community, Large Town | Cover (+2 Defense), slow movement |
| Community, Small City | Cover (+3 Defense), slow movement, no cavalry |
| Community, Large City | Cover (+5 Defense), slow movement, no cavalry |
| Desert* | Slow movement |
| Grassland | — |
| Hill | Slow movement, **+1B** em Fighting e Marksmanship† |
| Island | Enables warships |
| Mountain | **+2B** em Fighting e Marksmanship†, very slow movement, no cavalry, no siege weapons |
| Plain | — |
| Road | Remove slow movement; converte very slow em slow; **habilita cavalaria** (em montanhas) |
| Ruin | Cover (+2 Defense) |
| Wall | Cover (+5 Defense), **blocks movement** |
| Water, Stream | Slow movement |
| Water, River | Blocks movement (ou slow movement com ponte), enables warships |
| Water, Pond | Slow movement, enables warships |
| Water, Lake | Blocks movement, enables warships |
| Wetland | Slow movement |
| Woods, Light | Cover (+2 Defense) |
| Woods, Dense | Cover (+5 Defense) |

\* Deserto é qualquer terreno de planície sem campina, água ou bosque.
† O bônus aplica-se a ataques contra oponentes em **elevações menores**.

**Definições:**

- **Blocks Movement** — unidades (exceto navios) não podem entrar
- **Bonus Dice** — unidades **defendendo** naquele terreno ganham os bonus dice indicados em Fighting e Marksmanship (limitados pelos ranks)
- **Cover** — bônus de Defense contra ataques de Fighting e Marksmanship
- **Enables Warships** — permite navios no campo; eles só fazem Fighting contra unidades adjacentes e Marksmanship contra unidades no alcance
- **No Cavalry** — impede o uso de cavalaria. Certos traços de terreno anulam isso
- **No Siege Weapons** — impede **os atacantes** de usar máquinas de cerco. **Se o defensor tem uma fortificação, ele pode usá-las normalmente**
- **Slow Movement** — **−10 jardas** (ou −1 jarda na escala de personagem)
- **Very Slow Movement** — **−20 jardas** (ou −2 jardas na escala de personagem)

### Visibility

Funciona como as Vision Qualities do [[09-combate]]:

- **Dim light:** −1D em Agility, Athletics, Awareness, Fighting e Thievery; **−2D** em Marksmanship
- **Darkness:** todo terreno conta como slow movement (ou very slow, se já era slow); **−2D** nas mesmas abilities e **−4D** em Marksmanship

> Dada a dificuldade de iluminar um campo inteiro, **batalhas raramente são travadas no escuro** — exércitos tipicamente aguardam a primeira luz da aurora.

### Weather

Há uma razão para a maioria dos exércitos escolher lutar em dias claros. **O Narrador escolhe o clima**, embora alguns personagens possam prever condições e aconselhar quando golpear ou aguardar.

| Clima | Efeito |
|-------|--------|
| **Chuva fraca** | Nenhuma penalidade |
| **Chuva forte** | **−2** aos resultados de Fighting e Marksmanship. Chuva prolongada pode converter o terreno em slow movement e transformar riachos em rios |
| **Neve fraca** | **−2** aos resultados de Fighting e Marksmanship |
| **Neve forte** | Como a fraca, **e reduz a visibilidade a darkness** |

### Fortifications

Movimentar-se por uma área com fortificação **exige uma ordem** (escalar as muralhas, cruzar o fosso).

| Fortificação | Bônus | Capacidade |
|--------------|-------|------------|
| Superior Castle | **+12 Defense** | 10 unidades |
| Castle | **+8 Defense** | 5 unidades |
| Small Castle | **+6 Defense** | 3 unidades |
| Hall | **+4 Defense** | 2 unidades |
| Tower | **+3 Defense** | 1 unidade |

**Fortificações temporárias** — valas, estacas, taludes de terra. **Qualquer unidade pode montá-las com ao menos seis horas antes da batalha**, protegendo **uma única unidade**: **+1 de Defense**, ou **+2** se construída por uma unidade de **engenheiros**.

## Passo 2 — Posicionamento

**O defensor coloca primeiro** uma unidade em seu lado do campo; depois o atacante; e assim alternadamente até todas estarem posicionadas. Em seguida o **atacante** posiciona comandante e subcomandantes; depois o defensor. Por fim, os **heróis**, começando pelo defensor — no campo, ou acoplados a unidades.

### Unidades ocultas

Possível se houver terreno que conceda cobertura. A unidade rola **Stealth** contra o **resultado passivo de Awareness da unidade inimiga mais próxima**. Sucesso concede **+1D no primeiro teste de Fighting ou Marksmanship** — perdido se ela for detectada antes de atacar.

> **Não coloque a unidade oculta no campo**: anote a posição num papel à parte e coloque-a apenas quando atacar.

## Passo 3 — Parlay and Terms

Antes da batalha, o atacante pode oferecer termos enviando um emissário sob a bandeira da paz; o defensor também pode. O atacante declara o que oferece em troca da rendição — normalmente poupar as vidas das tropas e tomar os heróis como reféns. O defensor pode oferecer recursos para apaziguá-lo. **Acordados os termos, a batalha é evitada.**

> **Atacar um emissário sob a bandeira da paz é ato desonroso: reduz o recurso Influence da casa em 1d6.**

## Passo 4 — Initiative

Cada comandante rola um teste de **Warfare**. Empate: maior rank em Warfare, depois bonus dice de **Strategy**.

> Diferente do combate, **a iniciativa é determinada a cada round**, para dar conta dos elementos não quantificáveis que alteram o tom do campo — ordens malfeitas, reveses, fumaça, ruído. E se um comandante cair, a mudança de ordem reflete as diferenças entre comandantes.

## Passo 5 — Siege Weapons

Cada lado, começando pelo vencedor da iniciativa, pode **gastar uma ordem** para disparar um número de máquinas igual ao **rank de Warfare do comandante**.

A **unidade de engenheiros** que controla a máquina (uma unidade controla até **quatro** máquinas) rola um teste de **Warfare** contra a **Defense** da unidade alvo, causando dano **× grau de sucesso**.

> **Uma máquina de cerco disparada não pode ser disparada no battle round seguinte** — efetivamente, dispara a cada dois rounds.

### Catapult

*Recursos: 1 Wealth (pequena), 2 (média), 4 (grande)*
**Move:** estacionária em batalha · **AR** 5 · **Health** 10/20/40 · **Alcance** 300/400/500 jardas

| Tamanho | Pedra | Piche/Óleo | Sage's Fire |
|---------|-------|------------|-------------|
| Pequena | 3 | 3† | 7‡ |
| Média | 5 | 5† | 7‡ |
| Grande | 7 | 7† | 7‡ |

† Dano ignora AR. ‡ Comporta-se como Sage's Fire.

Munição de pedra não tem custo extra; para barris de óleo ou sage's fire é preciso gastar Wealth como se equipasse uma unidade comum.

**Contra muralhas e fortificações** (usando a ação **Break** de [[09-combate]], não Smash): **Athletics 5** (pequena), **7** (média), **9** (grande).

### Mangonel

*Recursos: 3 Wealth* · **Move** 10 jardas · **AR** 3 · **Health** 20 · **Dano** 6 · **Alcance** 200 jardas

Prima da catapulta e do trabuco. Invenção anterior ao trabuco, arremessa com **trajetória mais baixa e velocidade maior** — seu propósito é **derrubar muralhas**, não atacar defensores por cima delas. Diz-se que **escoiceia como uma mula** ao disparar. Mais arma de campo, frequentemente sobre rodas, arremessa pedras e piche em chamas. Pouco precisa, mas manobrável e versátil.

- **Contra muralhas:** **Athletics 10**
- **Contra unidades:** impõe **−1D** nos testes de Warfare

### Scorpion

*Recursos: 1 Wealth* · **Move** 10 jardas · **AR** 1 · **Health** 10 · **Dano** 3 (**ignora armadura**) · **Alcance** 500 jardas

Essencialmente uma besta gigante, usando molas de torção de crina de cavalo ou tendões animais. Arremessa lanças ou pedras.

> Na escala de batalha, **cada "scorpion" são na verdade três dispositivos**, que disparam juntos contra a mesma unidade causando o dano normal.
> **Contra um personagem individual:** o atacante rola Warfare com **−1D**; um acerto causa **10 de dano**.

### Spitfire

*Recursos: 2 Wealth* · **Move** 10 jardas · **AR** 2 · **Health** 10 · **Alcance** 200 jardas

Feita para arremessar potes de óleo fervente, de argila, que se estilhaçam no impacto.

- Munição padrão (óleo fervente): **3 de dano, ignorando armadura**
- Pode ser melhorada para **sage's fire** (gastando Wealth): **7 de dano**, comportando-se como descrito acima

### Trebuchet

*Recursos: 4 Wealth* · **Move:** nenhum · **AR** 4 · **Health** 40 · **Dano** 7 · **Alcance** 500 jardas

Arremessa projéteis de várias centenas de libras a alta velocidade. Normalmente pedra — mas **cadáveres infectados por doença** podem ser lançados dentro de um reduto para aterrorizar os de dentro.

> Trabucos **menores** (relativamente portáteis, acionados por polia e corda) → trate como **catapulta média**. Os **maiores** (com série de contrapesos) → trate como **catapulta grande**. Alguns exércitos constroem trabucos maciços para sitiar os maiores castelos; a construção é lenta e exige quantidades enormes de madeira, e são erguidos em **posição permanente** — podem reduzir uma fortificação de pedra a escombros.

- **Contra muralhas:** **Athletics 12**

## Passo 6 — First Player Actions

Personagens **não acoplados** a unidades podem agir por **cinco combat rounds** (cerca de 30 segundos). Se irromper combate entre eles, resolva pelas regras normais.

> **Comandantes e subcomandantes não podem agir neste passo**, exceto para renunciar ao comando ou se acoplar a uma unidade.

**Renounce Command** *(Greater)* — quem funciona como comandante ou subcomandante pode renunciar e agir normalmente. **Havendo subcomandantes, o de maior Status vira comandante.**

**Attach** *(Greater)* — qualquer personagem não integrado pode se acoplar a uma unidade. Se já emitiu ordens naquele round, só pode se acoplar a uma unidade a que **deu ordens**.
- A unidade **melhora a Discipline em −3** e ganha **+1D** em Fighting e Marksmanship
- **Personagens acoplados não podem agir** além das ordens dadas à unidade
- Comandantes acoplados **não podem emitir ordens** e reduzem o total de ordens normalmente
- **Personagens acoplados além do primeiro não conferem benefício adicional**

**Attack Unit** *(Greater)* — um personagem pode atacar uma unidade pelas regras normais. Porém, contra ataques de indivíduos, **unidades ganham +20 de Defense**.

**Attack Portions of Units** *(Lesser)* — tática melhor: focar num pequeno segmento. Resolve-se pelas regras normais de combate, mas você enfrenta **10 soldados por vez** em vez de 100. **A cada 10 soldados derrotados, a unidade perde 1 ponto de Health.** Como 1 battle round = 10 combat rounds, o Narrador pode permitir que um combate breve se resolva num único battle round.

**Organize / Rally** *(Greater)* — role **Warfare** contra a Discipline da unidade. Sucesso torna uma unidade **Disorganized** em **Organized**, ou uma **Routed** em **Disorganized**.

## Passo 7 — Orders

Cada comandante emite **uma ordem por vez**, alternando com os demais até todos terem emitido todas as suas ordens do round.

- Role **Warfare** contra a **Discipline** da unidade
- **Sucesso** — a unidade segue a ordem
- **Falha** — a unidade executa a última ordem recebida no **Passo 9**. Sem standing orders, não age
- **Sem ordem prévia no engajamento, ou Critical failure** — nenhuma ação
- **Sucesso ou falha, a ordem é consumida**

> Você pode **reemitir** uma ordem que falhou, gastando outra ordem e aceitando o modificador acumulado de Difficulty.

### Ordens básicas

**Attack** — a unidade ataca a unidade indicada. Para Fighting, precisa estar **engajada** (adjacente); para Marksmanship, o alvo deve estar no alcance. Role Fighting ou Marksmanship contra a **Defense**; o dano (conforme o tipo) é multiplicado pelo grau e subtraído do AR do alvo.
> *Standing:* continua a atacar unidades inimigas adjacentes a cada round (Fighting), ou a unidade inimiga mais próxima (Marksmanship).

> **Unidades contra personagens:** ao atacar um personagem individual, a unidade ganha **+2D** em Fighting ou Marksmanship.

**Charge** — combina movimento e um único ataque, contra qualquer inimigo dentro do sprint. **−1D** no Fighting, mas **+2 de dano base**.
> *Standing:* continua a atacar unidades adjacentes a cada round.

**Defend** — a unidade testa **Agility** e **substitui sua Defense pelo resultado** por um round, **mesmo se pior**. Com escudos, soma o rating dos escudos ao resultado.
> *Standing:* continua a defender a cada round.

**Fighting Withdrawal** — atacar e recuar. Sucesso permite um teste de Fighting ou Marksmanship com **−1D** e depois mover até **metade** do movimento. **Critical failure:** a unidade fica **Disorganized** além de não agir.
> *Standing:* continua a recuar em direção ao comandante a cada round.

**Move** — move à taxa normal (para girar, mudar de direção) ou em **sprint** — neste caso, **em linha reta**.
> *Standing:* nada faz até receber nova ordem.

**Organize** — restaura a Discipline de uma unidade Disorganized.
> *Standing:* nada faz até receber nova ordem.

**Ready** — ação atrasada: prepara um ataque ou movimento. **Você deve definir as condições** em que a unidade agirá — outra unidade entrar no alcance, ou mover-se se outra unidade debandar.
> *Standing:* permanece pronta até a condição ocorrer; depois ataca ou nada faz, conforme sua última ação.

**Rally** — sucesso torna uma unidade **Routed** em **Disorganized**, permitindo comandá-la normalmente.
> *Standing:* nada faz até receber nova ordem.

**Regroup** — remove **1 ponto de dano por grau de sucesso**.
> *Standing:* nada faz até receber nova ordem.

**Retreat** — recuo ordenado. **Critical failure:** a unidade **Routs** além de não agir.
> *Standing:* afasta-se da batalha um movimento por round até receber nova ordem.

**Surrender** — rendição geral. **Teste Warfare para cada unidade ativa**; numa falha, aquela unidade **Routs**.
> *Standing:* a unidade é removida do jogo.

## Passo 8 — Second Player Actions

Personagens ainda não acoplados podem agir por mais **5 rounds**. **Comandantes e subcomandantes que emitiram ordens no Passo 7 não podem agir aqui.**

**Detaching Characters** *(Greater)* — um personagem acoplado pode se desacoplar a qualquer momento nesta fase, mas **não pode tomar outras ações até o próximo battle round**.

**Take Command** *(Greater)* — perdido um comandante ou subcomandante, outro personagem aliado com **Status 2+** pode assumir. Personagens de Status menor podem tentar, mas isso exige uma **intriga simples** ([[08-intriga]]) ou outro gesto para conquistar a confiança da tropa, com Difficulty e requisitos definidos pelo Narrador. Dali em diante, o personagem **não age mais nos passos de jogador** e funciona como comandante normal.

## Passo 9 — Resolve Standing Orders

Começando pelo vencedor da iniciativa, cada comandante escolhe **uma unidade que ainda não agiu nem recebeu ordens** neste round e resolve as ordens vigentes do round anterior.

## Passo 10 — Repeat

Repita os passos 4–9. A batalha termina quando todos os lados exceto o vencedor se renderam, debandaram ou foram destruídos. **Unidades individuais podem sofrer essas consequências antes do fim da batalha** — consulte o Passo 11 quando ocorrerem e depois retorne aos passos 4–9.

## Passo 11 — Resolução e Consequências

### Dano e moral

Enquanto a Health estiver acima de 0, a unidade **não é prejudicada de forma alguma**. Reduzida a 0 ou menos, ela pode ficar **Disorganized, Routed ou Destroyed**.

**Disorganized** — ao ser reduzida a 0 Health. **−1D em todos os testes** e **+3 de Difficulty na Discipline**. Ainda pode receber ordens e lutar, mas está significativamente enfraquecida.
- Uma unidade Disorganized que sofrer dano de novo **Routs**
- A ordem **Organize** remove todo o dano, **mas mantém as penalidades**
- **Os efeitos de Disorganization são cumulativos**: se as penalidades igualarem o rank de **Endurance** da unidade, ela é **Destroyed**

**Routed** — ao sofrer qualquer dano estando Disorganized. Se o dano excederia **o dobro da Health máxima**, ela é **Destroyed** em vez disso. A formação muda automaticamente para **Mob**, e a unidade imediatamente **corre para longe** da unidade atacante — se isso a levar para fora do escopo do campo, **é removida do jogo**.
- Uma unidade Routed que sofrer dano é **Destroyed**
- A ordem **Rally** a torna Disorganized; uma ordem **Organize** a restaura

**Destroyed** — de três formas:
1. Dano superior ao **dobro da Health máxima** num único acerto
2. Qualquer dano **estando Routed**
3. Penalidades acumuladas de Disorganization **iguais ao rank de Endurance**

### Personagens acoplados e dano

| A unidade… | O personagem… |
|-----------|---------------|
| sofre dano | sofre **1 ponto** (ignorando AR) |
| fica Disorganized | sofre **2 pontos** (ignorando AR) |
| fica Routed | sofre **5 pontos** (ignorando AR) |
| é Destroyed | sofre **10 pontos** (ignorando AR) |

Personagens podem reduzir esse dano normalmente, com fadiga, injuries ou wounds.

### Comandantes e heróis mortos

Qualquer unidade **adjacente** a um comandante ou herói abatido deve passar imediatamente num teste de **Will**:

- **Formidable (12)** quando cai um **comandante**
- **Challenging (9)** quando cai um **herói**

Falha torna a unidade **Disorganized** (se organizada), **Routed** (se Disorganized) ou **Destroyed** (se Routed).

### Glory

| Circunstância | Glory |
|---------------|-------|
| Derrotou 3 unidades ou menos | 1 |
| Derrotou 3–6 unidades | 2 |
| Derrotou 7–9 unidades | 3 |
| Derrotou 10 ou mais unidades | 4 |
| Em desvantagem de 3:2 | +1 |
| Em desvantagem de 2:1 | +2 |
| Em desvantagem de 3:1 ou mais | +3 |

> **O comandante derrotado também ganha 1 Glory** por ter participado da batalha.

### Recursos

| Recurso | Efeito |
|---------|--------|
| **Defense** | Se a fortaleza não foi destruída, o vencedor aumenta a Defense pelo valor investido nela **e ganha o holding**; o vencido perde o mesmo. O vencedor pode depois ceder o controle a uma casa vassala, baixando sua Defense |
| **Lands** | O vencedor pode tomar as terras: o domínio e o valor correspondente do investimento passam a ele, e o perdedor reduz o próprio no mesmo montante. **Para reter a terra, o vencedor deve mantê-la (com unidades presentes) por ao menos 3 meses** |
| **Law** | O perdedor reduz Law em **1d6**. Se o vencedor mantiver o domínio, **ele também reduz Law em 1d6** pela agitação criada |
| **Population** | Se o perdedor perdeu um domínio, **−1d6**. Se o vencedor optar por manter a terra, **+1d6−1** |
| **Power** | Unidades destruídas reduzem a Power da casa pelo valor investido |
| **Wealth** | Se o domínio incluía comunidade ou fortaleza, o vencedor ganha **+1d6−1**; o perdedor perde **2d6**. Investimentos de Wealth ligados ao domínio também são transferidos, com perda e ganho correspondentes |

### Comandantes e heróis capturados

O comandante vencedor decide o destino dos capturados. Normalmente há resgate, mas qualquer desfecho de derrota do [[09-combate]] é possível.

> **Resgate típico: 1 ponto de Wealth por rank de Status do cativo.** Personagens podem **queimar** um Destiny Point para evitar morte certa e ditar consequências diferentes.

O Narrador pode usar a derrota como oportunidade de interação com os inimigos na condição de prisioneiro — um palco singular para intrigas.

### Unidades e baixas

Para cada unidade, role **1d6** e compare à coluna que melhor descreve sua condição ao final da batalha. **Use a coluna "Routed" apenas** se a unidade foi removida do jogo por debandada ou estava Routed ao fim da batalha.

| 1d6 | Sem dano | Danificada | Disorganized† | Routed | Destroyed |
|-----|----------|-----------|---------------|--------|-----------|
| 0 ou menos | −2 training | −3 training | Destroyed | Destroyed | Destroyed |
| 1 | −1 training | −2 training | −3 training | Destroyed | Destroyed |
| 2 | Intact | −1 training | −2 training | −3 training | Destroyed |
| 3 | Intact | Intact | −1 training | −2 training | −3 training |
| 4 | Intact | Intact | Intact | −1 training | −2 training |
| 5 | +1 training | Intact | Intact | Intact | −1 training |
| 6 | +2 training | +1 training | Intact | Intact | Intact |

† Subtraia **−1** cada vez que a unidade tiver ficado Disorganized.

- **Destroyed** — destruída por baixas e desertores. **Reduza sua Power pelo montante investido nela**
- **Intact** — remova todo o dano e penalty dice
- **Training** — ajusta o nível efetivo de treinamento. Uma unidade *trained* com **−1 training** vira *green* (reforços e recrutas crus substituem os mortos); com **+1 training**, vira *veteran*. Ajustes podem forçar redução ou aumento de abilities
  - **Se um resultado baixaria a unidade abaixo de green, ela é Destroyed**
  - **Se elevaria acima de elite**, ela ganha **+1 rank numa ability por passo acima de elite** — e **você não precisa pagar por essas melhorias** com o recurso Power

---

# Regras Avançadas

## Ordens avançadas

Cada uma inclui um **modificador de Difficulty** somado à Discipline da unidade.

**Ambush** *(+3)* — só para unidade **oculta**. Sucesso aumenta o dano em **+2 no primeiro round de batalha**. *Standing: como Attack.*

**Blitz** *(+6)* — a unidade move até o sprint **em linha reta**, podendo atravessar unidades inimigas e fazer um ataque de Fighting contra cada uma no caminho. **Cada unidade atacada após a primeira impõe −1D**, que persiste até o fim do battle round. **A unidade não pode terminar o movimento no espaço de outra unidade.** *Standing: como Attack.*

**Envelop** *(+6)* — a unidade envolve completamente a inimiga, fundindo-se a ela. Faz um ataque de Fighting normalmente. **Se o inimigo tentar recuar ou desengajar, sua unidade faz um ataque livre.** Ataques de Marksmanship bem-sucedidos contra unidades envolvidas **causam dano a ambas**. *Standing: continua envolvendo; se o inimigo se afastar, nada faz até nova ordem.*

**Force Back** *(+3)* — teste de **Fighting** contra o **Athletics passivo** da unidade inimiga. Sucesso a empurra **10 jardas por grau**. **Não pode ser empurrada para dentro de outra unidade.** Penalidades de movimento por terreno se aplicam: se o empurrão não a levar longe o bastante para entrar em terreno slow ou very slow, ela **para na borda** do terreno. *Standing: como Attack.*

**Hammer and Anvil** *(+6)* — exige que outra unidade já tenha recebido a ordem **Ready** para atacar. A unidade que recebe esta ordem deve estar **engajada** com a inimiga e vencer um **Athletics oposto**: sucesso empurra os inimigos por **metade do movimento**. Se o empurrão os colocar em contato com a unidade preparada, ela faz seu ataque de Fighting com **+1D**. *Standing: como Attack.*

**Pincer** *(+3)* — divida seus dados de Warfare para ordenar que **duas unidades próximas ataquem a mesma inimiga**. Se ambos os testes tiverem êxito, cada unidade faz um único ataque com **+1D**. **Só pode ser dada a unidades de Fighting.**

**Probing Attack** *(+6)* — ataque cauteloso: **−1D** no Fighting (persistindo até o fim do battle round), mas **+2 de Defense** até o início do próximo battle round. *Standing: como Attack.*

**Reform** *(+3)* — combina **duas unidades danificadas adjacentes** numa só saudável. Sucesso remove a unidade mais ferida (anotando os recursos investidos, para reduzi-los da Power ao fim da batalha) e **remove todo o dano da remanescente**. *Standing: nada faz até nova ordem.*

**Sap** *(+3)* — só para unidade de **engenheiros adjacente a uma fortificação**. Ela deve passar num **Formidable (12)** de Knowledge (o Knowledge Focus de **arquitetura** se aplica, e sapadores treinados costumam tê-lo). Sucesso **reduz o bônus de Defense da fortificação em 1 por grau**. Algumas fortificações são tão grandes que uma equipe só afeta uma pequena área por vez. **Enquanto executam esta ordem, os engenheiros sofrem −5 de Defense.** *Standing: nada faz até nova ordem.*

**Scale Walls** *(+3)* — a unidade deve passar num teste de **Athletics** com Difficulty definida pelo Narrador conforme a muralha. Sucesso escala **jardas iguais ao movimento normal**. **Se a unidade estiver armada com ganchos e cordas ou escadas de assalto, esta ordem não aumenta a Difficulty do Warfare.** *Standing: continua tentando até conseguir ou receber nova ordem; encontrando unidade inimiga no topo, ataca.*

**Set for a Charge** *(+3)* — se uma unidade inimiga carregar contra ela a qualquer momento do round, ela faz um ataque de Fighting. **Um acerto causa o dobro do dano da arma**, mais dano adicional por graus normalmente. *Standing: como Attack.*

**Slash and Burn** *(+3)* — a unidade queima colheitas, incendeia construções e aterroriza plebeus. **O senhor ou família governante da terra reduz Population e Wealth em 1 cada vez que a ordem é dada.** *Standing: nada faz até nova ordem.*

**Split Attack** *(+6)* — a unidade divide seus dados de Fighting ou Marksmanship entre **dois ou mais oponentes**. **Cada ataque deve ter ao menos um dado.** Bonus dice podem ser divididos igualmente, sujeitos aos limites normais. *Standing: como Attack.*

**Suppressing Fire** *(+3)* — uma unidade de **arqueiros** dispara uma salva para impedir o movimento inimigo. Sucesso no teste de Marksmanship **aumenta em +3 a Difficulty para emitir ordens à unidade alvo**; cada grau adicional soma mais **+1**. **Não causa dano num sucesso simples**; causa dano normal com **dois graus**, e dano adicional por grau daí em diante. *Standing: como Attack.*

**Trample** *(+3)* — **só para cavalaria**. A unidade move em sprint, em linha reta, podendo fazer um ataque de Fighting contra qualquer unidade no caminho; um acerto causa **+5 de dano**. Cada ataque após o primeiro sofre **−1D**. *Standing: como Attack.*

## Facing

Modificadores aplicam-se **apenas a testes de Fighting**.

| Situação | Bônus do atacante |
|----------|-------------------|
| **Flanco** | **+1B** |
| **Retaguarda** | **+1D** |
| **Cercada** | Frente **+1B**, flancos **+1D**, retaguarda **+2D** |

**Atacando os atacantes:** uma unidade pode atacar inimigos nos **flancos** com **−1D**. **Não pode atacar inimigos que golpeiam sua retaguarda.**

### Ordens de facing

**Reverse** *(+0)* — a unidade inverte a posição, apontando na direção oposta. **Numa falha, ela ainda se reorienta, mas o oponente mantém seus benefícios** até o início do próximo battle round. *Standing: ataca qualquer unidade à frente ou nos flancos.*

**Wheel** *(+3)* — muda o facing para a esquerda ou direita. Manobra mais complexa que um simples movimento, pois a unidade deve mover-se com precisão para manter a linha. **Numa falha, ela ainda muda o facing, mas o oponente mantém o bônus de flanco** até o início do próximo round. *Standing: ataca qualquer unidade à frente ou nos flancos.*

## Formações

Uma ordem pode mudar a formação de uma unidade.

| Formação | Difficulty | Benefício | Desvantagem |
|----------|-----------|-----------|-------------|
| **Battle** | +0 | Nenhum | Slow movement |
| **Checkered** | +0 | **+5 Defense** contra Marksmanship; **+1D** em Fighting contra *mobs* | **+3 Discipline**, slow movement |
| **Column** | +0 | Nenhum | **−1D** em Fighting |
| **Mob** | **−3** | Nenhum | **−5 Defense**, **+6 Discipline** |
| **Phalanx** | +9 | **+5 Defense** contra Fighting | **−5 Defense** contra Marksmanship, very slow movement |
| **Shield Wall** | +6 | **+5 Defense** contra todos os ataques de Fighting; **anula os benefícios de carga**; unidades **atrás** dela ganham **+5 de Defense** pela cobertura | **Sem movimento** |
| **Square** | +6 | **Anula os bônus de ataques por flanco e retaguarda** | **Sem movimento** |
| **Tortoise Shell** | +9 | **+5 Defense** contra todos os ataques | **Não pode atacar**, very slow movement |
| **Wedge** | +3 | **+1D** em Fighting relacionado a cargas | **−5 Defense** contra Marksmanship |

- **Battle** — a formação comum: fileiras cerradas, cada homem protegendo o vizinho. Semelhante à falange em alguns aspectos, mas mais rápida e versátil
- **Checkered** — os soldados se espalham para reduzir o alvo. O tamanho expandido dificulta o controle, pois torna difícil disseminar novas ordens
- **Column** — usada primariamente para mover tropas de forma ordenada
- **Mob** — a menos desejada, encontrada em unidades Routed e levas sem treino. **Sempre que uma unidade Routs, ela entra em Mob gratuitamente**
- **Phalanx** — só para unidades não-cavalaria e não-navio. As fileiras da frente formam muro de escudos enquanto as de trás usam lanças. Formidável contra o corpo a corpo, mas **exige muita disciplina e perícia**
- **Shield Wall** — barreira sólida de escudos formando obstáculo temporário, feita para frustrar cargas e assaltos frontais
- **Square** — quadrado com defensores voltados para cada direção. Defensivamente adequada, mas **imóvel**
- **Tortoise Shell** — muro de escudos móvel em formação quadrada, com os escudos das tropas internas erguidos, encerrando completamente a unidade
- **Wedge** — formação em V, feita para perfurar as fileiras inimigas. Extremamente eficaz em cargas, mas deixa a unidade vulnerável a ataques à distância

---

Anterior: [[09-combate]] · Próximo: [[11-o-narrador]]
