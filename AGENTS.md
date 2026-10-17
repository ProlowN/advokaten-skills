# AGENTS.md – Advokaten skills

Agent skills för svensk vardagsjuridik, installerbara med `npx skills add ProlowN/advokaten-skills`.

## Struktur

```
skills/<namn>/
  SKILL.md          # arbetsgång, under 500 rader
  references/       # detaljer som agenten läser vid behov
```

- `name` i SKILL.md: a–z, 0–9 och bindestreck, högst 64 tecken, samma som mappnamnet.
- `description`: högst 1024 tecken. Säg vad skillen gör och när den ska användas.
- Övriga fält under `metadata:` som text, till exempel `title` och `version`.
- Allt innehåll på svenska.
- Kontrollera att skillen hittas: `npx skills add . --list`.

## Innehåll

- Varje regel och belopp ska ha en källa (Skatteverket, lag eller myndighet). Skriv aldrig belopp eller regler från minnet.
- Belopp och datum som ändras mellan åren ligger i en årsfil, till exempel `references/inkomstar-2025.md`. Övriga filer hänvisar dit.
- Skills ska aldrig låta agenten skriva under, skicka in eller betala något åt användaren.
- Håll det enkelt: skriv det agenten behöver för att fråga rätt, räkna rätt och fylla i rätt.

## Underhåll

Se [UNDERHALL.md](UNDERHALL.md) för vad som ska uppdateras varje år.
