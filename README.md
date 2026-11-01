# Alexander

Building agent tooling at Nankai University, and leaving a rollback path
in case it breaks.
南开在读，做 agent 工具链；顺手把回滚的路留好。

---

## About

I study at Nankai University. Most of my working time goes into agent
tooling: taking candidate changes from an agent, running them for real,
scoring them, keeping the evidence, and reverting whatever does not hold
up. The rest goes into transfer-learning experiments and algorithm
practice. I trust numbers over adjectives, and I try not to hand over
anything I cannot undo.

我在南开读书。大部分时间花在 agent 工具链上：把 agent 给出的候选改动
真的跑起来、打分、留证据，站不住的改动就回退。剩下的时间给迁移学习
实验和算法练习。我信数字不信形容词，也尽量不交出去没法撤销的东西。

---

## Selected work

**molt** — 自进化 agent 引擎，只做编排，不自带 agent 能力。
Self-evolving agent engine: orchestration only. Private for now, open-sourced
after bohack.

- 四件套 signal / action / verify / rollback：候选改动跑起来、打分、留证据、回退。
- 打分口径：成功率 > token > 耗时。

**flower** — 102 类花卉细粒度分类，ImageNet 预训练 ResNet-18 做两阶段微调。
Fine-grained 102-class flower classification on an ImageNet-pretrained ResNet-18.
The useful conclusion is that two-stage fine-tuning alone is what moves
55.46% to 92.50% top-1, with the backbone kept at ResNet-18.

- test top-1：55.46%（scratch）→ 81.27%（frozen）→ 92.50%（two-stage）。
- [FeiSaMa/flower](https://github.com/FeiSaMa/flower)

**algo** — LeetCode 解法 + 本地调试脚手架。
LeetCode solutions with a local harness, so a problem can be built and tested
in the terminal instead of the browser tab.

- `leetcode/`、`tests/`、`tools/newtest|build|run`。
- 每道题都能在本地建样例、编译、跑测。
- [FeiSaMa/algo](https://github.com/FeiSaMa/algo)

---

## Stack

`Python`  `C++`  `PyTorch`  `Linux`  `Arch Linux`  `niri`

---

## Tooling

Arch + niri + a self-built agent workflow. That is the whole setup, and it is
also where the repos above get written.
Arch + niri + 自建 agent 工作流，也是上面这些仓库的日常环境。

---

## Contact

Tianjin, Nankai University. Corrections, reproductions and pointed questions
are welcome through Issues / Discussions on the relevant repository.
天津，南开。纠错、复现和具体的问题，欢迎走对应仓库的 Issues / Discussions。
