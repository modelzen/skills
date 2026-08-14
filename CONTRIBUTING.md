# Contributing

欢迎继续向这个仓库添加可复用的 Agent Skills。

## 新增 skill

1. 在 `skills/<category>/<skill-name>/` 下创建独立目录。
2. 必须包含 `SKILL.md`，并在 YAML frontmatter 中提供唯一的 `name` 和清晰的 `description`。
3. 只提交该 skill 运行所需的 `agents/`、`assets/`、`references/`、`scripts/` 等文件。
4. 如果基于第三方项目修改，保留其许可证要求，并在该 skill 目录内添加 `NOTICE.md`。
5. 在根目录 `README.md` 的 skill 列表中补充入口和一句话说明。

## 设计原则

- 单一职责：一个 skill 解决一类清晰问题。
- 可组合：避免把完整工作流硬编码进一个巨型 skill。
- 渐进读取：把详细参考资料放入 `references/`，只在需要时读取。
- 自包含：安装单个 skill 后，它依赖的本地文件应完整可用。
- 可验证：为关键步骤提供明确的完成门禁或 QA 检查。
- 尊重来源：衍生作品必须保留许可证和归属声明。

## 提交前检查

```bash
npx skills@latest add . --list
```

确认新增的 skill 能被发现，所有相对路径都能在其目录中解析，并检查图片或其他二进制资产没有缺失。
