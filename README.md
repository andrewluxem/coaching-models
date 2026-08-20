# coaching-models

Coaching helps another person examine a goal, the current reality, possible actions, and a chosen commitment. This skill prepares one GROW conversation, a longer coaching cycle, or an audit without scripting the coachee's answers.

It produces:

- **Coaching Session Prep** (A. Session prep): built from a development topic, supplied facts, and a desired outcome.
- **Coaching Cycle Plan** (B. Coaching cycle): built from a development outcome, practice opportunities, and review horizon.
- **Coaching Plan Audit** (C. Audit): built from an existing coaching plan or set of notes.

It executes the [Coaching Models playbook](https://www.andrewluxem.com/playbooks/coaching-models). The playbook teaches the framework. This skill runs it and returns a working artifact.

**Static by construction: no dependencies, executable code, telemetry, network calls, remote instructions, auto-update, scheduled work, or background behavior.** It reads only the files in its own skill folder. Nothing happens until a user or agent invokes it.

## Install

Clone and copy the skill into Claude Code:

```bash
git clone https://github.com/andrewluxem/coaching-models.git
cp -r coaching-models/skills/coaching-models ~/.claude/skills/
```

Or install it as a Claude Code plugin:

```text
/plugin marketplace add andrewluxem/coaching-models
/plugin install coaching-models@coaching-models
```

For clients that install from an archive, keep using the versioned [coaching-models v1.0.0 ZIP](https://www.andrewluxem.com/downloads/coaching-models-v1.0.0.zip).

## Invoke it

```text
Prep a coaching conversation for this situation
Prep a coaching conversation for a team member who wants to improve weekly
Build a coaching cycle from these notes. Communication needs work. There were a
```

Naming the skill is always valid: `use the coaching-models skill`.

## Files

```text
.claude-plugin/
  plugin.json
  marketplace.json
skills/coaching-models/
  SKILL.md
  meta.yaml
  LICENSE.md
  assets/
  references/
README.md
LICENSE
```

The complete canonical package is copied under `skills/coaching-models/`, including every asset, reference, example, and license file present in the source.

## Versioning

Plugin installation is version-pinned. When behavior changes, update the version consistently in `SKILL.md`, `meta.yaml`, and `.claude-plugin/plugin.json`, then add a changelog entry. Reinstalling is an explicit update; this repository never auto-updates itself.

## License

MIT. See [LICENSE](LICENSE). The canonical skill folder carries the same authorization in [skills/coaching-models/LICENSE.md](skills/coaching-models/LICENSE.md).

---

## More playbooks

This skill packages one playbook from the free library at [github.com/andrewluxem/playbooks](https://github.com/andrewluxem/playbooks). Every playbook is free to read, with no email required.
