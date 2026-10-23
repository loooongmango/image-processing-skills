# Image Processing Skills

持续收集可复用的图像处理 skills 与原始提示词。每个 skill 独立放在 `skills/<skill-name>/`，便于以后扩展、维护与单独安装。

## Skills

| Skill | 用途 |
| --- | --- |
| [travel-ticket-poster](skills/travel-ticket-poster/SKILL.md) | 将上传照片制作成上下等高的竖版旅行纪念票根海报 |
| [photo-line-art-poster](skills/photo-line-art-poster/SKILL.md) | 将上传照片制作成上半实景、下半线稿延伸互动的竖版旅行海报 |

## 使用

将所需 skill 的完整目录复制到你的 Codex skills 目录，然后在支持 skills 的会话中上传图片并调用，例如：

> 使用 $travel-ticket-poster，把这张照片做成旅行纪念票根海报。

本仓库存放指令与提示词，需要运行环境提供图片查看和图像生成／编辑能力。仅浏览仓库不会自动安装 skill。

## 添加更多

在 `skills/` 下创建新的小写连字符目录，并添加带 `name`、`description` YAML 元数据的 `SKILL.md`。原始提示词可放在该 skill 的 `references/original-prompt.md`，并在本页登记用途。
