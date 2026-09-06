# AI 落地陪跑方法论

> 一个面向本地中小企业/门店的 Agent Skill：帮你设计、执行、复盘“AI 落地陪跑”服务。
> An Agent Skill for planning and delivering AI adoption coaching for local small businesses.

它不按行业教学，而是按通用业务环节工作：

获客 → 咨询成交 → 交付 → 售后复购

## 安装

把 `skills/ai-peipao-methodology` 复制到你的技能目录：

- Codex / OpenAI-compatible clients：`~/.codex/skills/ai-peipao-methodology`
- 其他支持 Agent Skills 的客户端：按该产品文档放入对应 skills 路径

重启后，在你的对话中这样调用：

```text
$ai-peipao-methodology
```

或直接说：

```text
用 $ai-peipao-methodology 帮我为一个本地中小企业/门店设计 AI 落地陪跑方案
```

## 用法示例

- “客户是 20 人装修公司，老板觉得客户问着问着就不回，帮我生成资料清单和 30 天试点方案。”
- “帮一家奶茶店设计 7 天免费体验 + 299 元月包的内容陪跑流程。”
- “我把老板资料发给你，按流程跑一遍诊断。”

## 目录

```text
ai-peipao-methodology/
├── SKILL.md                    # 技能入口与约束
├── references/
│   └── methodology.md          # 完整通用方法论
└── agents/
    └── openai.yaml             # ChatGPT/Codex 界面元数据
```

## 设计来源

工作流参考了以下公开资源：

- [GenAI Consulting Methodology Toolkit](https://github.com/MorrisLu-Taipei/GenAI-Consulting-Methodology-Toolkit)
- [enterprise-ai-skills](https://github.com/sruthir28/enterprise-ai-skills)
- [AI Adoption Ladder / Copilot CoE](https://github.com/maree217/copilot-center-of-excellence)
- [良策 AI](https://www.liangce.ai/services)

## License

MIT
