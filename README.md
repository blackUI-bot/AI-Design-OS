# AI-Design-OS

我的 AI 设计知识库与工作流系统（AI Design OS）。

## Codex Skills

### 运营字体生成

根据用户提供的中文字体、标题字、手写字、艺术字或字标参考图片，分析字体骨架、笔画、结构、设计语言与排版，并为新的运营文案建立同字体家族的设计方案。

主要能力：

- 将第一张字体图片登记为主参考图；
- 拆解字体骨架、笔画、结构、设计点与排版；
- 优先复用已确认的整字、偏旁、部件和特征笔画；
- 为新的运营文案提出设计方案；
- 在支持图片生成的 Codex 环境中继续生成和局部修改字体图片；
- 确认字体名称后，将任务标题改为“字体名称｜运营字体生成”。

Skill 文件位于：

`operations-font-generator/`

#### 推荐安装方式

把下面这句话发给 Codex：

> 请从 https://github.com/blackUI-bot/AI-Design-OS/tree/main/operations-font-generator 安装“运营字体生成”Skill。

安装完成后，重新打开一个 Codex 任务，在 Skill 列表中选择“运营字体生成”。

#### 手动下载

1. 点击 GitHub 页面右上方绿色的 **Code**。
2. 选择 **Download ZIP**。
3. 把 ZIP 文件拖进 Codex。
4. 告诉 Codex：“请安装压缩包中的 operations-font-generator Skill。”
