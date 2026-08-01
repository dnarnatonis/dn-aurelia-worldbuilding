# Houses — Convenção de pastas e arquivos

> **Mundo:** Lorvenia · Terras Além-Mar
> **Sistema:** Chronicle System / SIFRP, Cap. 6 *House & Lands*
> **Regras adaptadas:** [[01-house-and-lands-rules|Casas e Terras · 01: Os Reinos]] · [[02-eventos-historicos|· 02: Eventos Históricos]]

---

## 1. A estrutura

```
World/Houses/
├── README.md                       ← este arquivo
├── house-template.md               ← template da casa (história)
├── holdings-template.md            ← template de recursos e holdings
├── character-template.md           ← template de personagem
│
└── [Nome do Reino]/                ← um dos dez reinos (Tabela A)
    └── [SS]-[casa]/                ← SS = Status do chefe · nome em kebab-case
        ├── 00-[casa].md            ← história: nome, brasão, os eventos, penetração
        ├── 00-[casa].png           ← brasão renderizado (opcional)
        ├── 01-[casa]-holdings.md   ← recursos e holdings — sempre o segundo
        ├── 02-[personagem].md      ← maior Status
        ├── 03-[personagem].md      ← Status seguinte
        └── ...
```

**Exemplo real:**

```
World/Houses/
└── A Escadaria e o Planalto/
    └── 05-atesata/
        ├── 00-atesata.md
        ├── 00-atesata.png
        ├── 01-atesata-holdings.md
        └── 02-[chefe atual].md
```

---

## 2. As regras de nome

### 2.1 Pasta do reino

Nome do reino **por extenso, como está na Tabela A** de [[01-house-and-lands-rules|Casas e Terras · 01]] — com acento e espaço:

`A Capital — Ysaminguatú` · `Euictyguá — o Recôncavo` · `Os Reinos Libertos` · `O Escudo do Leste` · `A Escadaria e o Planalto` · `Mauytyguá — a Costa do Mel` · `A Marca Fria e as Lagunas` · `Os Campos do Sul` · `O Sertão — a Marca Seca` · `O Delta e o Grande Rio`

### 2.2 Pasta da casa — `[SS]-[casa]`

**`SS` = o Status máximo do chefe da casa, com dois dígitos.** Deriva de **Influência**, e só dela:

| Influência | Status | Faixa |
|:---:|:---:|---|
| 1–10 | **02** | Cavaleiro menor |
| 11–20 | **03** | Cavaleiro maior |
| 21–40 | **04** | Casa menor |
| 41–50 | **05** | Casa menor poderosa |
| 51–60 | **06** | Casa maior |
| 61–70 | **07** | Grande casa |

> **Por que o Status no nome da pasta:** ordena o diretório do reino por poder real sem abrir nada, e **muda quando a casa muda** — renomear a pasta é o registro visível de uma ascensão ou de uma queda. Quem renomeia deve anotar o motivo nas Notas de Desenvolvimento do `00-`.

**`[casa]`** — kebab-case, minúsculas, **sem acento e sem a palavra "casa"**: `atesata`, `corvanu`, `en-vallclara`.

### 2.3 Arquivos dentro da pasta

| Prefixo | O quê |
|:---:|---|
| **`00-[casa]`** | **A história.** Nome, divisa, brasão, introdução, os Eventos Históricos em prosa, e a penetração P1–P5. Um só por pasta |
| **`01-[casa]-holdings`** | ⭐ **Os números e a propriedade.** A tabela dos sete recursos com derivação completa, as faixas do livro, e as holdings declaradas com nome próprio. **Sempre o segundo, sempre existe** |
| **`02-`, `03-`, …** | Personagens, **em ordem decrescente de Status**. `02-` é sempre o de maior Status; empate desempata por idade |

Arquivos de apoio (brasão, mapa, árvore) usam o prefixo do documento a que pertencem: `00-atesata.png`, `02-fulano.png`.

> **Por que os holdings ficam fora do `00-`:** a história é para ler; os holdings são para **consultar em jogo**. Separar evita rolar por trinta parágrafos de prosa para achar quanto vale a Riqueza — e mantém o `00-` legível como texto.

---

## 3. Como se cria uma casa

Ordem obrigatória — os três primeiros passos geram números, os três últimos geram texto, e **o texto tem de explicar os números**.

| Passo | O quê | Onde |
|:-:|---|---|
| 1 | **Reino** — 3d6 na Tabela A ou escolha | [[01-house-and-lands-rules\|Regras · 01]] §2 |
| 2 | **Recursos** — 7d6 por recurso (ou fixe **25**) + modificadores de reino | [[01-house-and-lands-rules\|Regras · 01]] §3 |
| 3 | **Fundação** — 1d6 nas Seis Fundações; define quantos eventos | [[seis-fundacoes-history\|As Seis Fundações]] §3 |
| 4 | **Eventos** — 3d6 por evento, na ordem; **o 1º é a origem** | [[02-eventos-historicos\|Regras · 02]] §2 |
| 5 | **Retoques** — 1d6 por jogador, máx. dois por recurso | Cap. 6 |
| 6 | **Escrever** — `00-` (história), `01-` (holdings), depois os personagens | templates |

