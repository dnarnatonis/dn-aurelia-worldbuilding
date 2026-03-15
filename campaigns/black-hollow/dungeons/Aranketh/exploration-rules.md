---
tags: [campaign, dungeon, black-hollow, hexcrawl, rules]
campaign: "[[Black Hollow]]"
location: "[[city-of-the-gods|Aran'keth]]"
---

# Regras de Exploração — Aran'keth

Aran'keth funciona como um **megadungeon urbano em hexcrawl**. Toda exploração é medida em **turnos de 10 minutos**.

Base: [[PHB-01-10-Exploration|PHB 01-10]] (Travel Pace) + [[DMG-02-07-Running-Exploration|DMG 02-07]] (hexcrawl, Journey Stages).

---

## Mapa Hexcrawl

| Parâmetro | Valor |
|-----------|-------|
| Escala | 1 hex = 3000 ft (0.5 mile, ~900 m) |
| Grid | 11×11 hexes (121 total) |
| Hexes com conteúdo | ~25–30 |
| Restante | Ruínas exploráveis (descobertas menores) |
| Movimento | Normal: 1 hex/turno. Fast: 2 hexes. Slow: ½ hex. |

**Base:** Normal pace = 1 hex per turno (10 min). A cidade usa multiplicadores simplificados: Fast = 2×, Slow = ½×.

| Pace   | Movimento por turno | Tempo por hex | WIS (Perception/Survival) | DEX (Stealth) |
|--------|---------------------|---------------|---------------------------|---------------|
| Fast   | 2 hexes             | 5 min         | Desvantagem               | Desvantagem   |
| Normal | 1 hex               | 10 min        | —                         | Desvantagem   |
| Slow   | ½ hex               | 20 min        | Vantagem                  | —             |

_Regra da cidade: Fast = dobro de movimento, Slow = metade. O turno base permanece 10 min._

### Modificadores por terreno

O tipo de hex afeta o movimento. Os valores da tabela acima são para **hexes normais** (ruas, quarteirões, ruínas).

| Terreno | Modificador | Exemplos |
|---------|-------------|----------|
| **Hex normal** | base | Ruas, templos menores, ruínas, city blocks |
| **Grande estrada** | 2× | Vias principais — movimento dobrado |
| **Hex especial** | ½× | Desníveis, rios (quadrante verdejante) — movimento pela metade |

Ao cruzar hexes de tipos diferentes no mesmo turno, aplique o modificador do hex de **destino** (ou do mais restritivo, a critério do DM).

> **PHB 01-10 — Travel Pace (verbatim)**  
> Each travel pace has a game effect, as defined below.
>
> **Fast.** Traveling at a Fast pace imposes Disadvantage on a traveler's Wisdom (Perception or Survival) and Dexterity (Stealth) checks.
>
> **Normal.** Traveling at a Normal pace imposes Disadvantage on Dexterity (Stealth) checks.
>
> **Slow.** Traveling at a Slow pace grants Advantage on Wisdom (Perception or Survival) checks.

---

## Visão e Iluminação

A cidade é iluminada por uma **luz esverdeada** que permeia todo o lugar — **Dim Light**.

> **PHB 01-10 — Light (verbatim)**  
> **Dim Light.** Dim Light, also called shadows, creates a Lightly Obscured area. An area of Dim Light is usually a boundary between Bright Light and surrounding Darkness.  
> *In a Lightly Obscured area, you have Disadvantage on Wisdom (Perception) checks that rely on sight.*

### Alcance da visão por tipo de hex

| Contexto | Alcance | O que se vê |
|---------|---------|-------------|
| **Hexes normais** | 1 hex | Ruas, quarteirões, templos menores, ruínas — apenas hex adjacente |
| **Grandes estradas** | 3 hexes | Visão ao longo da via principal |
| **Construções grandes** | 3 hexes | Templos principais, torres, estruturas altas — visíveis a ±3 hexes |
| **Torres de Obsidiana** | 6 hexes | As colunas centrais são visíveis de quase toda a cidade |

