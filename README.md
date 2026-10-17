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
| [bouppteckning](skills/bouppteckning/SKILL.md) | Gör bouppteckningen efter ett dödsfall. Agenten reder ut vilka som ska kallas, räknar fram fristerna, går igenom tillgångar och skulder och förbereder blanketten och breven. Ni i dödsboet skriver under och skickar in själva. | Bouppteckning på papper med blanketten SKV 4600, enligt reglerna från 1 juli 2026. Inte arvskifte, dödsboets deklaration eller dödsbon med utländsk anknytning. |
| [reklamation](skills/reklamation/SKILL.md) | Reklamera en felaktig vara, ett digitalt innehåll eller en tjänst som du har köpt av ett företag, och anmäl tvisten till ARN om företaget säger nej. Agenten räknar ut frister och skriver utkast, men du skickar och betalar själv. | Konsumentköplagen, konsumenttjänstlagen och anmälan till ARN. Belopp för 2026. Inte köp mellan privatpersoner, resor eller flyg. |
| [andrahandsuthyrning](skills/andrahandsuthyrning/SKILL.md) | Hyr ut din bostad i andra hand eller din egen bostad, eller kontrollera hyran när du hyr i andra hand. Agenten hjälper dig att få samtycke eller tillstånd, räknar fram en laglig hyra och skriver kontraktet, men du skriver under och skickar själv. | Hyresrätt, bostadsrätt, hus och ägarlägenhet enligt reglerna från 1 juli 2026, med privatuthyrningslagen. Inte lokaler, företag eller semesteruthyrning. |

## Ingen juridisk rådgivning

Skills ger information och struktur, inte juridisk rådgivning. Kontrollera alltid mot källorna och ta hjälp av en jurist eller Skatteverket när mycket står på spel.

## Licens

[CC BY-NC-SA 4.0](LICENSE)
