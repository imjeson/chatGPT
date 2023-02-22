#=======
#chatGPT中文资料-gptnb.com  
#=================
#
#[](#目錄)目录
#---------
#
#*   [官方资源](#%E5%AE%98%E6%96%B9%E8%B3%87%E6%BA%90)
#*   [在任何地方使用 ChatGPT](#%E5%9C%A8%E4%BB%BB%E4%BD%95%E5%9C%B0%E6%96%B9%E4%BD%BF%E7%94%A8-chatgpt)
#    *   [浏览器扩展套件](#%E7%80%8F%E8%A6%BD%E5%99%A8%E6%93%B4%E5%85%85%E5%A5%97%E4%BB%B6)
#    *   [桌面应用程序](#%E6%A1%8C%E9%9D%A2%E6%87%89%E7%94%A8%E7%A8%8B%E5%BC%8F)
#    *   [编辑器](#%E7%B7%A8%E8%BC%AF%E5%99%A8)
#    *   [启动器（Launcher）扩展套件](#%E5%95%9F%E5%8B%95%E5%99%A8launcher%E6%93%B4%E5%85%85%E5%A5%97%E4%BB%B6)
#    *   [聊天机器人](#%E8%81%8A%E5%A4%A9%E6%A9%9F%E5%99%A8%E4%BA%BA)
#    *   [反向代理网站（反向代理）](#%E5%8F%8D%E5%90%91%E4%BB%A3%E7%90%86%E7%B6%B2%E7%AB%99reverse-proxy)
#*   [扩展 ChatGPT 功能](#%E6%93%B4%E5%B1%95-chatgpt-%E5%8A%9F%E8%83%BD)
#*   [延展应用](#%E5%BB%B6%E4%BC%B8%E6%87%89%E7%94%A8)
#*   [提示词（提示）](#%E6%8F%90%E7%A4%BA%E8%A9%9Eprompts)
#*   [开发工具（API、SDK）](#%E9%96%8B%E7%99%BC%E5%B7%A5%E5%85%B7apisdk)
#*   [实验](#%E5%AF%A6%E9%A9%97)
#*   [贡献](#%E8%B2%A2%E7%8D%BB)
#
#* * *
#
#[](#官方資源)官方资源
#-------------
#
#*   [ChatGPT 官方网站](https://chat.openai.com/)
#*   [ChatGPT 发布部落格文章](https://openai.com/blog/chatgpt/)
#
#[](#在任何地方使用-chatgpt)在任何地方使用 ChatGPT
#-----------------------------------
#
#### [](#瀏覽器擴充套件)浏览器扩展套件
#
#*   [ChatGPT for Google](https://chrome.google.com/webstore/detail/chatgpt-for-google/jgjaeacdkonaoafenlfkkkmbaopkbilf)：Chrome/Edge/Firefox浏览器扩展套件，在Google搜索结果旁并列ChatGPT回复。（[Firefox扩展套件](https://addons.mozilla.org/en-US/firefox/addon/chatgpt-for-google/)、[程序代码](https://github.com/wong2/chat-gpt-google-extension)）
#*   [ChatGPT Extension](https://chrome.google.com/webstore/detail/chatgpt-chrome-extension/cdjifpfganmhoojfclednjdnnpooaojb)：Chrome浏览器扩展套件，在右上角弹窗快速使​​用ChatGPT。（[程序码](https://github.com/kazuki-sf/ChatGPT_Extension)）
#*   [ChatGPT Everywhere](https://github.com/gragland/chatgpt-everywhere)：Chrome浏览器扩展套件，在任何输入框使用ChatGPT。（[demo](https://twitter.com/gabe_ragland/status/1599466486422470656)）
#
#### [](#桌面應用程式)桌面应用程序
#
#*   [ChatGPT Desktop App](https://github.com/sonnylazuardi/chatgpt-desktop)：Windows/MacOS 桌面选择单应用程序。使用 Tauri 和 Rust 开发。
#*   [chatgpt-mac](https://github.com/vincelwt/chatgpt-mac)：MacOS 选项列表应用程序。
#
#### [](#編輯器)编辑器
#
#*   [ChatGPT for VSCode](https://github.com/mpociot/chatgpt-vscode)：VSCode 扩展套件。（[demo](https://twitter.com/marcelpociot/status/1599180144551526400)）
#*   [intellij-chatgpt](https://github.com/LiLittleCat/intellij-chatgpt)：JetBrains 编辑器扩展套件。
#*   [chatgpt.vim](https://github.com/terror/chatgpt.nvim)：Neovim插件，在Neovim缓冲区里使用ChatGPT。
#*   [docGPT](https://github.com/cesarhuret/docGPT)：Google 文件编辑器插件，在 Google Docs 内使用 ChatGPT。
#
#### [](#啟動器launcher擴充套件)启动器（Launcher）扩展套件
#
#*   [ChatGPT Raycast 扩展](https://github.com/abielzulio/chatgpt-raycast)：Raycast 扩展套件。
#
#### [](#聊天機器人)聊天机器人
#
#*   [Twitter/@ChatGPTBot](https://twitter.com/ChatGPTBot)：Twitter 推特机器人。（[程序式码](https://github.com/transitive-bullshit/chatgpt-twitter-bot)）
#*   [ChatGPT ProBot](https://github.com/oceanlvr/ChatGPTBot)：GitHub APP。输入`/chatgpt`来与ChatGPTBot 交流。
#*   [chatgpt-telegram](https://github.com/m1guelpf/chatgpt-telegram)：执行自己的GPTChat Telegram 机器人，只需要一步指令。
#*   [ChatGPT Telegram Bot in AWS Lambda](https://github.com/franalgaba/chatgpt-telegram-bot-serverless) : ChatGPT Telegram 机器人，执行在 AWS Lambda 上。支持语音消息和 Markdown 显示。
#*   [chatbot-telegram](https://github.com/Ciyou/chatbot-telegram) : 一键运行ChatGPT Telegram Bot，使用`Deno`和`TypeScript`创建。
#*   [chatGPT-discord-bot](https://github.com/Zero6992/chatGPT-discord-bot)：整合自己的 Discord 机器人。
#*   [wechat-c​​hatgpt](https://github.com/fuergaosi233/wechat-chatgpt)：ChatGPT 的微信Bot。安装完成依赖后只需要填写OpenAI账号密码和微信扫描码就可以使用。
#*   [ChatGPT LINE Bot](https://github.com/isdaviddong/chatGPTLineBot)（中文内容）：建立自己的ChatGPT LINE机器人。
#*   [gpt-ai-assistant](https://github.com/memochou1993/gpt-ai-assistant)（中文内容）：在10分钟内打造自己的GPT LINE机器。
#
#### [](#反向代理網站reverse-proxy)反向代理网站（反向代理）
#
#*   [gpt.chatapi.art](https://gpt.chatapi.art/)：ChatGPT 反代理网站，在被 OpenAI 限制权限的区域也可以使用 ChatGPT，无需登录账号。
#
#[](#擴展-chatgpt-功能)扩展 ChatGPT 功能
#-------------------------------
#
#*   [ShareGPT](https://sharegpt.com/) : 轻松分享 ChatGPT 对话记录。（[demo](https://twitter.com/steventey/status/1599816553490366464)）
#*   [ChatGPT export to PNG/PDF/HTML](https://github.com/liady/ChatGPT-pdf)：Chrome浏览器扩展套件，能将ChatGPT记录下载成PNG、PDF文件，或生成可分享的链接。
#*   [ChatGPT Advanced](https://github.com/qunash/chatgpt-advanced) : Chrome浏览器扩展套件，在ChatGPT页面同时显示网页搜索结果。
#*   [TampermonkeyUserscripts/ChatGPTVoiceInput](https://github.com/doggy8088/TampermonkeyUserscripts/blob/main/src/ChatGPTVoiceInput.user.js?fbclid=IwAR2sYE_CIOTdhNlRqaYwJ3eh-foa4O7ZHukYcc1dXLcU8IHLIDOt52gdAdQ)（中文内容）: Tampermonkey脚本，ChatGPT语言输入界面（支持中/英/日/韩语）。
#
#[](#延伸應用)延展应用
#-------------
#
#*   [summarize.site](https://chrome.google.com/webstore/detail/summarize/lmhkmibdclhibdooglianggbnhcbcjeh)：Chrome浏览器扩展套件，总结网页内容、给出摘要。
#*   [commitgpt](https://github.com/RomanHotsiy/commitgpt)：自动生成commit消息。
#*   [chatgpt-action](https://github.com/kxxt/chatgpt-action) : Github Action，让 ChatGPT 审核你的 PR。
#*   [StackExplain](https://github.com/shobrook/stackexplain) : 让 ChatGPT 解决错误消息的命令列表工具。
#
#[](#提示詞prompts)提示词（提示）
#----------------------
#
#*   [showGPT](https://showgpt.co/) : 搜索优质提示词的网站，你也可以轻松上传更多提示词。
#*   [awesome-chatgpt](https://github.com/saharmor/awesome-chatgpt) : 各种 ChatGPT 提示词使用法的文章和想法。
#*   [Awesome ChatGPT Prompts](https://github.com/f/awesome-chatgpt-prompts) : ChatGPT 提示词清单。
#
#[](#開發工具apisdk)开发工具（API、SDK）
#----------------------------
#
#*   [PyChatGPT](https://github.com/rawandahmad698/PyChatGPT)（Python）：轻量化、基于TLS的ChatGPT API可以在您的CLI中使用，不需要使用浏览器或验证金针。
#*   [pip/revChatGPT](https://github.com/acheong08/ChatGPT)（Python）：与 OpenAI 的 ChatGPT API 交互的轻量化套件。采用逆向工程手工法。
#*   [npm/chatgpt](https://github.com/transitive-bullshit/chatgpt-api)（Node.js）：Node.js 客户端。
#*   [ChatGPT API Dart](https://github.com/MisterJimson/chatgpt_api_dart)（飞镖）：Dart 客户端。
#*   [go-chatgpt](https://github.com/abhayptp/go-chatgpt) (Golang): Golang 客户端。
#
#[](#實驗)实验
#---------
#
#*   [gptlang](https://github.com/forrestchang/gptlang) : 试验是不能利用ChatGPT 建立一个程序式语言的试验。
#
#* * *
#
#![alt 属性文本](https://raw.githubusercontent.com/imjeson/chatGPT/main/_images/weixin.png "更多咨询，欢迎关注")

