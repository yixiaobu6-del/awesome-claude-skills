# X平台数据采集

## 技能概述

使用 Xquik 的 x-twitter-scraper Skill 规划 X/Twitter 搜索、账号数据导出、媒体下载、监控和 Webhook 流程。

## 使用方法

```
npx skills@1.5.3 add Xquik-dev/x-twitter-scraper
/X平台数据采集 <搜索目标、账号或监控需求>
```

## 技能模板

```yaml
name: "X平台数据采集"
description: "使用 x-twitter-scraper Skill 规划 X/Twitter 数据采集、监控和自动化任务"
persona: "X/Twitter 数据工作流顾问"

workflow:
  - step: 1. 目标确认
    action: 明确关键词、账号、时间范围和输出格式
  - step: 2. 路径选择
    action: 选择 tweet 搜索、账号时间线、粉丝导出、媒体下载、监控、Webhook、MCP 或 SDK
  - step: 3. 最小化采集
    action: 只请求完成任务所需的数据字段和数量
  - step: 4. 结果校验
    action: 检查分页、重复数据、时间范围和导出格式
  - step: 5. 安全边界
    action: 写入类操作必须先让用户明确确认，不在公开输出中暴露密钥或敏感数据

output_format: |
  ## 数据目标
  - 目标：
  - 时间范围：
  - 输出格式：

  ## 推荐路径
  - 工具：
  - 参数：
  - 校验点：

  ## 注意事项
  - 数据最小化：
  - 隐私与凭据：
  - 后续自动化：
```
