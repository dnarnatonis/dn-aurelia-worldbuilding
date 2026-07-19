---
title: "Chronicle System — Cap. 1: Regras de Jogo"
category: "Chronicle System"
tags: [reference, rules, chronicle-system, core, test, difficulty, dice]
related_concepts: [test, difficulty, bonus dice, penalty dice, degrees of success]
source: "Sword Chronicle (Green Ronin, 2020), Cap. 1, pp. 8–13"
---

# Cap. 1 — Regras de Jogo

Este capítulo é o alicerce. Tudo o mais — criação de personagem, combate, guerra, intriga — se apoia no processo de **Test** descrito aqui.

## Os dados

O sistema usa apenas **d6**. São rastreados de três formas:

| Tipo | Notação | Como funciona |
|------|---------|---------------|
| **Test Dice** | `#D` | Dados rolados e **somados**. Quantidade = rank da ability. `+2D` significa "adicione dois test dice". |
| **Bonus Dice** | `#B` | Dados extras rolados **junto** com os test dice. Nunca são somados diretamente: role tudo e **mantenha os melhores** em número igual aos test dice. |
| **Penalty Dice** | `–#D` | Cada penalty die **cancela um test die** ao somar. Aplicado *depois* de rolar e *depois* de descartar bonus dice. |
| **Modifier** | `+#` / `–#` | Bônus ou penalidade fixa aplicada ao **resultado** do teste. |

**Regra crítica dos bonus dice:** o número de bonus dice nunca pode exceder o número de test dice rolados. Com 2 test dice e 3 bonus dice disponíveis, você rola 4 dados e mantém 2.

**Resultados aleatórios** são pedidos como `#d6` — role e some.

## Tests e Difficulties

Sempre que uma ação tem consequências dramáticas ou resultado incerto, testa-se uma ability. Um **Test** é uma rolagem visando igualar ou superar a **Difficulty** da ação.

### O processo de teste — 7 passos

| Passo | Quem | O que |
|-------|------|-------|
| 1 | Jogador | Declara a ação |
| 2 | Narrador | Escolhe a ability mais relevante |
| 3 | Narrador | Define a Difficulty |
| 4 | Jogador | Rola dados = rank da ability (+ bonus dice) |
| 5 | Jogador | Soma os dados e aplica modificadores |
| 6 | Jogador | Compara o resultado com a Difficulty |
| 7 | Narrador | Descreve o desfecho |

**Passo 1 — Declarar a ação.** Se a ação não tem risco significativo nem consequência para o fracasso, não precisa de teste. O Narrador tem a palavra final.

**Passo 2 — Escolher a ability.** Abilities são flexíveis: a mesma ação pode usar abilities diferentes conforme o método. Passar por um guarda pode ser Persuasion (enganá-lo) ou Status (impor a posição). O jogador pode propor qual usar e como; se razoável, o Narrador deve permitir.

**Passo 3 — Definir a Difficulty.** Ver tabela abaixo.

**Passos 4–6 — Rolar, somar, comparar.** Resultado ≥ Difficulty = sucesso.

**Passo 7 — Descrever.** O Narrador narra o desfecho e as consequências.

> **Exemplo.** Lady Lanara tem Awareness 3 (Notice 2B) e escuta conspiradores num salão escuro. O Narrador define Difficulty Formidable (12). Nicole rola 5 dados: 6, 6, 5, 2, 1. Descarta o 1 e o 2 (dois bonus dice) e soma 17. Sucesso por larga margem.

## Tipos de teste

### Basic Test

O padrão. Se a situação não indicar outro tipo, use este.

1. Role test dice = rank da ability
2. Role bonus dice de specialty ou assistência
3. Descarte dados em número igual aos bonus dice rolados; some o resto
4. Aplique modificadores
5. Compare com a Difficulty

### Extended Basic Test

Ações longas ou ambiciosas exigem **múltiplos sucessos**. O Narrador informa quantos sucessos são necessários; cada teste cobre um intervalo de tempo. Ex.: escalar um penhasco íngreme (Athletics repetido), pesquisar uma linhagem oculta (Knowledge repetido).

### Competition Test

Dois personagens competem pelo mesmo objetivo. Ambos rolam contra a **mesma Difficulty**. Vence quem superar a Difficulty **pela maior margem**.

> **Exemplo.** Corrida a pé, Difficulty Automatic (0). Chris (Athletics 3) rola 6, 4, 1 = 11. Hal (Athletics 2, Run 1B) rola 5, 2, 2 — descarta um 2 pelo bonus die, ficando com 7. Chris vence.

### Conflict Test

Usado sempre que algo funcionaria como um **"ataque"** — golpe de espada, esgueirar-se por um guarda, seduzir um nobre. Qualquer coisa que você "faça a alguém".

A Difficulty é a **Defense do oponente**, geralmente **4 × o rank da ability oposta** (Awareness contra Stealth, ataque de veneno contra Endurance). Em combate, a Defense é a soma de ranks de várias abilities — ver [[09-combate]].

**Quem rola?** Quem for o **oponente ativo**. Se o guarda procura ativamente alguém escondido, o guarda rola. Se o personagem tenta passar por um guarda desatento, o personagem rola Stealth contra a Awareness passiva do guarda.

**Conflitos simultâneos.** Quando ambos "atacam" ao mesmo tempo, ambos testam e vence o maior resultado.

## Modificando testes

### Modifiers

Número fixo somado ou subtraído do resultado, refletindo condições temporárias que afetam *você*, não a ação. Vêm de assistência, condições ambientais ou ferimentos.

