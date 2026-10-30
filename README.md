# DataMining — task data for frontier models & agents

**Original, expert-authored task data for training and evaluating frontier models and agents.** Founded by PhD researchers from the School of Software, Peking University. Delivered to leading technology companies including ByteDance, Alibaba, and Tencent.

## What we build

| Line | What it covers | Difficulty evidence |
|---|---|---|
| **Coding** | Repo-level SWE, algorithm engineering, CLI reconstruction | GPT-5.6 Sol (xhigh), 4 attempts/task: DeepSWE-style 3 of 5 tasks never solved; Frontier SWE 1 of 4; ProgramBench (515 hidden tests) all ≤ 2/4 |
| **Reasoning** | HLE-style expert problems (math, physics, chemistry) | L3 band: authored beyond HLE difficulty; Pass@4 = 0 calibration |
| **Agents** | Long-horizon tool use, desktop automation, professional workflows | APEX-style tasks: frontier model scores 33–58%; TBS-style: 0/5 trials budget-exhausted |
| **Multimodal** | Figure- and screen-grounded expert reasoning | 8-problem cross-disciplinary booklet published in full |

Every task ships with a runnable verification environment. QA combines formal solvers (Z3/SymPy), multi-model cross-validation, and double-blind expert review. Difficulty is measured and published — see the [Frontier Task Difficulty Report 2026](https://www.datamining.cloud/en/reports/frontier-task-difficulty-2026.html).

## Repositories

- **[eval-task-examples](https://github.com/datamining-ai/eval-task-examples)** — example tasks with runnable verifiers, authoring guide, agent-environment checklist, and the public view of a real DeepSWE task.
- **[task-demo-highlights](https://github.com/datamining-ai/task-demo-highlights)** — model-visible sides of delivered demos: an 8-problem HLE-VL booklet, a full APEX-style workspace, TBS/Toolathlon/AutomationBench task briefs.

We publish the **model-visible side only** — hidden tests, rubrics, golden patches, and ground-truth workspaces stay private (they are the evaluation assets).

## Links

- Website: <https://www.datamining.cloud>
- Difficulty report: <https://www.datamining.cloud/en/reports/frontier-task-difficulty-2026.html>
- Delivered datasets overview: <https://www.datamining.cloud/en/datasets/>
- Contact: <contact@datamining.cloud>
