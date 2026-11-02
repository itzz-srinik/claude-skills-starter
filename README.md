# claude-skills-starter# claude-skills-starter

A small collection of reusable Claude Skills. Each skill is a folder
with a `SKILL.md` file that tells Claude how to handle one kind of task.

## Skills
| Skill | What it does |
|---|---|
| `code-reviewer` | Structured code review: bugs, security, readability |
| `meeting-notes` | Turns messy notes into decisions and action items |
| `study-notes` | Builds study notes and practice questions |

## Use
1. Download the skill folder you want.
2. Add it as a custom skill in Claude's settings.
3. Ask Claude for a matching task, and it will follow the skill.

## Add your own
Create `skills/your-skill/SKILL.md` with a `name` and `description`
at the top, followed by plain-language instructions.
