# 落地页配图skill

为产品落地页组织图片、英文 UI、icon、流程箭头与同帧对比。

## 内容

- [技能正文](SKILL.md)：流程、色板、排版与验证规范。
- [表达模式](references/表达模式.md)：同帧对比、连续动作、产品、角色、歌词与多比例导出。
- [调用配置](agents/openai.yaml)：中文名称和默认提示词。

## 安装

将仓库克隆到本地技能目录；如果已有同名目录，请先保留现有修改。

```sh
git clone https://github.com/jiangshanshan361-ops/landing-page-illustration-skill.git ~/.codex/skills/落地页配图skill
```

## 使用

提供 Figma 画板链接和需求，例如：

> 使用 $落地页配图skill，把这个画板整理成同帧左右对比，沿用现有背景。

图内默认使用英文，沟通使用中文。Figma 编辑需要可用的 Figma 插件，缺少素材时按需使用图像生成工具。

静态说明配图不代表已经生成真实 4K 视频、插帧视频或导出文件。
