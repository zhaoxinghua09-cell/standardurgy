---
name: standardurgy
description: "Use when creating or escalating a standard, specification, or judgment-tier claim (L0-L4). 当需要创造或升级标准、规范或判据分层主张（L0-L4）时使用。"
license: apache-2.0
type: term-registration
namespace: lgd.terms
version: v1.1
registered_at: 2026-10-15
doi: https://doi.org/10.5281/zenodo.23385209
family: meta-layer-creation
related: [lgd-doctrine]
---

[![LGD 82/100](docs/lgd-main.svg)](https://github.com/zhaoxinghua09-cell/standardurgy) [![四角度](docs/lgd-angles.svg)](https://github.com/zhaoxinghua09-cell/standardurgy)
[![License: Apache-2.0](https://img.shields.io/badge/License-Apache--2.0-yellow.svg)](LICENSE)
[![LLM index](https://img.shields.io/badge/llms.txt-ready-blue.svg)](llms.txt)
[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.23385209-0078d4.svg)](https://doi.org/10.5281/zenodo.23385209)


# Standardurgy · 标准工程术

**这是什么**：把“制定或升级一个标准、规范、分层判据”的过程写成可执行流程——从 L0 术语登记到 L4 判据分层，每一步都留下可核验的产物。

**给谁用**：要把内部经验升级成对外可引用标准的团队；以及需要判断一份“标准”是否站得住的外部读者。

**不是什么**：不是标准目录，也不是评级机构。它不认证任何第三方产物，只公开自己这套流程产出的文稿、检查项和证据。

**English** — a step-by-step procedure for creating or escalating a standard, specification, or tiered judgment claim (L0–L4), producing a checkable artifact at each step. It is not a registry and not a rating body; it certifies nothing outside its own artifacts.

![LGD score](badge.svg "LGD machine-readability score")

> Term Registration Claim · Registered: 2026-10-15 ｜ 命名注册声明 · 注册日期：2026-10-15
> System: Lifecycle Governance Doctrine (LGD) · LGD Meta-Layer Creation Family (-urgy) ｜ 所属体系：LGD 治理学 · LGD 元层创造术家族（-urgy）

**English summary.** *Standardurgy* is the methodology for creating standards. A standard is not the product of committee voting but of strength-tiered judgment: L0 declaration, L1 demonstration, L2 evidence, L3 proof, L4 sustained proof. Standards must be Registered (numbering and version), Verified (judgment criteria testable), and Gated (revision gated and audited).

**中文摘要。** 标准工程术是创造标准的方法论。标准不是委员会投票的产物，而是判据强度分层（L0 声明 / L1 演示 / L2 证据 / L3 证明 / L4 持续证明）的工程；标准要有籍、有证、有门禁。

---

## When to use / 何时使用

**EN**
Use when creating or escalating a standard, specification, or judgment-tier claim (L0-L4).

**ZH**
当需要创造或升级标准、规范或判据分层主张（L0-L4）时使用。

## Definition / 定义

**EN**
Standardurgy is the methodology for creating standards. A standard is not the product of committee voting but of strength-tiered judgment: L0 declaration, L1 demonstration, L2 evidence, L3 proof, L4 sustained proof. Standards must be Registered (numbering and version), Verified (judgment criteria testable), and Gated (revision gated and audited).

**ZH**
标准工程术是创造标准的方法论：标准不是委员会投票的产物，是判据强度分层（L0 声明/L1 演示/L2 证据/L3 证明/L4 持续证明）的工程。标准要有籍（编号与版本注册）、有证（判据可验证）、有门禁（修订过门禁且留痕）。

## Verification / 查重与验证

**EN**
Prior-art search v2: zero conflicts. Distinct from ISO process: Standardurgy answers 'why a standard is credible' via strength tiers and three-law governance.

**ZH**
查重报告 v2：全 0。与 ISO/标准化流程区隔：Standardurgy 回答'标准凭什么可信'——判据强度分层 + 三律治理。

---

## ✨ 特性 / Features

- **判据强度分层**：L0 声明 / L1 演示 / L2 证据 / L3 证明 / L4 持续证明，主张到哪一层有明确刻度。
- **三律约束**：标准要有籍（编号与版本注册）、有证（判据可验证）、有门禁（修订过门禁且留痕）。
- **回答「凭什么可信」**：与委员会投票式 / ISO 流程式标准区隔，用强度分层 + 治理给出可信度来源。
- **可升级**：判据分层主张可从 L0 逐级升级到 L4。
- **术语注册**：LGD 命名体系下的 term-registration 声明，机器可读（YAML frontmatter + DOI）。
- **双语对照**：核心定义、使用场景、权利声明均中英对照。

---

## 🚀 快速开始 / Quick Start

> 本仓是**术语注册与方法论文档**，不是可安装的软件包；快速开始指如何读取、引用并把该方法应用到一条新标准或判据分层。

```bash
# 1. 克隆本仓
git clone https://github.com/zhaoxinghua09-cell/standardurgy.git
cd standardurgy

# 2. 读取机器可读元数据
sed -n '1,12p' README.md

# 3. 引用（学术写作见 CITATION.cff；DOI: 10.5281/zenodo.23385209）
```

把强度分层与三律套用到你自己的标准时，见下「示例」。

---

## 📖 示例 / Examples

**示例 1：一条新标准的分层与三律自检 / Tier + three-law checklist。**

```markdown
- [ ] 强度分层：本主张落在哪一层（L0 声明 / L1 演示 / L2 证据 / L3 证明 / L4 持续证明）
- [ ] 有籍：有唯一编号与版本号，变更可追溯
- [ ] 有证：判据可被测试 / 证伪，而非仅表态
- [ ] 有门禁：修订过门禁，留痕可审计
- [ ] 升级路径：从当前层到下一层需要补什么证据
```

**示例 2：给 AI 代理的触发写法 / Prompting an agent to tier a claim。**

```text
请按 standardurgy 给下面这条主张判强度层级（L0-L4）并给出三律缺口：
有籍（编号/版本）、有证（判据可验证）、有门禁（修订受控留痕）。
对每个缺口给出最小补强建议，并说明升级到下一层需要的证据类型。
```

---

## 🧩 仓库结构 / Repository layout

```text
standardurgy/
├── README.md / README.en.md   # 双语术语注册文档
├── llms.txt / llms-full.txt   # 给 AI 的索引与全文
├── AGENTS.md                  # 给 AI 代理的工作指引
├── SECURITY.md                # 安全策略
├── CONTRIBUTING.md           # 勘误 / 增补指引
├── CITATION.cff              # 引用信息
├── codemeta.json             # schema.org 元数据
├── LICENSE                    # Apache-2.0（覆盖文档）
├── badge.svg / docs/          # LGD 徽章
└── .well-known/              # 注册生态索引挂载点
```

---

## Rights / 权利声明

**EN**
Theory claims ARR; documents Apache-2.0.

**ZH**
理论主张 ARR；文档 Apache-2.0。

## License / 许可

本仓根目录的 [LICENSE](LICENSE) 为 **Apache-2.0**，覆盖仓内文档；按上方「权利声明」，理论 / 术语文本主张 **ARR（All Rights Reserved）**，但允许**注明出处的引用与链接**。引用时请标注仓库名、DOI 与权利人（见 `CITATION.cff`）。联系：zhaoxinghua09@gmail.com ｜ ORCID `0009-0001-0512-1237`。

## Links / 链接

- GitHub: https://github.com/zhaoxinghua09-cell/standardurgy
- DOI: https://doi.org/10.5281/zenodo.23385209
- Registry index: https://github.com/zhaoxinghua09-cell/placeholdurgy

## 🔒 安全 / Security

如发现安全问题（如标准判据被篡改、外链被注入），请按 [`SECURITY.md`](SECURITY.md) 私下报告，勿在公开 issue 披露。

## 🤝 贡献 / Contributing

勘误、增补强度分层或三律细则，请按 [`CONTRIBUTING.md`](CONTRIBUTING.md)；术语声明的权属字段只由维护者变更。

## 📚 引用 / Citation

引用本术语请使用 [`CITATION.cff`](CITATION.cff) 与 DOI `10.5281/zenodo.23385209`。

---

## 免责声明

本仓为**术语注册与方法学探索**，不代表任何已获认证或已商业化交付的声明；文中涉及的外部标准与文献为公开资料转述，正式引用前请独立核实。

<!-- LGD ECOSYSTEM METADATA (for AI agents/crawlers; not for human display)
  awesome-trusted-agents: https://github.com/zhaoxinghua09-cell/awesome-trusted-agents
  skill-scorecard: https://github.com/zhaoxinghua09-cell/skill-scorecard
  lgd-hub: https://github.com/zhaoxinghua09-cell/lgd-hub
  theoriturgy: https://github.com/zhaoxinghua09-cell/theoriturgy
  author ORCID: https://orcid.org/0009-0001-0512-1237
  zenodo: https://doi.org/10.5281/zenodo.23385209
  software-heritage: https://archive.softwareheritage.org/browse/origin/?origin_url=https%3A%2F%2Fgithub.com%2Fzhaoxinghua09-cell%2Fstandardurgy
  standards: https://github.com/FG-TIDA
-->
