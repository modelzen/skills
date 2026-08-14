# Vonvon Skills

## Skills

### Visual

| Skill | 用途 |
| --- | --- |
| [`vonvon-illustrations`](./skills/visual/vonvon-illustrations/SKILL.md) | 用 Vonvon 品牌形象生成 16:9 白底手绘中文正文配图，适合观点、流程、结构、状态和方法论。 |
| [`vonvon-scenes`](./skills/visual/vonvon-scenes/SKILL.md) | 用 Vonvon 品牌形象生成“真实物件 + 物理动作”的正文场景图，以及超横版长卷故事图。 |

## 安装

列出仓库内可用的 skills：

```bash
npx skills@latest add modelzen/skills --list
```

交互式选择并安装：

```bash
npx skills@latest add modelzen/skills
```

安装指定 skill：

```bash
npx skills@latest add modelzen/skills --skill vonvon-illustrations
npx skills@latest add modelzen/skills --skill vonvon-scenes
```

也可以一次安装全部 skills：

```bash
npx skills@latest add modelzen/skills --all
```

## 使用示例

```text
Use $vonvon-illustrations 为这篇中文文章设计并生成 4 张 Vonvon 手绘正文配图。
```

```text
Use $vonvon-scenes 的彩蛋模式，把这个项目复盘做成一张超横版 Vonvon 长卷故事图。
```

## 目录结构

```text
skills/
└── visual/
    ├── vonvon-illustrations/
    │   ├── SKILL.md
    │   ├── NOTICE.md
    │   ├── agents/
    │   ├── assets/
    │   └── references/
    └── vonvon-scenes/
        ├── SKILL.md
        ├── NOTICE.md
        ├── agents/
        ├── assets/
        └── references/
```

后续新增 skill 时，请继续使用 `skills/<category>/<skill-name>/` 结构。具体约定见 [CONTRIBUTING.md](./CONTRIBUTING.md)。

## 来源与致谢

这两个 Vonvon skills 是基于 Ian（[@helloianneo](https://github.com/helloianneo)）的“小黑”系列 skills 修改而来：

- `vonvon-illustrations` 基于 [helloianneo/ian-xiaohei-illustrations](https://github.com/helloianneo/ian-xiaohei-illustrations)
- `vonvon-scenes` 基于 [helloianneo/ian-xiaohei-scenes](https://github.com/helloianneo/ian-xiaohei-scenes)

上游项目采用 MIT License。Vonvon 版本保留了其内容理解、视觉隐喻、母版选择与 QA 工作流的核心思路，并替换为 Vonvon 品牌形象、角色参考图和重新生成的示例图。这些衍生版本不是 Ian 的官方发布。

完整归属说明见 [NOTICE.md](./NOTICE.md) 和各 skill 目录内的 `NOTICE.md`。

## License

[MIT](./LICENSE)
