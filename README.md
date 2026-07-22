# Viva Prep

[![Validate skill](https://github.com/khaichongwork/viva-prep/actions/workflows/validate.yml/badge.svg)](https://github.com/khaichongwork/viva-prep/actions/workflows/validate.yml)

An evidence-based Agent Skill for preparing and conducting a project viva using the student's real code, report, rubric, and runtime behavior.

## Use it for

- producing project-specific viva questions
- running an interactive mock viva one question at a time
- checking code tracing, concepts, design choices, and limitations
- identifying sections the student cannot yet explain confidently

## Install

Clone or copy this repository into:

```text
<project>/.agents/skills/viva-prep/
```

For GitHub Copilot project skills:

```text
<project>/.github/skills/viva-prep/
```

## Example prompt

```text
Use $viva-prep to run a mock viva using my actual Java project.
```

## Validate

```bash
python tests/validate_skill.py
```

## License

MIT
