# Image Processing Skills

持续收集可复用的图像处理 skills 与原始提示词。每个 skill 独立放在 `skills/<skill-name>/`，便于以后扩展、维护与单独安装。

## Skills

| Skill | 用途 |
| --- | --- |
| [travel-ticket-poster](skills/travel-ticket-poster/SKILL.md) | 将上传照片制作成上下等高的竖版旅行纪念票根海报 |
| [photo-line-art-poster](skills/photo-line-art-poster/SKILL.md) | 将上传照片制作成上半实景、下半线稿延伸互动的竖版旅行海报 |
| [photo-line-art-fade-poster](skills/photo-line-art-fade-poster/SKILL.md) | 将上传照片制作成 3:4 实景延伸线稿海报，中部背景色渐隐为近白纸面、无硬分界线 |
| [rubber-stamp-travel-poster](skills/rubber-stamp-travel-poster/SKILL.md) | 将上传照片制作成上半原照、下半橡胶印章转译的 3:4 旅行记录海报 |
| [shadow-puppet-poster](skills/shadow-puppet-poster/SKILL.md) | 将上传照片制作成上半原照、下半主体皮影戏偶在暖光宣纸幕布上演出的 3:4 海报 |
| [second-world-poster](skills/second-world-poster/SKILL.md) | 将上传照片制作成上下连续场景海报：上半真实摄影、下半从原照结构生长出"第二世界" |

## 使用

将所需 skill 的完整目录复制到你的 Codex skills 目录，然后在支持 skills 的会话中上传图片并调用，例如：

> 使用 $travel-ticket-poster，把这张照片做成旅行纪念票根海报。

本仓库存放指令与提示词，需要运行环境提供图片查看和图像生成／编辑能力。仅浏览仓库不会自动安装 skill。

## 添加更多

在 `skills/` 下创建新的小写连字符目录，并添加带 `name`、`description` YAML 元数据的 `SKILL.md`。原始提示词可放在该 skill 的 `references/original-prompt.md`，并在本页登记用途。
