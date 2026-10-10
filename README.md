# 日常集 · 生活工作台（源码备份）

本仓库是 [WorkBuddy](https://www.workbuddy.cn)「资料库」搭建的集成式生活工作台的**页面源码备份**，仅用于版本管理与留存，**不是可独立运行的部署**。

## 在线运行入口（数据在线存储、多端同步）
https://workbuddy.link/p/NSuPJxJiW6EzSCQIfwidr1

## 包含的模块
今日概览 / 记账理财 / 习惯健康 / 减脂健身 / 日程统筹 / 待买清单 / 书影音收藏

## 重要说明
- 数据存储在 WorkBuddy 资料库的 10 张线上数据表，页面通过平台注入的 `window.__SMART_PAGE__.database` SDK 读写。
- 因此本 `life_workbench.html` **不能**直接放到 GitHub Pages 等外部环境运行（脱离平台会缺少 SDK 与鉴权，数据读不到）。如需使用，请在 WorkBuddy 内打开上面的在线链接。
- 备份数据：页面顶栏「导出」按钮可将全部云端数据导出为 JSON 落到本地。

> 此仓库由 WorkBuddy 同步生成，仅作源码留存。线上以资料库页面为准，请勿手动改 `life_workbench.html` 后期望同步回线上。
