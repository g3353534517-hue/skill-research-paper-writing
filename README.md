# ML/AI 论文写作流水线 / ML/AI Research Paper Writing Pipeline

![版本](https://img.shields.io/badge/版本-1.1.0-blue) ![分类](https://img.shields.io/badge/分类-研究-green) ![平台](https://img.shields.io/badge/平台-linux-lightgrey) ![平台](https://img.shields.io/badge/平台-macos-lightgrey)

## 简介 / Overview

End-to-end pipeline for writing ML/AI research papers — from experiment design through analysis, drafting, revision, and submission. Covers NeurIPS, ICML, ICLR, ACL, AAAI, COLM. Integrates automated experiment monitoring, statistical analysis, iterative writing, and citation verification.

## 详细说明 / Details

End-to-end pipeline for producing publication-ready ML/AI research papers targeting **NeurIPS, ICML, ICLR, ACL, AAAI, and COLM**. This skill covers the full research lifecycle: experiment design, execution, monitoring, analysis, paper writing, review, revision, and submission.

This is **not a linear pipeline** — it is an iterative loop. Results trigger new experiments. Reviews trigger new analysis. The agent must handle these feedback loops.

```
┌─────────────────────────────────────────────────────────────┐
│                    RESEARCH PAPER PIPELINE                  │
│                                                             │
│  Phase 0: Project Setup ──► Phase 1: Literature Review      │
│       │                          │                          │
│       ▼                   ...

## 功能特性 / Features

- Research Paper Writing Pipeline
- When To Use This Skill
- Core Philosophy
- Phase 0: Project Setup
- Understand project structure
- Simple cost tracker pattern
- Phase 1: Literature Review
- Via terminal:
- Via web_search:
- Via web_extract (for specific papers):

## 环境要求 / Prerequisites

- 平台：linux, macos
- 依赖：semanticscholar, arxiv, habanero, requests, scipy, numpy, matplotlib, SciencePlots

## 使用示例 / Usage Examples

```
┌─────────────────────────────────────────────────────────────┐
│                    RESEARCH PAPER PIPELINE                  │
│                                                             │
│  Phase 0: Project Setup ──► Phase 1: Literature Review      │
│       │                          │                          │
│       ▼                          ▼                          │
│  Phase 2: Expe
...
```

```bash
# Understand project structure
ls -la
find . -name "*.py" | head -30
find . -name "*.md" -o -name "*.txt" | xargs grep -l -i "result\|conclusion\|finding"
```

```
workspace/
  paper/               # LaTeX source, figures, compiled PDFs
  experiments/         # Experiment runner scripts
  code/                # Core method implementation
  results/             # Raw experiment results (auto-generated)
  tasks/               # Task/benchmark definitions
  human_eval/          # Human evaluation materials (if needed)
```

## 文件结构 / File Structure

```
SKILL.md
references/autoreason-methodology.md
references/checklists.md
references/citation-workflow.md
references/experiment-patterns.md
references/human-evaluation.md
references/paper-types.md
references/reviewer-guidelines.md
references/sources.md
references/writing-guide.md
templates/README.md
templates/aaai2026/README.md
templates/aaai2026/aaai2026-unified-supp.tex
templates/aaai2026/aaai2026-unified-template.tex
templates/aaai2026/aaai2026.bib
templates/aaai2026/aaai2026.bst
templates/aaai2026/aaai2026.sty
templates/acl/README.md
templates/acl/acl.sty
templates/acl/acl_latex.tex
templates/acl/acl_lualatex.tex
templates/acl/acl_natbib.bst
templates/acl/anthology.bib.txt
templates/acl/custom.bib
templates/acl/formatting.md
templates/colm2025/README.md
templates/colm2025/colm2025_conference.bib
templates/colm2025/colm2025_conference.bst
templates/colm2025/colm2025_conference.pdf
templates/colm2025/colm2025_conference.sty
templates/colm2025/colm2025_conference.tex
templates/colm2025/fancyhdr.sty
templates/colm2025/math_commands.tex
templates/colm2025/natbib.sty
templates/iclr2026/fancyhdr.sty
templates/iclr2026/iclr2026_conference.bib
templates/iclr2026/iclr2026_conference.bst
templates/iclr2026/iclr2026_conference.pdf
templates/iclr2026/iclr2026_conference.sty
templates/iclr2026/iclr2026_conference.tex
templates/iclr2026/math_commands.tex
templates/iclr2026/natbib.sty
templates/icml2026/algorithm.sty
templates/icml2026/algorithmic.sty
templates/icml2026/example_paper.bib
templates/icml2026/example_paper.pdf
templates/icml2026/example_paper.tex
templates/icml2026/fancyhdr.sty
templates/icml2026/icml2026.bst
templates/icml2026/icml2026.sty
templates/icml2026/icml_numpapers.pdf
templates/neurips2025/Makefile
templates/neurips2025/extra_pkgs.tex
templates/neurips2025/main.tex
templates/neurips2025/neurips.sty
```

## 相关技能 / Related Skills

- [skill-arxiv](https://github.com/g3353534517-hue/skill-arxiv)
- [skill-ml-paper-writing](https://github.com/g3353534517-hue/skill-ml-paper-writing)
- [skill-subagent-driven-development](https://github.com/g3353534517-hue/skill-subagent-driven-development)
- [skill-plan](https://github.com/g3353534517-hue/skill-plan)

## 作者 / Author

Orchestra Research

## 许可证 / License

MIT License

---

更多技能请访问：[github.com/g3353534517-hue?tab=repositories](https://github.com/g3353534517-hue?tab=repositories)
