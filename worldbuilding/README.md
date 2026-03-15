# Worldbuilding — Aurelia

Estrutura para todo o conteúdo sobre o mundo de Aurelia.

## Pastas

| Pasta | Propósito |
|-------|-----------|
| **history** | Fatos — framework de consistência. Coisas que provavelmente nunca usaremos diretamente, mas servem de base para o mundo. |
| **culture** | Línguas, costumes, etnias. Descrições culturais do mundo. |
| **myths** | Lentes sobre a history — o que as pessoas *sabem* (ou acham que sabem). Podem ser verdadeiras, falsas ou contradizer umas às outras. Usar classificação de penetração. |

## Myths — Classificação de Penetração

Todo mito deve ter um nível de penetração que indica *quem* conhece essa informação no mundo.

| Nível | Código | Descrição |
|-------|--------|-----------|
| 1 | `P1` | **Todo mundo sabe** — conhecimento universal, parte do senso comum |
| 2 | `P2` | **Conhecimento comum** — a maioria das pessoas conhece |
| 3 | `P3` | **Conhecimento restrito** — grupos específicos (eruditos, clérigos, nobres) |
| 4 | `P4` | **Conhecimento secreto** — poucos guardiões, tradições orais, círculos fechados |
| 5 | `P5` | **Ninguém sabe** — perdido, esquecido ou nunca revelado |

### Uso no frontmatter

```yaml
---
penetration: P2
contradicts: ["[[Outro Mito]]"]
veracity: unknown  # true | false | unknown | partial
---
```
