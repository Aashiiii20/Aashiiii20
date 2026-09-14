# short-drama-toolkit

A Claude Code plugin that bundles the **short-drama-series-writer** skill: a full-process
short-drama scriptwriting assistant that takes a project from topic selection through a
complete 50–100 episode script package (character design, pacing hooks, paywall beats,
episode outlines, single-episode drafting, quality review, compliance checks, and export).

Supports domestic vertical-screen drama formats as well as overseas formats
(ReelShort / DramaBox), across genres such as god-of-war, baby-genius, comeback,
sweet-love, and revenge.

## Contents

```
short-drama-toolkit/
├── .claude-plugin/
│   └── plugin.json
├── README.md
└── skills/
    └── short-drama-series-writer/
        ├── SKILL.md
        ├── README.md          # original skill documentation (Chinese)
        ├── LICENSE             # original MIT license
        ├── meta.yaml
        └── references/         # 8 reference docs (genre guide, hook design,
                                 # rhythm curve, paywall design, satisfaction
                                 # matrix, villain design, opening rules,
                                 # compliance checklist)
```

## Installing

From a Claude Code session:

```
/plugin marketplace add aashiiii20/aashiiii20
/plugin install short-drama-toolkit
```

Or point directly at this plugin directory if you've cloned the repo locally.

## Usage

Once installed, the skill triggers automatically on prompts like "write a short drama",
"vertical drama script", "episode outline", or "ReelShort script" — or drive it through
its command-style workflow (`/start`, `/plan`, `/characters`, `/outline`, `/episode N`,
`/review N`, `/compliance`, `/export`, `/overseas`). See
`skills/short-drama-series-writer/README.md` for the full command reference.

## Attribution

The bundled skill is authored by **0xsline / MiniMax Hub** and distributed under the
[MIT License](skills/short-drama-series-writer/LICENSE) (see that file for the full
notice). It is repackaged here unmodified as a Claude Code plugin skill.
