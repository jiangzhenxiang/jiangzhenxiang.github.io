
> 作为程序员，最关心的是ChatGPT如何帮助我们写代码。 
> 
> 亲自体验chatGPT配合vscode后，觉得对日常工作有一些帮助，所以记录一下
# 首先看一下如何使用ChatGPT写代码

打开vscode，安装ChatGPT插件，输入自己账号的秘钥，点login登录，然后提问。

![image.png](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/2647d8784c3b46b698e6f31f02bb7fcf~tplv-k3u1fbpfcp-watermark.image?)

提问：使用vue3 组合式api封住一个useFetch方法。
![image.png](https://p9-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/69d9e48d66624a15ae099aa4dbae55a1~tplv-k3u1fbpfcp-watermark.image?)
可以点击copy复制代码，insert插入到当前文件中。new新建文件。


还可以选中自己的代码，让chatGPT优化代码、找bug、写注释等等。
![image.png](https://p9-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/c9470e3ded584ea88d5bcc05a3b977fb~tplv-k3u1fbpfcp-watermark.image?)

# ChatGPT其他玩法
可以写知乎的回答、写小说，写作文、演讲稿、工作报告、读书笔记、合同、菜谱等。

详见https://github.com/PlexPt/awesome-chatgpt-prompts-zh/blob/main/USEAGE.md

> # 下面正式介绍一下ChatGPT及注册教程、使用教程、相关插件

# ChatGPT介绍
（以下介绍是由ChatGPT生成）

ChatGPT是由OpenAI开发的大型语言模型。它使用了一种称为GPT（Generative Pre-trained Transformer）的机器学习算法进行训练，能够以人类类似的方 式进行对话和生成文本。ChatGPT可以用于各种任务，例如生成文章、回答问题、聊天对话等。它在多个NLP任务上取得了优异的成绩，并且在业界和学术界 都受到了广泛的关注和应用。

# 使用ChatGPT前置条件
- ChatGPT账号
- “科学上网”工具

# ChatGPT注册教程

网上有很多人已经写注册教程了，就不详细描述了。
嫌麻烦的也可以找人买成品账号。

说几个我遇到的坑：

- 代理的ip在部分国家才能登录ChatGPT，如美国、日本等。香港是不行的
- 如果打开页面后，没有注册入口，建议使用浏览器无痕模式试试，或者换个节点

注册教程： https://juejin.cn/post/7198097078005841980
、https://mp.weixin.qq.com/s/zti8CCIY8vAG8NU0YpzpAg




# ChatGPT网页版与 ChatGPT API区别


| ChatGPT网页版 | ChatGPT API |
| --- | --- |
| 响应速度较慢，不稳定 | 稳定性高，响应速度较快 |
| 能够连续对话，有对应上下文 | 不能连续对话 |
| 官网限制访问的区域，中国等一些地区不能访问 | 官方不限制地区，任何地区主机均可使用（但国内openai.com被qiang，还是需要代理） |



# 网页版ChatGPT
地址：https://chat.openai.com/chat 

使用方式：打开后点new chat ，直接输入问题就行。 可以保存多个chat会话，每个会话能够保持对应的上下文，能连续对话。


![image.png](https://p6-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/7b0f433cd5f44415bf61f76a1b7aa284~tplv-k3u1fbpfcp-watermark.image?)

结果

![image.png](https://p6-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/71e1539173c149ae80da97e2f1d6ff18~tplv-k3u1fbpfcp-watermark.image?)

# ChatGPT API
ChatGPT的 API 提供自然语言处理相关的功能，包括问答、文本生成、翻译等。你可以使用我的 API 来实现一些自然语言处理的应用，比如智能客服、语音助手等。

你可以通过 OpenAI 官网申请 API 访问权限，使用我的 API。https://platform.openai.com/account/api-keys


![image.png](https://p6-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/533264756b1b42a490175cb983276e03~tplv-k3u1fbpfcp-watermark.image?)

在此不介绍自己如何使用基于API开发。 

推荐一些ChatGPT相关插件，都是基于api开发的


# VScode插件推荐

## ChatGPT VScode插件
可以在vscode跟chatgpt交互，并将生成的代码快速插入到文件中，而且可以优化代码、找bug等等。

![image.png](https://p6-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/98a8a6ccbd4a448287b597a01eeb69e3~tplv-k3u1fbpfcp-watermark.image?)


安装链接：https://marketplace.visualstudio.com/items?itemName=gencay.vscode-chatgpt 

使用方式：

1、安装完成

2、去官网登录自己账号，生成secret key https://platform.openai.com/account/api-keys 

3、在VScode中配置上一步生成的secret key。点击login。然后就可以使用了

#### 示例1：让ChatGPT写代码

点击vscode侧边栏的chatgpt图标，提问：使用vue3 组合式api封住一个useFetch方法。
然后就可以看到生成的代码了。
![image.png](https://p9-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/69d9e48d66624a15ae099aa4dbae55a1~tplv-k3u1fbpfcp-watermark.image?)
可以点击copy复制代码，insert插入到当前文件中。new新建文件。

#### 示例2：让ChatGPT优化我们的代码
选中我们自己的代码，右键选择 chatgpt: Optimize，然后就能在左侧对话框中看到优化后的代码和解释了。
![image.png](https://p9-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/c9470e3ded584ea88d5bcc05a3b977fb~tplv-k3u1fbpfcp-watermark.image?)

#### 示例3：对选中的代码自定义提问
右键选择 chatgpt：Ad-hoc prompt，然后在顶部的输入框中输入自己的问题，如优化代码。然后在右侧就能看到想要的回答。

![image.png](https://p9-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/c0ef6079c62549a89683f04641f447f7~tplv-k3u1fbpfcp-watermark.image?)

选中package.json，自定义问题，生成readme。
![image.png](https://p9-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/5f4cccd684c0412ea32711354a948628~tplv-k3u1fbpfcp-watermark.image?)


## ChatGPT中文版 VScode插件
中文版安装地址：https://marketplace.visualstudio.com/items?itemName=WhenSunset.chatgpt-china 


## Code GPT VScode插件
跟上面的类似插件，不多做介绍了。

安装地址： https://marketplace.visualstudio.com/items?itemName=DanielSanMedium.dscodegpt

# Jetbrains webstorm插件
Jetbrains IDE相关插件 


安装地址https://plugins.jetbrains.com/plugin/20603-chatgpt 

说明文档https://github.com/obiscr/ChatGPT/blob/main/README_CN.md

# Chrome 插件
## chatgtp for google
在搜索引擎结果中同时显示ChatGPT的回答

安装链接：https://chrome.google.com/webstore/detail/chatgpt-for-google/jgjaeacdkonaoafenlfkkkmbaopkbilf?hl=z

![image.png](https://p6-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/a18bb64bd36d4c8aac0916cd89c11ed8~tplv-k3u1fbpfcp-watermark.image?)

## AIPRM for ChatGPT

为 ChatGPT 添加了一系列策划好的提示模板，包括 SEO、SaaS 等等。很强大

安装地址：https://chrome.google.com/webstore/detail/aiprm-for-chatgpt/ojnbohmppadfgpejeebfnmnknjdlckgj?hl=zh


![image.png](https://p9-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/4d9f79bde7e94f3fbc266fb2be70ca5b~tplv-k3u1fbpfcp-watermark.image?)


![image.png](https://p9-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/5ceb8338c15f4a7ea6111cfc64550b0e~tplv-k3u1fbpfcp-watermark.image?)

# ChatGPT 桌面应用（Mac, Windows and Linux）
https://github.com/lencx/ChatGPT/blob/main/README-ZH_CN.md


![image.png](https://p6-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/444ac78d09e24bd1aadb31c7cb0fb71b~tplv-k3u1fbpfcp-watermark.image?)

# 总结一下

ChatGPT搭配VScode插件，速度快，稳定，官方对地区不限制，生成的代码能快速插入到文件中。写代码的好帮手。缺点是不能连续对话。 

ChatGPT网页版，优点是能连续连续对话，聊天体验更好，能体验原汁原味的人工智能聊天机器人。缺点是限制部分地区使用、不稳定，速度慢。


# 相关资料

汇总了chatgpt相关资源https://github.com/humanloop/awesome-chatgpt 

ChatGPT 中文调教指南：https://github.com/PlexPt/awesome-chatgpt-prompts-zh 

