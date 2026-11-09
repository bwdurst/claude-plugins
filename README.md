# bwdurst Claude Code plugins

A Claude Code plugin marketplace for the skills I build and use every day.

```
/plugin marketplace add bwdurst/claude-plugins
/plugin install <name>@bwdurst
```

| Plugin | What it does |
|---|---|
| [agent-team](https://github.com/bwdurst/agent-team) | Six coding personas (Kira the lead, plus implementation, frontend, review, testing and architecture specialists) that share one set of instructions across Claude and Codex. Talk to Kira and she routes the work. |
| [rule-curator](https://github.com/bwdurst/rule-curator) | Audits every rule your agent runs under (CLAUDE.md files, memory, AGENTS.md, ADRs) against the whole set, flags the stale, duplicated and conflicting ones, and gives you a browser UI to keep, drop or rewrite each. |
| [waiting-on-me](https://github.com/bwdurst/waiting-on-me) | Finds every session waiting on you across all projects (questions, decisions, stuck permission prompts), collects your answers in one pass, and sends each back to the session that asked. |

Each plugin also installs with the [skills](https://skills.sh) installer for Claude Code, Codex and other agents:

```bash
npx skills add bwdurst/<name>
```

## Also

[agent-tts](https://github.com/bwdurst/agent-tts) is a Windows app, not a plugin, that reads Claude Code and Codex replies aloud with a separate voice per agent. It pairs with agent-team, whose personas start spoken lines with their name.

## License

Each plugin carries its own MIT license in its repository.
