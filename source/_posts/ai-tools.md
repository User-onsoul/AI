---
title: AI 对话工具集
date: 2023-03-18 06:41:34
---

> 收集 AI 领域优秀的工具, 我们将保持持续更新


### ChatGPT
ChatGPT 由OpenAI官方提供, [详细使用指南](/2023/03/14/chatgpt-register)

### 微软

微软AI生态目前并未对国内开放, 并且使用AI相关功能时，需要在[New Bing](https://www.bing.com/new) 单独申请使用资格。
拥有资格时,在Bing官网下载 Edge。
如果已获取到资格,在国内使用时,需要魔法并安装 Edge 插件 [ModHeader](https://microsoftedge.microsoft.com/addons/search/mode%20header?hl=zh-CN)


``` powershell
# ModHeader 是一款用来修改HTTP请求头信息的插件, 在访问New Bing时以模拟在非大陆其它地区访问！
# 配置
X-Forwarded-For    1.64.33.87
Request URL filter .*://http://www.bing.com/.*

# 请注意不要少字符
```

- [Bing](https://www.bing.com/new) 
- [Skype](https://shiguangpu.com/down/) 下载后关注Bing，可直接交互
- [Office Copilot](https://www.office.com/)

### BaiChat

[Theb.ai](https://theb.ai/)

开发与运营者对接了openai.com ，免费、无限制使用。不过此方式目前来看消耗过大，不确定会开放多久。

### Poe
[Poe](https://poe.com/) 聚合了大部分人工智能聊天机器人，需要付费订阅、梯子

### AI0x0

[ai0x0.com](https://ai0x0.com/) 

AI 聚合工具，目前整合了ChatGPT、Bing、BaiChat。解包分析是使用Node、electron实现。浮动小组件可以悬挂在任何程序窗口之上，在程序窗口输入时提供对应的AI输出整合.

### Notion

[Notion](https://notion.so) 是有名的博客笔记, 近期整合openai.com 的GPT3.5接口。提供了部分免费Token额度。在额度消耗完后，收费 10 美元/月。在写文档时直接插入AI生成的内容体验是很棒的。


### ChatHub

[ChatHub](https://chrome.google.com/webstore/detail/chathub-all-in-one-chatbo/iaakpnchhognanibcahlpcplchdfmgma?hl=zh-CN)	是一款Chrome插件,聚合了多款人工智能聊天机器人。众所周知，Google Chrome 插件市场也是需要魔法的，如果能安装,也代表可使用。下载安装后你需要填写自己的开发Key，ChatHub插件作者连接OpenAI时进行了请求头处理，账号相对安全。