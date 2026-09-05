# 研究综合 Skill

对两份以上、尤其跨方法或跨来源的既有研究材料去重、对照和综合，形成可追溯的主题、矛盾、机会与决策证据。

## 适合处理

- 多份研究材料的来源盘点、去重和交叉验证
- 跨方法、跨人群或跨时间的主题与矛盾分析
- 负例、边界案例、置信度与证据限制
- 从研究结论到机会和产品决策的证据链

设计新研究、逐份正式编码原始访谈、客户 Persona/JTBD 分析和问卷统计应使用相应专项 Skill。

## 使用

在 Codex 中直接调用：

```text
$synthesize-research-cn 综合这些研究材料，保留证据、冲突、反证和未知。
```

安装到个人 Skill 目录的一种方式：

```bash
git clone https://github.com/fengxinbo558/synthesize-research-cn.git ~/.codex/skills/synthesize-research-cn
```

若目标目录已经存在，请先自行检查，不要直接覆盖。

## 内容

- `SKILL.md`：主入口、路由、工作模式与证据纪律
- `agents/openai.yaml`：中性中文 UI 元数据
- `references/`：综合方法与输出模板
- `evals/`：触发与行为样例

## 验证与来源

本仓库版本已通过结构、安全、链接和隔离安装检查。来源和修改边界见 `UPSTREAM.md`，适用许可证原文见 `LICENSE.upstream`；这些文件属于法律与诚实溯源记录，不应删除。
