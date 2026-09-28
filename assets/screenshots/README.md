# Screenshot Upload Guide

请将脱敏后的展示图片放在本目录，推荐使用以下名称：

1. `01-cover.webp`：项目首页或完整画布；
2. `02-clarification.webp`：Agent 需求澄清；
3. `03-plan-confirmation.webp`：多步骤计划与确认；
4. `04-canvas-workflow.webp`：图片/视频工作流；
5. `05-generation-result.webp`：多模态生成结果；
6. `06-job-queue.webp`：任务队列、重试或恢复；
7. `07-operations.webp`：健康状态或运维页面。

上传前检查并隐藏：API Key、Token、Cookie、邮箱、服务器 IP、用户 ID、项目 ID、
供应商余额、OSS 地址、真实人物和其他不适合公开的数据。建议图片宽度控制在 1600px 左右，
转换为 WebP，并添加低透明度的 `LongTV Demo` 水印。

上传完成后，编辑根目录 `README.md`，按下面格式插入图片：

```markdown
![Agent 需求澄清](assets/screenshots/02-clarification.webp)
```
