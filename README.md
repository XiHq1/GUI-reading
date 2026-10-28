# GUI Agent 论文阅读

记录 GUI Agent / 网页智能体方向的论文、阅读笔记与阅读路线。内容服务于「面向 GUI 智能体的推理价值校准」项目：先弄清环境与评测，再进入 grounding 与 agent 框架，最后落到“何时值得多看一眼、多想一步”。

## 目录

- [仓库结构](#仓库结构)
- [阅读路线](#阅读路线)
- [笔记索引](#笔记索引)
- [论文清单](reading-list.md)
- [笔记模板](notes/_template.md)

## 仓库结构

```text
GUI-reading/
├─ README.md
├─ reading-list.md          # 14 篇论文总表：年份、主题、用途、状态
├─ notes/
│  ├─ _template.md          # 新笔记模板
│  ├─ MIND2WEB_Towards_a_Generalist_Agent_for_the_Web/
│  │  ├─ MIND2WEB_Towards_a_Generalist_Agent_for_the_Web.md
│  │  └─ images/
│  └─ webarena/
│     ├─ webarena.zh-CN.md
│     └─ images/
└─ papers/                  # 本地 PDF（不入库）
```

## 阅读路线

### 第 1 阶段：环境与评测

1. **WebArena**（2024 ICLR）— 自托管真实站点 + 功能正确性判分 + 可重置。
2. **Mind2Web**（2023 NeurIPS）— 真实网页任务数据集，离线元素选择。
3. **OSWorld**（2024 NeurIPS）— 桌面环境，执行式评测。

这一阶段只回答两个问题：**环境能不能重置到同一状态**、**成功能不能自动判**。这两个问题不解决，后面的 Δ 都不可信。

### 第 2 阶段：Grounding

4. **SeeClick**（2024 ACL）— 视觉 GUI grounding 的早期代表。
5. **UGround**（2025 ICLR）— 统一视觉 grounding。
6. **OS-Atlas**（2025 ICLR）— 跨平台 grounding 数据与模型。
7. **ScreenSpot-Pro**（2025 MM）— 高分辨率专业软件 grounding 基准，适合做难度分层。
8. **ShowUI**（2025 CVPR）— 轻量 VLM GUI agent，关注 token 效率。
9. **RegionFocus**（2025 ICCV）— 区域放大提升 grounding，是“补观测”最直接的相关工作。

### 第 3 阶段：Agent

10. **Agent S**（2025 ICLR）— 经验检索式 agent，可作为强基线。
11. **OS-Symphony**（2026 ACL）— 里程碑触发的反思/检索，可作为“触发时机”的对照。
12. **GUI-Cursor**（2026 ICML）— 学习式多步光标交互，可作为自适应投入的对照。
13. **OpenCUA**（2025 NeurIPS）— 开放的 CUA 数据、模型与基准。
14. **VideoAgentTrek**（2026 ICLR）— 轨迹数据与测试时扩展。

## 笔记索引

| 论文 | 年份/会议 | 笔记 | 状态 |
|---|---|---|---|
| WebArena | 2024 ICLR | [中文笔记](notes/webarena/webarena.zh-CN.md) | 已读 |
| Mind2Web | 2023 NeurIPS | [笔记](notes/MIND2WEB_Towards_a_Generalist_Agent_for_the_Web/MIND2WEB_Towards_a_Generalist_Agent_for_the_Web.md) | 已读 |
| OSWorld | 2024 NeurIPS | [笔记](notes/OSWorld/OSWorld_Benchmarking_Multimodal_Agents_for_Open_Ended_Tasks_in_Real_Computer_Environments.md) | 已读 |
| RegionFocus| 2025 ICCV | [笔记](notes/regionFocus/Visual_Test_Time_Scaling_for_GUI_Agent_Grounding.md) | 已读 |
| 其余 10 篇 | — | 待补 | 待读 |

> PDF 不纳入版本库，本地保存在 `papers/`（已在 `.gitignore` 中排除）。
