# Agency Agents

Claude Code Subagents aus [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents) (MIT-Lizenz, siehe LICENSE).

Jede `.md`-Datei ist ein Subagent (Name und Beschreibung im YAML-Frontmatter) und wird von Claude Code
in diesem Projekt automatisch geladen. Aktivierung in einer Session z. B. mit:

```
Activate Frontend Developer and help me build a React component.
```

Aktualisieren:

```bash
git clone --depth 1 https://github.com/msitarzewski/agency-agents /tmp/agency-agents
/tmp/agency-agents/scripts/install.sh --tool claude-code --path .claude/agents --no-interactive --no-convert
```
