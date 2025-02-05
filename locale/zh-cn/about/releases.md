---
layout: about-release-schedule.hbs
title: 发布
statuses:
  maintenance: '长期维护版'
  active: '长期维护版（主推）'
  current: '当前版'
  pending: '待定'
columns:
  - '发布'
  - '状态'
  - '代号'
  - '首发日'
  - '长期维护版（主推）开始日期'
  - '长期维护版开始日期'
  - '（服务）终止日期'
schedule-footer: 日期可能会发生变化。
---

# 发布

主版本的 Node.js 进入 _当前版_ 将持续六个月的时间，在此期间库作者可以对其进行支持。
六个月之后，奇数版本（诸如 9、11 等）将变为不支持状态，只有偶数版本（诸如 10、12 等）变成 _活跃 LTS_ 状态，并且准备投入使用。
_LTS_ 发布版的状态是“长期维护版”，这意味着重大的 Bug 将在后续的 30 个月内持续得到不断地修复。
上线时应仅使用 _活跃 LTS_ 或者是 _维护 LTS_ 版。Node.js [所有已发布版本截止维护日期](https://github.com/nodejs/Release/#end-of-life-releases)列表由发布工作组维护
