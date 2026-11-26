# av-pro-skills

Claude Agent Skills for AV design, documentation, verification and project
delivery. Not control-system code generation. Each skill packages real AV
domain content (checklists, templates, reference tables) so Claude produces
deliverables an AV project engineer would actually hand to a client or GC.

## Install

```
claude plugin marketplace add AVjarboe/av-pro-skills
claude plugin install av-pro-skills@av-pro-skills
```

## Skills

| Skill | What it produces | Status |
|---|---|---|
| `av-sow-writer` | Scope of work with inclusions, exclusions, clarifications and a responsibilities matrix | planned |
| `av-commissioning-report` | Verification report with pass/fail table, deficiencies and sign-off | planned |
| `av-design-peer-review` | Checklist-driven design review memo | on hold |
| `div27-spec-writer` | CSI MasterFormat-style Division 27 section | planned |
| `av-bom-to-rack-and-io` | Rack elevation table and I/O schedule from an equipment list | planned |

## Disclaimer

Output is a drafting aid. Review every document before issuing it. Not a
substitute for a qualified professional's judgment. AVIXA standards are cited
by number only; no standards text is reproduced.

## License

MIT. See `LICENSE`.
