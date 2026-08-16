# Money OS — Setup

1. Install Claude Code if you haven't already.
2. Unzip this folder (or move it) so it's your working directory, e.g. `money-os/`.
3. Open a terminal in that folder and run:
   ```
   claude
   ```
4. Claude Code will read `CLAUDE.md` automatically as project instructions.
5. Review and edit `memory/interests.md` — it's pre-filled with a best guess based on known background. Correct/expand it before your first scan, especially the "Offene Fragen" (open questions) at the bottom.
6. Make sure web search is enabled in Claude Code so the Scout and Researcher agents can actually cite sources.
7. Run your first scan:
   ```
   Run my morning scan
   ```

## Folder structure
```
money-os/
├── CLAUDE.md                  # master orchestrator instructions
├── .claude/agents/
│   ├── scout.md
│   ├── researcher.md
│   ├── validator.md
│   ├── strategist.md
│   └── builder.md
├── memory/
│   ├── interests.md            # pre-filled — review before first run
│   ├── discoveries.md          # log of everything found (grows over time)
│   └── results.md              # log of what was actually tried
└── opportunities/               # each candidate gets its own file here
```

## Daily habit
End each session with: **"Save today's findings to memory."**
