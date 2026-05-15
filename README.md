<img src="./.github/dots.png" align="left" width="128px" height="128px"/>

## Pi Config
> *personal configuration for the Pi Coding Harness*

[pi.dev](https://pi.dev/) — [badlogic/pi-mono]

## "Custom" Extensions

#### From [badlogic/pi-mono]

- [`.pi/agent/extensions/handoff.ts`] - extract current session to a hand-off prompt and open it in a new session.
- [`.pi/agent/extensions/notify.ts`] - send desktop notifications when waiting for input

#### From [mitsuhiko/agent-stuff]

- [`.pi/agent/extensions/summarize.ts`] - summarize the current session/thread.

#### Personal

- [`.pi/agent/extensions/exa-websearch/`] - single Exa web/search contents tool with highlights-first results, deep search modes, summaries, and URL content retrieval.
    - Alternative, with no API Key required and [kepano/defuddle] sanitization: [thinkscape/agent-smart-fetch]
- [`.pi/agent/extensions/skill-autocomplete.ts`] - press `$` in the editor to open an autocomplete menu of loaded skills.

## Packages

https://pi.dev/packages

- [MasuRii/pi-permission-system] - permissions linked to [`.pi/agent/pi-permissions.jsonc`]
- [ayagmar/pi-extmgr] - UI for managing extensions.
- [nicobailon/pi-subagents] - Powerful sub-agent system with recursion and pipelining support
    - Alternatives: [tintinweb/pi-subagents] and [pasky/pi-side-agents]
- [pi-token-burden] - Claude-like context command with granular token counts per tool, mcp, etx
    - Alternatives: [pi-context]

## Acknowledgements

#### Feynman

The `research-*` agents and [agent/prompts/deepresearch.md] prompt are copied from [getcompanion-ai/feynman].

## Global Skills

[Agent Skills] located in `global-skills/` are less coding specific, thus designed for usage in other tools.

Intended usage of these is with GNU Stow:

```sh
stow --target $HOME global-skills
```

<!-- Reference Links -->

[`.pi/agent/extensions/handoff.ts`]: ./agent/extensions/handoff.ts
[`.pi/agent/extensions/notify.ts`]: ./agent/extensions/notify.ts
[`.pi/agent/extensions/summarize.ts`]: ./agent/extensions/summarize.ts
[`.pi/agent/pi-permissions.jsonc`]: ./agent/pi-permissions.jsonc
[`.pi/agent/extensions/exa-websearch/`]: ./agent/extensions/exa-websearch/
[`.pi/agent/extensions/skill-autocomplete.ts`]: ./agent/extensions/skill-autocomplete.ts
[`.pi/agent/prompts/deepresearch.md`]: ./agent/prompts/deepresearch.md

[badlogic/pi-mono]: https://github.com/badlogic/pi-mono
[mitsuhiko/agent-stuff]: https://github.com/mitsuhiko/agent-stuff
[MasuRii/pi-permission-system]: https://github.com/MasuRii/pi-permission-system
[ayagmar/pi-extmgr]: https://github.com/ayagmar/pi-extmgr
[nicobailon/pi-subagents]: https://github.com/nicobailon/pi-subagents
[pi-context]: https://github.com/ttttmr/pi-context
[pi-token-burden]: https://github.com/Whamp/pi-token-burden
[agent skills]: https://agentskills.io/home
[getcompanion-ai/feynman]: https://github.com/getcompanion-ai/feynman
[kepano/defuddle]: https://github.com/kepano/defuddle
[thinkscape/agent-smart-fetch]: https://github.com/Thinkscape/agent-smart-fetch


[tintinweb/pi-subagents]: https://x.com/nicht_tintin/status/2031119030224920979
[pasky/pi-side-agents]: https://x.com/xpasky/status/2028273594782855267
