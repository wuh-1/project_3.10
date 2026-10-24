feat: 新功能
feat(employee): 新增员工状态修改接口

fix: 修复问题
fix(auth): 处理 JWT 过期后的登录跳转

refactor: 重构，不改变功能
refactor(request): 统一封装 Axios 错误处理

style: 仅格式、样式调整
style(employee): 调整员工页面布局

docs: 文档修改
docs: 补充项目启动说明

test: 新增或修改测试
test(employee): 覆盖重复用户名场景

chore: 配置、依赖、构建等杂项
chore: 添加 Axios 和 Pinia 依赖



| Skill | 主要使用位置 | 适合什么时候用 |
|---|---|---|
| `grill-with-docs` | 需求分析 | 你只有一个模糊想法，还没想清楚需求 |
| `to-spec` | 需求设计 | 已经讨论清楚，要整理成正式功能说明 |
| `to-tickets` | 任务拆分 | 一个功能太大，需要拆成几个小任务 |
| `implement` | 编码实现 | 需求和任务已经明确，让 Codex 真正修改代码 |
| `tdd` | 测试驱动开发 | 想先写测试，再实现功能 |
| `diagnosing-bugs` | Debug | 程序报错、功能不符合预期，需要系统定位问题 |
| `code-review` | 开发完成后 | 检查代码质量、潜在 Bug、设计问题 |
| `ask-matt` | Skill 导航 | 不知道当前应该使用哪个 Skill |
| `setup-matt-pocock-skills` | 项目初始化 | 一个项目第一次配置这套 Skill 时使用 |