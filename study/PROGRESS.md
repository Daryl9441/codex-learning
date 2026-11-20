# 研读进度

**结论**：15 课都未开始。勾选由导师在你通过后写入；笔记只留 1–2 句。两道面试题都 ≥ 8/10 才勾「面试题已过」。

基线 commit：`67f0994b532b8740f14b5b738af7b7b2a915b1d6`。

**学习偏好（2026-11-19）**：
- 之后所有课，**永久跳过「演示命令」「动手练习」整节**
- **引导问题 / 面试题一律题目+参考答案同发**（见 `.cursor/rules/codex-tutor.mdc`）

## 当前位置

| 字段 | 值 |
|---|---|
| 课 | L15 · Capstone |
| 节 | 10分钟提纲 / 对比表 |
| 状态 | 进行中 |
| 下一节 | 引导问题（演示/练习永久跳过） |
| 更新日期 | 2026-11-20 |

> 推进到下一节时更新本表并 `git commit`（见 `.cursor/rules/codex-tutor.mdc` 学习习惯）。

| 课 | 读完 | 练习 | 面试题已过 | 完成日期 | 笔记 |
|---|---|---|---|---|---|
| [L01](lessons/L01-layout.md) | [x] | [x] | [ ] |  | 布局/分层已过；面试题跳过。笔记：[notes/2026-11-02-L01-L02.md](notes/2026-11-02-L01-L02.md) |
| [L02](lessons/L02-session.md) | [x] | [ ] | [ ] |  | SQ/EQ、steer、Session vs TurnContext；面试参考已读未打分。练习分支 `study/L02-op-log` |
| [L03](lessons/L03-run-turn.md) | [x] | [ ] | [ ] |  | run_turn 两环、needs_follow_up、早 spawn 晚 drain；面试参考已读。练习分支 `study/L03-follow-up-log` |
| [L04](lessons/L04-model-client.md) | [x] | [ ] | [ ] |  | ModelClient vs Session；完整 history + WS 增量；演示/练习跳过 |
| [L05](lessons/L05-prompt.md) | [x] | [ ] | [ ] |  | fragment + role/kind；稳定前缀 vs history diff；面试题跳过；CLI 因缺 toolchain 1.95.0 未跑 |
| [L06](lessons/L06-history-compaction.md) | [x] | [ ] | [ ] |  | ContextManager + for_prompt/normalize；auto compact 三选一；面试题跳过 |
| [L07](lessons/L07-tools.md) | [x] | [ ] | [ ] |  | Router/Registry/Runtime；并行 RwLock；RespondToModel vs Fatal；面试题跳过 |
| [L08](lessons/L08-approval-execpolicy.md) | [x] | [ ] | [ ] |  | approval × sandbox 正交；ForcedRm；Orchestrator 先批后沙箱；面试题跳过 |
| [L09](lessons/L09-sandbox.md) | [x] | [ ] | [ ] |  | SandboxManager；bwrap/Seatbelt；`.git` 只读；拒绝启发式；面试题跳过 |
| [L10](lessons/L10-apply-patch.md) | [x] | [ ] | [ ] |  | Begin Patch 协议；verify→safety→落盘；seek_sequence 四级；面试题跳过 |
| [L11](lessons/L11-mcp-client.md) | [x] | [ ] | [ ] |  | MCP client；callable_* vs raw name；AppToolApproval；无 mcp-server；面试题跳过 |
| [L12](lessons/L12-exec-app-server.md) | [x] | [ ] | [ ] |  | exec→app-server JSON-RPC；Never+reject；ThreadEvent≠EventMsg；面试题跳过 |
| [L13](lessons/L13-config-agents-md.md) | [x] | [ ] | [ ] |  | layer precedence；requirements 打回；AGENTS root→cwd + 32KiB；面试题跳过 |
| [L14](lessons/L14-tui-rollout-otel.md) | [x] | [ ] | [ ] |  | TUI select!→app-server；rollout JSONL resume；otel 默认不记 prompt；面试题跳过 |
| [L15](lessons/L15-capstone.md) | [ ] | [ ] | [ ] |  |  |

## 勾选含义

| 列 | 何时勾 |
|---|---|
| 读完 | 课稿各节都过完，你能按调用链复述 |
| 练习 | 动手练习有预期结果；改过的代码已按课稿撤回或留在练习分支 |
| 面试题已过 | 两题都 ≥ 8/10 |
| 完成日期 | 上两列都勾上的日期（`YYYY-MM-DD`） |
| 笔记 | 1–2 句：本课最关键的设计和你仍不确定的点 |
