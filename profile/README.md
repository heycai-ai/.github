# HeyCAi

> HeyCAi is an AI receptionist for health clinics: it answers calls and WhatsApp messages and books appointments in the clinic's practice software.
>
> HeyCAi es una recepcionista con IA para clínicas de salud: contesta las llamadas y los mensajes de WhatsApp y reserva las citas en el programa de gestión de la clínica.

CAi, HeyCAi's assistant, works in English and Spanish and books into PracticeHub, QuiroHiro, Cliniko, Jane App or Google Calendar. More than 30 clinics already work with HeyCAi.

This organization publishes HeyCAi's open-source work for the people who build, market and run health clinics of any specialty.

## Agent skills

[`heycai-ai/skills`](https://github.com/heycai-ai/skills) holds two MIT-licensed agent skills for Claude Code, Cursor, Codex and the other agents that read `SKILL.md`, in English and Spanish:

| Skill | What it does |
| --- | --- |
| [`clinic-front-desk-audit`](https://github.com/heycai-ai/skills/tree/main/skills/clinic-front-desk-audit) | Estimates the revenue a clinic loses each month to missed calls, slow WhatsApp replies and no-shows, from the clinic's own figures, and ranks what to fix first. |
| [`clinic-website-ai-search`](https://github.com/heycai-ai/skills/tree/main/skills/clinic-website-ai-search) | Audits a clinic's website for Google and AI search engines and gives each fix with the page that shows it and the code. |

Install both from GitHub:

```sh
npx skills add heycai-ai/skills
```

or from the HeyCAi website, which serves the same skills at `/.well-known/agent-skills/`:

```sh
npx skills add https://heycai.ai
```

The skills are also on skills.sh: [clinic-front-desk-audit](https://www.skills.sh/heycai-ai/skills/clinic-front-desk-audit) and [clinic-website-ai-search](https://www.skills.sh/heycai-ai/skills/clinic-website-ai-search).

## Links

- Website: https://www.heycai.ai
- In Spanish: https://www.heycai.ai/es
- For AI assistants: https://www.heycai.ai/llms.txt
- Agent skills catalog: https://www.heycai.ai/.well-known/agent-skills/index.json
- Contact: hey@heycai.ai
