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
| Movimento | 1 hex = 1 turno (10 min) em **Normal pace** |

**Cálculo:** PHB Normal pace = 300 ft/min → 3000 ft ÷ 300 = 10 min. A cidade cobre ~5.5 miles por lado (~30 sq miles).

| Pace   | Velocidade | Tempo por Hex | WIS (Perception/Survival) | DEX (Stealth) |
|--------|------------|---------------|---------------------------|---------------|
| Fast   | 400 ft/min  | ~7.5 min      | Desvantagem               | Desvantagem   |
| Normal | 300 ft/min  | 10 min        | —                         | Desvantagem   |
| Slow   | 200 ft/min  | 15 min        | Vantagem                  | —             |

> **PHB 01-10 — Travel Pace (verbatim)**  
> Each travel pace has a game effect, as defined below.
>
> **Fast.** Traveling at a Fast pace imposes Disadvantage on a traveler's Wisdom (Perception or Survival) and Dexterity (Stealth) checks.
>
> **Normal.** Traveling at a Normal pace imposes Disadvantage on Dexterity (Stealth) checks.
>
> **Slow.** Traveling at a Slow pace grants Advantage on Wisdom (Perception or Survival) checks.

---

## Turno de Exploração

Em cada turno de 10 minutos, o grupo pode fazer **uma** ação:

- **Mover** para um hex adjacente
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

| Facção | Distrito | Interpretação |
|--------|----------|---------------|
| Culto Estelar | Fogo e Céu | O aboleth é um deus do destino |
| Culto da Vida Corrupta | Vida e Natureza | O aboleth oferece evolução |
| Culto Necromântico | Morte e Sombras | O aboleth domina a morte |
| Culto da Ordem Fanática | Ordem e Pedra | O aboleth é a lei suprema |

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
