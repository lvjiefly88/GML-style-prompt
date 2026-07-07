# Vincenox的页面提示词生成器

**GML-style page prompt lab** 是一个 0 token 拼配式页面 Prompt 生成工具，用于把网页想法拆解为类型、风格、视觉策略、页面结构、交互细节和质量约束，再组合成可直接交付给页面生成模型的高质量 Prompt。

> 语言的边界就是世界的边界。

## 项目特点

- 单文件运行：核心工具是 `gml-prompt-generator.html`，直接用浏览器打开即可使用。
- 中文操作界面：用户选择中文选项，工具自动匹配更适合网页生成的英文提示词。
- 结构化 Prompt：按页面类型、风格方向、视觉策略、页面 / 游戏结构、交互细节和实现要求组织输出。
- 风格包预设：内置品牌官网、博客、小游戏、3D 定制器、教育可视化、作品集、电商页、工具 / SaaS 等方向。
- 配色方案独立：颜色和用途分开填写，避免把“什么颜色”和“用在哪里”混在一起。
- 支持手动编辑：右侧生成结果可以继续手动调整；手动编辑后不会被普通表单变化自动覆盖。
- 可撤销操作：切换类型、应用风格、重置等关键操作提供撤销入口。

## 文件结构

```text
.
├── GML-html-prompt.md
├── gml-prompt-generator.html
├── README.md
└── .gitignore
```

- `GML-html-prompt.md`：原始 GML 风格网页 Prompt 样例和规律来源。
- `gml-prompt-generator.html`：页面 Prompt 生成器主体，包含 HTML、CSS 和 JavaScript。
- `README.md`：项目说明文档。

## 使用方式

1. 下载或克隆本项目。
2. 用浏览器打开 `gml-prompt-generator.html`。
3. 依次选择网页类型、风格方向、视觉策略、页面结构和交互细节。
4. 在右侧复制生成的 Prompt，或下载为 `.txt` 文件。

不需要安装依赖，不需要启动开发服务器。

## 适合生成的页面类型

- 品牌官网
- 博客 / 内容站
- 网页小游戏
- 3D / 定制器
- 教育可视化
- 作品集
- 电商 / 产品页
- 工具 / SaaS

## 作者

- Email: [lvjiefly88@gmail.com](mailto:lvjiefly88@gmail.com)
- GitHub: [lvjiefly88](https://github.com/lvjiefly88)

## License

目前未指定开源协议。如需公开协作或复用，建议后续补充 `LICENSE` 文件。