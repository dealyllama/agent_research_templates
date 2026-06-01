# Research Skills

Hermes Agent skills for research workflows. These are live skills (symlinked or copied from `~/.hermes/skills/`) and can be version-controlled alongside the research templates.

## Skills

- **research-foundation** — System prompt blocks, citation standards, and 7 research tracks (Overview, Deep Dive, Comparison, Synthesis, Action, Fact-Check, Roadmap) with an interactive refinement workflow.
- **doublecheck** — Three-layer verification pipeline (Self-Audit, Source Verification, Adversarial Review) for catching hallucinations in AI output. Includes verification report template and agent definition.

## Usage

Load these skills in Hermes to standardize research prompting and verification across sessions.

```
# Load the foundation skill for any research task
skill_view(name='research-foundation')

# Load doublecheck for verification (can use a different model/context)
skill_view(name='doublecheck')
```

## Maintenance

Changes to skills should be made in `~/.hermes/skills/` and synced here, or vice versa. The `skills/` directory serves as a git-tracked backup and reference.