**Convenções desta campanha:**

- **Todo d6 de modificador de evento vale 4.** (`2d6` = 8 · `+6−2d6` = −2.) Ver [[02-eventos-historicos|Regras · 02]] §1.
- **Base fixa em vez de rolagem** — a média prática dos dados, arredondada para cima.
- Os eventos são distribuídos **proporcionalmente às janelas das Seis Fundações**, não em intervalos iguais.

### 3.1 A escala de dados ⭐

O Cap. 6 manda rolar **7d6** por recurso. Isso não é neutro: **7d6 é uma máquina de fabricar casa menor.**

| Status | Chance com 7d6 puro |
|:-:|---:|
| 2 | 0,04% |
| 3 | 19,1% |
| **4** | **80,8%** |
| 5 | 0,003% *(só 41 ou 42 — 8 combinações em 279.936)* |

Máximo possível de 7d6 = **42**. A faixa de Status 5 começa em 41. Uma casa que passe de Status 4 **passou por modificador, não por dado**.

### As duas escadas, e por que não coincidem ⭐

O livro tem uma regra de vassalagem — **casa jurada rola 2d6 a menos que a sua liege**. Ela **não** sobe um Status por degrau, e o motivo é geométrico:

> **A faixa de Status 4 vale 21–40 — vinte pontos. Todas as faixas acima valem dez.**

Como cada d6 rende 3,5, `+2d6` anda 7 pontos e `+3d6` anda 10,5. Logo:

| Dados | Média | Status modal | Distribuição |
|:-:|---:|:-:|---|
| 5d6 | 17,5 | **3** | St3 68% · St4 32% |
| **7d6** | **24,5** | **4** | St3 19% · St4 81% |
| 9d6 | 31,5 | **4** | St4 **95%** · St5 4% |
| 11d6 | 38,5 | **4** | St4 64% · St5 35% |
| **13d6** | **45,5** | **5** | St4 21% · St5 58% · St6 20% |
| 15d6 | 52,5 | **6** | St5 35% · St6 50% · St7 11% |
| 17d6 | 59,5 | **6** | St6 45% · St7 38% |
| **19d6** | **66,5** | **7** | St6 20% · St7 49% · St8 27% |
| 21d6 | 73,5 | **8** | St7 30% · St8 46% · St9 17% |
| 23d6 | 80,5 | **8–9** | St8 39% · St9 39% |
| 25d6 | 87,5 | **9** | St9 43% · St10 36% |

**As duas escadas medem coisas diferentes:**

- **`+2d6` = um degrau de vassalagem** — quanto uma liege supera quem lhe jura
- **`+3d6` = um degrau de Status** — a faixa do título

Elas não coincidem porque **"casa menor" absorve três degraus de vassalagem inteiros** (7d6, 9d6 e 11d6 são todos Status 4). É fiel ao original: cavaleiro pequeno, casa menor pequena e casa menor grande estão todos na mesma faixa, e a escada só morde acima dos 40.

### A escala canônica de Lorvenia

| Classe da casa | Dados | Base fixa | Status típico *(antes de modificadores)* |
|---|:---:|:---:|:---:|
| Casa jurada a uma casa menor | 5d6 | 18 | 3 |
| **Casa menor — a escala dos PCs** | **7d6** | **25** | **4** |
| Casa menor grande | 9d6 | 32 | 4 |
| Casa menor poderosa | 11d6 | 39 | 4–5 |
| **Casa maior** | **13d6** | **46** | **5** |
| Casa maior forte | 15d6 | 53 | 6 |
| **Grande casa** | **19d6** | **67** | **7** |
| Ducal · Warden | 21d6 | 74 | 8 |
| Casa do herdeiro | 23d6 | 81 | 9 |
| Coroa sem apoio de reino | 25–28d6 | 88–98 | 10 |

> ⭐ **A base escolhe-se pelo alvo final, não pela classe.** Some **reino + eventos** antes de decidir — e lembre que **o modificador de reino vale até duas faixas de Status sozinho** (+20 de Influência = dois degraus).
>
> **Exemplo canônico — a Casa do Almiratoru.** Base **13d6 / 46** (casa maior, escala modesta), mas em A Capital pelo perfil **A Coroa** (Influência +20) e com sete Eventos Históricos que somam +28 de Influência: **46 + 20 + 28 = 94 → Status 10.** Uma casa de escala 13d6 governando um império — porque o reino e a história fizeram o trabalho que os dados não fizeram. *Lá eles eram alguém; aqui são tudo, porque não sobrou mais ninguém.*

**As faixas acima de 70.** A tabela do livro para em 70 = Status 7, porque Westeros não tem imperador — lá o Status 8 vem do *título*, não do recurso. As Terras Além-Mar têm uma Coroa de verdade, então a escala continua de dez em dez:

| Influência | Status | Quem |
|:---:|:---:|---|
| 61–70 | 7 | Grande casa |
| 71–80 | 8 | Ducado · Warden |
| 81–90 | 9 | Casa do herdeiro |
| **91–100** | **10** | **O Imperatoru / a Imperatora** |

