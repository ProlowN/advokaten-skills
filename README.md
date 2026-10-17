# Advokaten skills

Agent skills som ger din AI-agent kunskap om svensk vardagsjuridik. Katalogen finns på [advokaten.ai](https://advokaten.ai).

## Installera

```bash
npx skills add ProlowN/advokaten-skills --skill inkomstdeklaration
```

Utan `--skill` får du välja bland alla skills. Du behöver Node.js 22.20 eller senare och en agent som stöder Agent Skills, till exempel Claude Code, Codex eller Cursor.

## Skills

| Skill | Beskrivning | Täcker just nu |
|---|---|---|
| [inkomstdeklaration](skills/inkomstdeklaration/SKILL.md) | Granska och fyll i Inkomstdeklaration 1. Agenten läser den förifyllda deklarationen, frågar om avdrag och kan fylla i e-tjänsten, men du skriver alltid under själv. | Punkt 1–3: lön, pension, resor och andra avdrag i tjänst. Inkomståret 2025. |

## Ingen juridisk rådgivning

Skills ger information och struktur, inte juridisk rådgivning. Kontrollera alltid mot källorna och ta hjälp av en jurist eller Skatteverket när mycket står på spel.

## Licens

[CC BY-NC-SA 4.0](LICENSE)
