# Evaluation notes / 评估记录

These are qualitative agent checks, not human usability studies or statistically reliable benchmarks.

## Scenarios

| Case | Request | Behavior to examine |
|---|---|---|
| Portfolio | Six homepage directions; camera-only project navigation; recruiter needs a campaign case study. | Structural diversity, per-direction task paths and trade-offs, direct navigation, no invented usability evidence. |
| Motion | A 20-second CSV-export explanation with no usage data. | Focal points, explicit reading holds, continuity, reduced motion, accurate product assumptions, no fabricated claims. |
| Dashboard | Polished KPIs do not reveal conversion loss; no user tests exist. | Question-led structure, metric provenance, proposed observation separated from actual findings. |
| Bounded edit | Change only a primary button from blue to green. | Preserve scope, check immediate contrast/states, avoid restarting exploration. |

## English baseline and forward check

A baseline agent without this skill produced sensible directions, an honest motion storyboard, a funnel proposal, and a scoped button response. It already avoided invented usage statistics and proposed a usability task.

The baseline did not consistently attach risks and accessibility/mobile/cost trade-offs to each portfolio direction. Its motion timeline omitted explicit settled reading holds and a reduced-motion alternative. Its dashboard response mentioned metric definitions but did not spell out source lineage and transformations.

A separate agent then used the completed skill on the same requests. Its output included:

- Six structural options with paths, risks, mobile/accessibility considerations, and cost.
- Direct portfolio navigation and an explicitly untested recruiter task.
- A 20-second storyboard with focal points, settled holds, matched records, reduced motion, and an export-scope assumption.
- Three dashboard structures, inspectable data lineage, and pending participant findings.
- A narrowly scoped button response that requested the absent component instead of inventing an implementation.

This was one baseline and one forward pass. No repetition-based claim, causal performance estimate, or production usability conclusion is supported.

## 中文说明

以上是智能体行为的定性检查，不是真实用户研究，也不是具有统计可靠性的基准测试。

无技能的基线回答已经具备部分良好判断。完成技能后的独立回答在方案取舍、阅读停留、减少动态效果和指标来源链路方面更完整，并保持了小修改的边界。每组仅进行一次检查，不能据此推断稳定提升或真实产品效果。

独立评估者阅读了两种语言的主文件、参考文件与代理配置，并用中文版处理了看板场景：回答给出了阶段对比、指标来源与任务测试计划，没有声称已有用户研究结果。评估者发现一处译法将 segment 收窄为“细分人群”，现已改为“细分维度（如渠道、设备、用户群体）”。未报告其他实质意义差异。

两个版本均通过技能结构验证；相对链接、技能命名、界面元数据和未完成占位符检查也通过。真实用户反馈仍须在具体项目中获得。

## Chinese edition review

An independent evaluator compared both editions and applied the Chinese edition to the dashboard scenario. The response proposed stage comparisons, metric provenance, and an observational task without claiming completed research. One translation narrowed “segments” to audiences; it was corrected to include channels, devices, and user groups. No other material parity issue was reported. Both editions passed the skill validator and local link/metadata checks.
