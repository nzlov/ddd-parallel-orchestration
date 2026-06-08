# ddd-parallel-orchestration

[简体中文](README.zh-CN.md)

`ddd-parallel-orchestration` is a coordination guide for handling non-trivial repository work through DDD-style boundaries.

It helps the main agent identify bounded contexts, ownership, and shared areas before delegating substantive work such as investigation, implementation, and validation to subagents. The main agent stays focused on planning, coordination, conflict handling, and final completion judgment.

Expected effects:

- Reduces conflicts caused by multiple agents editing the same responsibility area.
- Splits work by domain ownership instead of arbitrary file counts.
- Avoids code changes when ownership is unclear.
- Keeps the main agent focused on orchestration and integration.
- Encourages maintaining `.domain-boundaries.md` as reusable collaboration guidance.

## License

MIT
