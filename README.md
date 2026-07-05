# fable-dev-doctrine

从 H753 编码器工装战役（2026-07，Fable 5 主导的全栈硬件在环开发）蒸馏出的三个
工程方法论 skill，作为 Claude Code 插件跨项目挂载。

| Skill | 一句话 | 何时触发 |
|---|---|---|
| `forensic-debugging` | 取证式排除法：判别器实验、逐层清白记录、字节级定罪 | 跨层疑难故障、间歇复现、"修了没用" |
| `subagent-pipeline` | 强模型规划判决 + 执行模型实现 + 独立审查 + 义务传递 + 台账 | 3+ 任务的 spec 驱动开发 |
| `bench-discipline` | 停机双验、零触碰证明、判据先行、双份沉淀 | 电机/烧录/共享固件/真机验收 |

## 挂载

```
/plugin marketplace add <你的用户名>/fable-dev-doctrine
/plugin install fable-dev-doctrine@fable-dev-doctrine
```

## 出身

- 战役档案：`@STM32H753ZI/ESP32-S3-N16R8/NOTES.md` 与
  `docs/2026-07-04-wifi-link-architecture-review.md`（判决书 §10）
- 代表性战果：十层根因链（GND 幽灵地环 → PC 读取器行首匹配缺陷）全部实验定罪/洗白；
  ARQ 可靠性层 4 任务流水线终审抓出切片审查结构性看不见的组合僵死雷。

方法论与项目解耦：skill 正文只保留可复用流程，项目细节仅作一行例证。
