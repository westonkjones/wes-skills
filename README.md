# wes-skills

Weston Jones's [Claude Code](https://claude.com/claude-code) plugin marketplace.

## Install

Add the marketplace once, then install the plugins you want:

```
claude plugin marketplace add westonkjones/wes-skills
claude plugin install weston-review@wes-skills
claude plugin install validation-plan@wes-skills
```

## Plugins

| Plugin | What it does |
|---|---|
| [weston-review](https://github.com/westonkjones/weston-review) | Adversarial multi-agent PR review. Focused reviewers, an independent verifier per finding, and a triage pass where you approve every comment before it posts. |
| [validation-plan](https://github.com/westonkjones/validation-plan) | Manual validation plans for finished changes: local setup, happy-path steps grounded in the code, and Playwright videos of UI scenarios. |

To pick up new versions, run `claude plugin marketplace update wes-skills`.