### Assistance

Qualquer aliado adjacente pode ajudar. O aliado concede um modificador igual a **metade do rank dele na ability testada** (arredondado para baixo, mínimo 1). Normalmente no máximo **duas pessoas** ajudam por vez; em tarefas maiores o Narrador pode permitir mais.

> Aliado com Athletics 4 assiste → `+2` no resultado.

### Taking More Time

Com tempo disponível, cada intervalo adicional de preparação (uma hora de pesquisa, seis segundos extras antes de escalar) concede **um test die extra**. Limite: não se pode ganhar mais que o **dobro** dos test dice originais. Com ability 2, no máximo +2D.

### Specialties & Bonus Dice

Specialties são áreas de expertise dentro de uma ability. Ao testar a ability de modo relacionado à specialty, role bonus dice iguais ao rank da specialty. Ver [[03-abilities-e-specialties]].

> Trent tem Stealth 3 (Blend In 2). Ao se misturar à multidão, rola 5 dados e mantém os 3 melhores.

### Injuries & Frustration

Combate e intriga geram ferimentos e frustração. Ambos afetam testes — como modificador ao resultado ou, no caso de *wounds*, como **penalty dice**. Aplicam-se depois de somar os test dice.

> **Exemplo.** Rann tem 1 penalty die por um wound. Marksmanship 4 (Bows 2B) → rola 6 dados: 6, 5, 4, 4, 3, 1. Descarta 1 e 3 (bonus dice) e mais um 4 (penalty die). Resultado: 15.

## Difficulty

Difficulties sobem em incrementos de três, de 0 (automático) a 21+ (heroico).

### Test Difficulties

| Descrição | Difficulty | Rank mínimo para sucesso |
|-----------|-----------|--------------------------|
| Automatic | 0 | 1 |
| Easy | 3 | 1 |
| Routine | 6 | 1 |
| Challenging | 9 | 2 |
| Formidable | 12 | 2 |
| Hard | 15 | 3 |
| Very Hard | 18 | 3 |
| Heroic | 21+ | 4 |

## Graus de sucesso e falha

Igualar a Difficulty já é sucesso — mas um sucesso mínimo é desajeitado e nada impressionante. Superá-la por margem produz resultados melhores: ação mais rápida, resultado mais limpo, ou **dano adicional** em testes de Fighting e Marksmanship.

### Degree of Success and Failure

| Diferença entre resultado e Difficulty | Grau |
|----------------------------------------|------|
| −5 ou menos | Critical failure |
| −1 a −4 | Marginal failure |
| 0 a +4 | Marginal success |
| +5 a +9 | Great success |
| +10 a +14 | Incredible success |
| +15 ou mais | Astonishing success |

**Falha.** Falhar geralmente só significa que a ação não funcionou — normalmente pode-se tentar de novo. Quando há **perigo envolvido** e a falha é por 5 ou mais, ocorre **Critical failure**: consequências adicionais em forma de dano, ferimento ou outro revés, geralmente especificado na ação tentada.

**Graus de falha.** Existem apenas dois: Marginal (falha por 4 ou menos) e Critical (falha por 5 ou mais). O grau de falha raramente importa; quando importa, as regras dizem.

---

## Glossário de termos de jogo

| Termo | Definição |
|-------|-----------|
| **Ability** | Traço definidor do personagem, medido por **rank**. |
| **Ability Test** (ou **Test**) | Uso de uma ability quando o resultado é incerto. Role d6 igual ao rank e some. |
| **Benefit** | Quality com efeito benéfico — talento, conexão com pessoas importantes. |
| **Bonus Die** (`+#B`) | Dado extra rolado no teste; descarta-se depois um número igual de dados baixos antes de somar. |
| **Damage** | Pontos que medem quão perto o personagem está da derrota em **combate**. |
| **Degree** | Quão bem-sucedido (ou malsucedido) foi um teste, além do simples sucesso/falha. |
| **Destiny Points** | Potencial do personagem (e, em algumas crônicas, sua conexão com forças que torcem o destino), gastos para influenciar o destino. |
| **Dice** | Randomizadores. Sword Chronicle usa apenas d6. |
| **Difficulty** | Valor numérico que mede a chance de atingir um resultado. De Automatic (0) a Heroic (21+). |
| **Drawback** | Quality com efeito negativo — uma deficiência. |
| **Frustration** | Dificuldade social menor aceita para evitar influência (e portanto derrota) numa intriga. |
| **Influence** | Pontos que medem quão perto o personagem está da derrota numa **intriga social**. |
| **Injury** | Ferimento leve aceito para evitar dano (e portanto derrota) em combate. |
| **Modifier** (`+#`/`–#`) | Bônus ou penalidade aplicada ao **resultado** do teste. |
| **Penalty Die** (`–#D`) | Dado subtraído dos test dice (do menor primeiro), depois de descartar bonus dice e antes de somar. |
| **Quality** | Traço que descreve talento, capacidade ou elemento de background. Benéficas = **Benefits**; prejudiciais = **Drawbacks**. |
| **Rank** | Medida de uma ability, de 1 (*impaired*) a 7 (*legendary*). Rank médio padrão: **2**. |
| **Result** | Valor obtido somando os test dice mantidos. |
| **Test Die** (`#D`) | Dado rolado e somado como parte de um teste. |
| **Wound** | Ferimento grave e duradouro aceito para evitar dano (e portanto derrota) em combate. |

---

Próximo: [[02-criacao-de-personagem]]
