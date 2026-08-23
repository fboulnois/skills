# Skills

A collection of custom AI skills for software engineering on production codebases. Built for the daily work of understanding and modifying existing systems.

## Installation

Point your favorite AI agent or harness at this repository and ask it to install the skills. For example:

```text
Install the skills from https://github.com/fboulnois/skills
```

If you only want a specific skill, point your agent at that skill's URL and ask it to install it. For example:

```text
Install the skill from https://github.com/fboulnois/skills/tree/main/improve-codebase
```

## Skills

### [`/improve-codebase`](./improve-codebase/SKILL.md)

Scans a codebase for codebase-wide improvement opportunities, presents them in a visual HTML report, and develops an implementation plan for whichever opportunity you choose.

Inspired by the `/improve-codebase-architecture` skill, but designed to take a broader and more flexible approach to improving codebases.

There were several aspects of the original skill that `/improve-codebase` approaches differently:

1. **Broader range of refactors:** Rather than focusing solely on architectural changes, `/improve-codebase` looks for codebase-wide opportunities involving both consistency across the codebase and clarity within individual pieces of code.
2. **Practical terminology:** Instead of framing improvements in design-theory jargon, `/improve-codebase` describes problems and proposed changes in clear, practical language, the way one developer would explain them to another.
3. **Flexible HTML reporting:** Rather than prescribing a rigid report structure, `/improve-codebase` defines what evidence and analysis the report should contain while letting the presentation adapt to the findings. Repeated analyses of the same codebase often surface different opportunities and perspectives across runs.
