# Deep Researcher

**An evidence-driven research skill for AI agents.**

Deep Researcher turns complex questions into structured investigations. It discovers relevant sources, evaluates evidence, verifies material claims, challenges conclusions, and synthesises findings into professional research reports.

## What It Does

Give the agent a research question in natural language. The skill determines the research scope, selects an appropriate investigation strategy, and carries out the work.

### Core Capabilities

- **Research planning:** Breaks complex questions into answerable subquestions and builds an investigation strategy.
- **Source discovery:** Prioritises primary sources, authoritative publications, original datasets, and relevant expert analysis.
- **Source evaluation:** Assesses authority, methodology, independence, recency, incentives, and limitations.
- **Claim verification:** Checks important claims against the underlying evidence, including quantitative definitions and original data.
- **Triangulation:** Compares independent evidence and identifies disagreements between sources.
- **Counterevidence:** Actively investigates competing explanations, criticism, and contradictory findings.
- **Synthesis:** Converts evidence into calibrated conclusions, with uncertainty and limitations made explicit.
- **Report generation:** Produces structured Microsoft Word (`.docx`) reports for substantial research tasks.

## Example Prompts

Use short, natural requests:

```text
Research whether AI agents are delivering measurable productivity improvements in businesses.
```

```text
Compare the leading open-source LLMs for production use.
```

```text
Investigate the economics of quick commerce in India.
```

```text
Evaluate the evidence behind the claim that intermittent fasting improves longevity.
```

```text
Prepare a literature review on foundation models for healthcare.
```

The skill adapts its research depth to the task:

| Mode | Purpose |
|---|---|
| Focused | Narrow questions requiring targeted verification |
| Comprehensive | Multi-source investigation and critical synthesis |
| Exhaustive | Deeper coverage for unusually broad or high-stakes research |

Comprehensive is the default.

## Research Principles

Deep Researcher is designed around several principles:

1. Evidence before conclusions.
2. Primary sources over derivative reporting.
3. Independent corroboration over raw source count.
4. Verification of important quantitative claims.
5. Active investigation of counterevidence.
6. Transparent treatment of uncertainty and limitations.
7. No fabricated sources, citations, quotations, or research activity.

## Deliverables

For substantial research, the default deliverable is a structured `.docx` report.

Reports are designed to include:
- Executive summary.
- Research question and scope.
- Evidence-based findings.
- Critical analysis and competing explanations.
- Quantitative findings where supported.
- Limitations and unresolved questions.
- Conclusions and implications.
- References and source map.

The report format adapts to the subject. A scientific literature review should not look like a market research report.

Simple factual questions do not trigger the full research workflow.

## Installation

### Personal installation

Clone the repository into your personal Codex skills directory:

```powershell
git clone https://github.com/AnshumanNigam/deep-researcher.git "$HOME\.agents\skills\deep-researcher"
```

### Project-level installation

Alternatively, clone it into your project's skills directory:

```powershell
git clone https://github.com/AnshumanNigam/deep-researcher.git ".agents/skills/deep-researcher"
```

Restart Codex if the skill does not appear automatically.

## Repository Structure

```text
deep-researcher/
├── SKILL.md
├── README.md
├── CHANGELOG.md
├── CONTRIBUTING.md
└── LICENSE
```

## Version

**Current version:** 1.0.0

**Status:** Experimental

The skill has undergone an instruction-level quality review. Further execution testing across different research domains is required.

## Contributing

Contributions, issue reports, and methodology improvements are welcome.

Read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a pull request.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
