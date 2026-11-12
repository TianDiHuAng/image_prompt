# image_prompt

AI 生图 / 提示词相关的技能与提示词集合。

## 目录

| 目录 | 说明 |
|---|---|
| [fashion-prompt-artist](./fashion-prompt-artist/SKILL.md) | 服装美术 / 时尚造型 / 真人写真提示词写作助手（Claude Skill 结构） |

---

## fashion-prompt-artist

把"一个想法"变成"一段能被模型稳定画出来、有时装行业质感、且像真实照片的描写"。

- **适用模型**：Midjourney、Stable Diffusion、Flux、即梦、可灵、Nano Banana、GPT-image 等
- **覆盖品类**：针织开衫、毛衣裙、旗袍/新中式、丝袜与鞋履、蕾丝、真丝睡裙、泳装、职业装、礼服露背
- **双模式路由**：`REAL` 写实摄影（默认）/ `PAINTERLY` 2.5D 厚涂，两种模式的肤质词与负面词严禁混用
- **六种写法模式**：A 模块式、B 叙事分段式、C 随机池式、D 锁定式、E 一段式英文、F 八段式
- **硬规则：负面词不进正文**——有独立负面输入口（SD/Flux 双框、MJ 的 `--no`）才填负面词；
  只有正向文本框（H3 / Minimax 系等）时整段省略，全部改写为正向陈述（实测"不要插座"会召唤插座）

### 文件结构

```
fashion-prompt-artist/
├── SKILL.md                                  # 主入口：理念、路由、安全边界、工作流、检查清单
└── references/
    ├── garments.md                           # 服装/针织/丝袜/新中式/睡裙/泳装/职业装
    ├── fabrics-colors.md                     # 面料、质感、色彩
    ├── jewelry-accessories.md                # 首饰、包、鞋、发饰
    ├── brands.md                             # 品牌语言（Balenciaga、Valentino、Prada、The Row…）
    ├── realism-and-candid.md                 # 真实感与抓拍叙事
    ├── anti-ai-realism.md                    # 去 AI 感手册：面料/光线/骨相/手机随手拍/胶片锚点
    ├── pose-and-anatomy.md                   # 姿势、机位、人体结构硬性要求
    ├── prompt-templates.md                   # 各模式模板与分类负面词库（仅用于有负面输入口的工作流）
    ├── painterly-mode.md                     # 2.5D 厚涂 / 韩漫模式
    ├── consistency-and-troubleshooting.md    # 随机池防失控、角色卡锁定、常见问题修正
    └── case-studies.md                       # 27 条真实提示词拆解
```

### 使用方式

作为 Claude Skill 使用：把 `fashion-prompt-artist/` 放进 skills 目录，模型会在涉及写真、人像、服装描写、
穿搭、造型、人设、lookbook、生图提示词等场景自动加载。

也可以当作纯提示词资料：直接读 `SKILL.md` 建立框架，再按需翻阅 `references/` 下的对应主题。

### 边界

- 人物必须是**明确的成年人**（写明"明确成年的 XX 岁"，年龄 ≥ 22 为宜）
- 保持**时装大片/杂志写真级别**，不做露骨内容、不做偷窥视角、不写 logo 与真实名人

---

## License

仅供个人学习与创作参考。