**Teto de 100.** Nenhum recurso passa de 100. Em escala imperial, várias colunas encostam no teto — e é isso que significa ser a Coroa.

---

## 4. O que vai em cada arquivo

### `00-[casa].md` — a casa

Segue [[house-template|Template de Casa Nobre]]:

| § | Conteúdo |
|:-:|---|
| **0** | Nome, Divisa e Brasão *(saem do **primeiro** evento)* |
| **1** | Breve Introdução — o que a casa é hoje e a contradição que a define |
| **2** | História — um bloco por Evento Histórico, na ordem |
| **3** | Recursos e Holdings — **só o resumo e o link** para o `01-` |
| **4** | **Personagens — só links.** A prosa mora nos arquivos `02-`, `03-`… |
| **Ap. A** | Penetração P1–P5 |
| **Ap. B** | Verificação |

### `01-[casa]-holdings.md` — os números e a propriedade

Segue [[holdings-template|Template de Holdings]]:

| § | Conteúdo |
|:-:|---|
| **1** | Recursos — derivação completa, leitura final, o que os eventos provaram |
| **2** | Interpretação — as faixas do livro |
| **3** | Holdings declaradas — sede, terras, poder, riqueza, o notável, **e o que a casa não tem** |

> ⭐ **Regra dura:** cada holding da §3 tem de **apontar para o Evento Histórico que a criou**. Se não aponta, ou o evento está faltando no `00-`, ou a holding está inventada.

### `02-[personagem].md` — cada personagem

Segue [[character-template|Template de Personagem]]: os três nomes, prosa em **História / Personalidade / Aparência** (formato do livro), ficha, e o apêndice **"O que sabe"** — quais níveis de penetração da casa este personagem conhece.

> ⭐ **Regra dura:** o **Status máximo** de qualquer personagem é o Status da casa (§2.2). Uma casa vasta e rica presa em Influência 20 **não produz ninguém acima de Status 3**, por mais notável que seja.

---

## 5. Convenções de escrita

- **Pt-BR.** Nomes próprios in-world em *itálico*.
- **Wikilinks** `[[nome-do-arquivo|texto]]` entre documentos. O alvo é o **basename sem extensão** (`[[00-atesata|Casa Atesáta]]`).
- ⭐ **Ortografia da Ordem.** Documentos de casa são documentos do mundo colonial: usam a grafia que o mundo realmente escreve — `qu`, `c`, `gu`, `nh`, `y` — e **nunca `k` nem `w`**, que não existem na *Litera Arvena*. Ver [[auecaui-conlang|Auecauí]] §3. A transcrição de gramático (com `k`/`w`) fica restrita aos documentos de língua e de mundo pré-contato; se ela aparecer num foral in-world, é falsificação, e isso é uma ferramenta de trama, não um descuido.
- Cabeçalho em **blockquote**, como no resto do repositório — nunca frontmatter YAML.
- ⚑ marca decisão em aberto · ⭐ marca o que carrega peso · ⚠️ marca conflito de canon.
- **Toda casa precisa de um P5 que refute a §1.** Se o segredo só acrescenta cor, está desperdiçado.

---

## 6. Índice de casas

| Reino | Casa | Status | Fundação | Em uma linha |
|---|---|:---:|:---:|---|
| A Capital — Ysaminguatú *(Venită)* | [[00-navanu\|**Navanu**]] · [[01-navanu-holdings\|holdings]] | **10** | **F0** | Os Almiratori. Armaram a frota que se perdeu e viraram a frota que se perdeu; governam por juramento, não por posse |
| A Escadaria e o Planalto | [[00-atesata\|**Atesáta**]] · [[01-atesata-holdings\|holdings]] | 5 | F1 | A casa mais antiga das Terras Além-Mar, fundada por um falsário, guardiã do único arquivo contínuo do mundo |

*Atualizar esta tabela sempre que uma casa for criada ou mudar de Status.*

---

## Notas de Desenvolvimento

- [x] Estrutura de pastas `[Reino]/[SS]-[casa]/[NN]-[doc].md`
- [x] Regra do Status no nome da pasta, derivado de Influência
- [x] Templates de casa, de holdings e de personagem separados
- [x] ⭐ Holdings movidos para o `01-`; personagens começam no `02-`
- [ ] Casas dos outros nove reinos
- [ ] Definir se casas extintas ficam em `_extintas/` ou mantêm a pasta com Status `00-`
- [ ] Armorial consolidado com todos os blazons — ver [[heraldica-blazon-referencia|Heráldica e Blasão]]

---

*Referências: [[01-house-and-lands-rules|Casas e Terras · 01: Os Reinos]] · [[02-eventos-historicos|· 02: Eventos Históricos]] · [[seis-fundacoes-history|As Seis Fundações]] · [[heraldica-blazon-referencia|Heráldica e Blasão]] · [[house-template|Template de Casa]] · [[holdings-template|Template de Holdings]] · [[character-template|Template de Personagem]]*
