# AI 观测 / The AI Observer

高级黑白风格的 AI 资讯精选网页。单文件静态站点，无构建依赖。

## 内容与功能

- 本期 7 条资讯，覆盖 OpenAI、腾讯、Google、Microsoft、百度和 Meta。
- 每条提供事件日期、原始发布时间、背景、摘要、内容、核验说明、核验日期及官方原文链接。
- 支持关键词搜索、机构筛选、时间排序和详情展开。
- 适配桌面及移动端。

资讯为截至 2026 年 11 月 3 日（北京时间）的人工检索核验快照，入选原文发表于 10 月 15 日至 11 月 2 日，尚未接入自动采集。日期依原文标注，原文未注明时区时不作时区换算。

## 本期换条说明

- 保留：Meta 的 Muse Spark Open（10 月 15 日），作为近期开放权重动态。
- 替换：国务院“人工智能+”会议、Reflection Beam、ChatGPT Slides、ChatGPT Voice、Gemini 4 Argon、腾讯 WorkBuddy 旧文，共 6 条。旧条目本身并非失效；在 7 条篇幅下让位于更新的官方动态。Gemini 4 Argon 的后续进展由 Carbon 条目承接，腾讯 WorkBuddy 的后续进展由 10 月 29 日腾讯公告承接。
- 新增：OpenAI LifeVal、网站 AI 训练偏好共同信号、腾讯云企业 AI 公告、Google Gemini 4 Carbon、Microsoft Copilot harness、百度文心 Unlimited OCR 2。

页面展示的日期为事件日期，排序依据原始发布时间；两者均在详情中单独列出。厂商的性能、规模和效果陈述均按官方主张处理，不视为独立验证。

## 本地预览

直接打开 `index.html`，或运行：

```sh
python -m http.server 8766 --bind 127.0.0.1
```

## GitHub Pages

使用 `main` 分支根目录发布。`.nojekyll` 用于直接提供静态文件。
预期默认网址为 `https://yeeica.github.io/codex_test1/`，以 GitHub Pages 实际部署结果为准。
