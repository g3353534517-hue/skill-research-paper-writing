# ML/AI Research Paper Writing Pipeline / ML/AI 论文写作流水线

![版本](https://img.shields.io/badge/版本-1.1.0-blue) ![分类](https://img.shields.io/badge/分类-研究-green) ![平台](https://img.shields.io/badge/平台-linux-lightgrey) ![平台](https://img.shields.io/badge/平台-macos-lightgrey)

## 项目简介

ML/AI 研究论文的端到端写作流水线——从实验设计到分析、起草、修订和投稿。覆盖 NeurIPS、ICML、ICLR、ACL、AAAI、COLM 等会议。集成自动实验监控、统计分析、迭代写作和引用验证。

## 功能特性

- Research Paper Writing Pipeline
- When To Use This Skill
- Core Philosophy
- Proactivity and Collaboration
- Phase 0: Project Setup
- Step 0.1: Explore the Repository
- Understand project structure
- Step 0.2: Organize the Workspace
- Step 0.3: Set Up Version Control
- Step 0.4: Identify the Contribution
- Step 0.5: Create a TODO List
- Step 0.6: Estimate Compute Budget
- Simple cost tracker pattern
- Step 0.7: Multi-Author Coordination
- Phase 1: Literature Review

## 环境要求

- 运行平台：linux, macos
- 依赖项：semanticscholar, arxiv, habanero, requests, scipy, numpy, matplotlib, SciencePlots

## 使用示例

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

## 文件结构

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

## 作者

Orchestra Research

## 许可证

MIT License

---

更多项目请访问：[github.com/g3353534517-hue?tab=repositories](https://github.com/g3353534517-hue?tab=repositories)
