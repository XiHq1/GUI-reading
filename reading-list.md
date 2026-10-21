# 论文清单

共 14 篇，按阅读阶段排序。状态：已读 / 在读 / 待读。

| # | 年份/会议 | 论文 | 主题 | 在本项目中的用途 | 状态 | 笔记 |
|---|---|---|---|---|---|---|
| 1 | 2024 ICLR | [WebArena](https://arxiv.org/abs/2307.13854) | 真实网页环境与基准 | 主实验环境候选：reset、功能判分、长程任务 | 已读 | [笔记](notes/webarena/webarena.zh-CN.md) |
| 2 | 2023 NeurIPS | [Mind2Web](https://arxiv.org/abs/2306.06070) | 网页 agent 数据集 | 理解离线元素选择与跨站/跨域泛化 | 已读 | [笔记](notes/MIND2WEB_Towards_a_Generalist_Agent_for_the_Web/MIND2WEB_Towards_a_Generalist_Agent_for_the_Web.md) |
| 3 | 2024 NeurIPS | [OSWorld](https://arxiv.org/abs/2404.07972) | 桌面 OS 环境 | 桌面扩展；执行式评测与虚拟机快照 | 待读 | — |
| 4 | 2024 ACL | [SeeClick](https://arxiv.org/abs/2401.10935) | 视觉 GUI grounding | grounding 背景；截图定位 | 待读 | — |
| 5 | 2025 ICLR | [UGround](https://arxiv.org/abs/2410.05243) | 统一视觉 grounding | grounding 底座候选；多候选一致性 | 待读 | — |
| 6 | 2025 ICLR | [OS-Atlas](https://arxiv.org/abs/2410.23218) | 跨平台 grounding 数据 | 数据合成与跨平台迁移参考 | 待读 | — |
| 7 | 2025 MM | [ScreenSpot-Pro](https://arxiv.org/abs/2504.07981) | 高分辨率 grounding 基准 | 难度分层；3–5 天离线预实验 | 待读 | — |
| 8 | 2025 CVPR | [ShowUI](https://arxiv.org/abs/2411.17465) | 轻量 VLM GUI agent | token 成本视角；轻量底座候选 | 待读 | — |
| 9 | 2025 ICCV | RegionFocus | 区域放大 | “补观测”直接相关工作；observe 基线 | 待读 | — |
| 10 | 2025 ICLR | [Agent S](https://arxiv.org/abs/2410.08164) | 经验检索式 agent | 强基线；经验检索可视为一种追加推理 | 待读 | — |
| 11 | 2026 ACL | OS-Symphony | 里程碑触发反思 | “触发时机”的对照；反思状态记录 | 待读 | — |
| 12 | 2026 ICML | GUI-Cursor | 学习式多步交互 | 自适应投入的对照；多步光标策略 | 待读 | — |
| 13 | 2025 NeurIPS | OpenCUA | 开放 CUA 数据/模型 | 评测任务与数据扩展 | 待读 | — |
| 14 | 2026 ICLR | VideoAgentTrek | 轨迹数据 | 轨迹数据与测试时扩展 | 待读 | — |


## 按主题分组

- **环境与基准**：WebArena、Mind2Web、OSWorld、ScreenSpot-Pro、OpenCUA
- **Grounding**：SeeClick、UGround、OS-Atlas、RegionFocus、ShowUI
- **Agent 框架**：Agent S、OS-Symphony、GUI-Cursor、VideoAgentTrek

## 更新规则

- 读完一篇：把状态改为「已读」，补上笔记链接；
- 写了一篇：在 `notes/` 下新建文件，并在本表「笔记」列加链接；
- 新增论文：按阅读阶段插入，不要打乱编号，新论文用小数或追加在末尾并注明。
