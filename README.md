# Project Management

**Connect Claude to your project tracker and let it draft, file, and organize the work.** — built in-house by [Skill&nbsp;Me](https://skillme.dev).

Wire Claude directly into the tools your team plans in. This pack pairs official (and best-in-class community) MCP connectors for Notion, Jira/Confluence, Linear, Asana, ClickUp, monday.com, Airtable, and Trello with the authoring skills that make them sing - so Claude can draft a well-formed ticket and actually file it, design a database schema and build it, or set up a triage workflow and run it. Connectors authenticate via OAuth or a scoped token and act only within your existing permissions. Use when you want Claude to read, create, and move real work items instead of just talking about them.

⭐ **If this is useful, star the repo** — it's how we gauge what to build next.

## Install

- **From the catalog:** [skillme.dev/pack/project-management](https://skillme.dev/pack/project-management) — install the whole pack into Claude in one step.
- **With the skills CLI:** `npx skills add SkillMedev/project-management`
- **Manually:** copy any `skills/<slug>/SKILL.md` into your Claude skills directory.

## Skills in this pack

- **[Notion MCP](https://github.com/makenotion/notion-mcp-server)** — Connect Claude to Notion's official MCP server to read and write pages, query databases, search the workspace, and manage comments. _(external — see source)_
- **[Jira & Confluence MCP (Atlassian)](https://github.com/atlassian/atlassian-mcp-server)** — Connect Claude to Atlassian's official remote MCP server for Jira issues and Confluence pages via OAuth. _(external — see source)_
- **[Linear MCP](https://linear.app/docs/mcp)** — Connect Claude to Linear's official hosted MCP server to manage issues, projects, cycles, and teams via OAuth. _(external — see source)_
- **[Asana MCP](https://developers.asana.com/docs/using-asanas-mcp-server)** — Connect Claude to Asana's official MCP server to manage tasks, projects, workspaces, dependencies, and comments via OAuth. _(external — see source)_
- **[ClickUp MCP](https://developer.clickup.com/docs/connect-an-ai-assistant-to-clickups-mcp-server-1)** — Connect Claude to ClickUp's official MCP server to manage tasks, docs, time tracking, and project structure via OAuth. _(external — see source)_
- **[monday.com MCP](https://github.com/mondaycom/mcp)** — Connect Claude to monday.com's official MCP server to manage boards, items, and workflows via OAuth. _(external — see source)_
- **[Airtable MCP](https://github.com/domdomegg/airtable-mcp-server)** — Connect Claude to Airtable bases to read/write records, search, and inspect or edit schema. _(external — see source)_
- **[Trello MCP](https://github.com/delorenj/mcp-server-trello)** — Connect Claude to Trello boards, lists, cards, checklists, and comments. _(external — see source)_
- **[Jira Ticket Writer](skills/jira-ticket-writer/SKILL.md)** — Writes ready-to-build Jira stories with user-story summaries, Given/When/Then acceptance criteria, subtasks, and story-point guidance, checked against INVEST and a Definition of Ready.
- **[Linear Workflow](skills/linear-workflow/SKILL.md)** — Configures a Linear team end to end - team structure, minimal workflow states, cycles, a small label taxonomy, a daily triage rotation, and priority SLAs with breach views.
- **[Notion Database Designer](skills/notion-database/SKILL.md)** — Designs Notion databases that scale - one entity per database, deliberate property types, two-way relations with rollups, audience-specific views, and row templates - with explicit decision rules for relation vs rollup vs formula.

## License

MIT — see [LICENSE](LICENSE). Skills are portable `SKILL.md` files; the canonical
copies live in the [Skill&nbsp;Me catalog](https://skillme.dev).