Creatures com **Darkvision** ignoram a penalidade de Dim Light para visão, mas a cidade continua Lightly Obscured para efeitos de alcance (não aumenta o número de hexes visíveis).

---

## Turno de Exploração

Em cada turno de 10 minutos, o grupo pode fazer **uma** ação:

- **Mover** — conforme pace e terreno (hex normal: Fast 2, Normal 1, Slow ½; grande estrada: 2×; hex especial: ½×)
- **Explorar** um local de interesse
- **Investigar** uma ruína menor
- **Interagir** com NPC ou facção
- **Realizar ritual** ou ação especial
- **Descanso curto** (consome 6 turnos = 1 hora)

Após cada turno: o tempo avança e eventos podem ser acionados.

---

## Locais de Interesse

Três níveis de conteúdo nos hexes:

### Grandes Marcos (8)

Os oito templos/locais divinos. Mini-dungeons com mapa próprio.

Contêm: chefes, peças de selamento, segredos profundos.

→ Ver detalhes em `aranketh.md`

### Locais Intermediários (12–16)

Exploração menor, sem mapa completo.

Exemplos: bibliotecas destruídas, criptas, quartéis cultistas, jardins corrompidos, máquinas divinas quebradas.

Oferecem: recursos, pistas, encontros.

### Descobertas Menores (10–15)

Encontradas em hexes "vazios":

Exemplos: estátuas antigas, inscrições, fantasmas eco, artefatos menores.

Função: atmosfera e lore incremental.

---

## Tabela de Eventos

A cada **2–3 turnos**, role 1d8:

| d8 | Evento |
|----|--------|
| 1 | Patrulha cultista |
| 2 | Eco temporal (visão do passado) |
| 3 | Visão do aboleth (WIS save) |
| 4 | Fantasma antigo (informação ou perigo) |
| 5 | Colapso estrutural (DEX save) |
| 6 | Conflito entre facções cultistas |
| 7 | Sussurros psíquicos (INT save ou pista) |
| 8 | Nada acontece |

---

## Sistema de Corrupção

A influência do **Whisperer in the Dark** cresce com o tempo de permanência.

A cada **1 hora de exploração** (6 turnos), role na tabela de corrupção:

| d6 | Efeito |
|----|--------|
| 1 | Sussurros na mente — disadvantage em próximo WIS save |
| 2 | Memória falsa — DM insere informação incorreta |
| 3 | Mutação menor — efeito cosmético temporário |
| 4 | Cultistas alertados — próximo encontro com vantagem inimiga |
| 5 | Visão profética — pista real, mas perturbadora |
| 6 | Sem efeito |

Isso cria **pressão temporal**: quanto mais tempo na cidade, maior o risco.

---

## Facções Ativas

Cada distrito é dominado por uma facção cultista derivada da fé original corrompida:

| Facção | Distrito | Base | Ver |
|--------|----------|------|-----|
| Facção da Forja (Elemental) | Ordem e Pedra | Forja Titânica | `backstory.md` |
| Facção da Passagem (Death) | Morte e Sombras | Necrópole Inferior | `backstory.md` |
| Facção do Sussurro (Aberrant) | Morte e Sombras | Torre do Véu | `backstory.md` |
| Facção Infernal (Fiend) | Ordem e Pedra | Hall do Julgamento | `backstory.md` |

As facções:
- Patrulham seus territórios
- Disputam fronteiras entre distritos
- Reagem à presença e ações dos jogadores
- Podem ser manipuladas umas contra as outras

---

## Descanso

| Tipo | Custo | Condição |
|------|-------|----------|
| **Short rest** | 6 turnos (1h) | Possível em hex seguro |
| **Long rest** | Requer sair da cidade ou local muito seguro | Role corrupção ao descansar dentro da cidade |

---

## Referências

- [[aranketh|Overview do dungeon]]
- `hex-key.md` — chave de hexes
