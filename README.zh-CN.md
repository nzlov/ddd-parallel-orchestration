# ddd-parallel-orchestration

[English](README.md)

`ddd-parallel-orchestration` 是一个协作编排指南，用于让代理在处理非平凡仓库任务时按 DDD 边界进行编排。

它的作用是让主代理先识别项目的 bounded context、ownership 和共享区域，再把调查、实现、验证等实质性工作按边界委派给 subagent。主代理主要负责规划、协调、冲突处理和最终判断。

使用效果：

- 减少多个代理同时修改同一职责区域导致的冲突。
- 让任务拆分更贴近业务边界，而不是按文件数量机械拆分。
- 避免在所有权不清楚时贸然改代码。
- 让主代理保持全局视角，专注于 orchestration 和结果集成。
- 促使仓库维护 `.domain-boundaries.md`，把领域边界沉淀成可复用的协作规则。

## License

MIT
