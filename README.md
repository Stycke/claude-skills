# claude-skills

Min samling af Claude Skills. Hver mappe under `skills/` er én selvstændig skill med sin egen `SKILL.md`.

## Indhold

| Skill | Hvad den gør | Oprindelse | Licens |
|---|---|---|---|
| `ai-seo` | Optimering af indhold til AI-søgemaskiner (AEO/GEO), så det bliver citeret af LLM'er | coreyhaines31/marketingskills | MIT |
| `cold-email` | B2B cold outreach — sekvenser, opfølgning, deliverability | alirezarezvani/claude-skills | MIT |
| `content-creation` | Marketingindhold på tværs af kanaler: blog, social, nyhedsbrev, landingsside | Anthropic Knowledge-Work | Apache-2.0 |
| `copywriting` | Skrive og forbedre marketing-copy til sider: forside, landingsside, pris, produkt | alirezarezvani/claude-skills | MIT |
| `hhx-skolelaerer` | HHX-lærer til skoleopgaver i alle fag — faglige mål og bedømmelseskriterier | Egen | — |
| `linkedin` | Publicering og styring af LinkedIn-indhold via Hyper MCP | hyperfx-ai/marketing-skills | MIT |
| `marketing-psychology` | 70+ mentale modeller og adfærdsvidenskab anvendt på marketing | alirezarezvani/claude-skills | MIT |
| `programmatic-seo` | SEO-sider i skala via templates og data | alirezarezvani/claude-skills | MIT |
| `risk-management-specialist` | Risikostyring for medicinsk udstyr efter ISO 14971 (FMEA, fejltræsanalyse) | alirezarezvani/claude-skills | MIT |
| `social-media-content-repurposer` | Genbrug indhold på tværs af platforme (blog → tråd, artikel → LinkedIn-opslag) | OneWave-AI/claude-skills | MIT |

## Struktur

```
skills/<navn>/
├── SKILL.md          # instruktionerne — det Claude læser
├── references/       # baggrundsmateriale skillen kan slå op i
├── scripts/          # hjælpescripts (Python)
├── LICENSE           # original licens
└── NOTICE.txt        # kilde og licensoplysninger
```

## Licenser

Ni af de ti skills er tredjepartsmateriale, videredistribueret under deres oprindelige licens.
Original copyright og licenstekst er bevaret i hver mappe (`LICENSE` + `NOTICE.txt`).
`hhx-skolelaerer` er mit eget.

## Brug

En skill installeres ved at lægge mappen ind i Claudes skills-mappe. `SKILL.md`'s
`description`-felt afgør hvornår Claude selv aktiverer den, så det felt er værd at
finjustere hvis en skill trigger for tidligt eller for sent.
