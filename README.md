# XinWenLianBo_duration

新闻联播**首播**时长数据集

最近在看《R数据科学》，里边介绍了很多数据集。
一直有看新闻联播的习惯，就想着整个新闻联播时长数据集（是不是挺无聊的😂），以前的就不统
计了，从2021-09-26开始吧。

> 以后如果有时间，或许会尝试爬取一下
[新闻联播的主页](https://tv.cctv.com/lm/xwlb/?spm=C52056131267.P4y8I53JvSWE.0.0)，
获取一下往期的实际时长。

## 内容介绍

### duration

播出时长，五列

- datetime 播出时间，符合ISO 8601 标准

- duration 首播节目的实际长度，单位是分钟

- extend 与30分钟相比是否有延长，T（True）或F（False）

- anchorA 屏幕左侧的主播

- anchorB 屏幕右侧的主播

### anchors

主播性别，两列

- name 主播名字。格式为：姓-名

- gender 性别。
