# NataChat
一个简单的，支持 AES 加密通信的 HTML+Python 匿名在线聊天室,直接启动main.py即可

 [English](https://github.com/ZGIT-Network/NataChat/blob/main/README_en.md) | 中文

代码比较基础，新手小白作品，大佬勿喷

前端使用了MDUI，后端仅作消息转发，使用Python编写

演示站点：[https://natachat.zyghit.cn/](https://natachat.zyghit.cn/)

***
#### Server端启动指令：
``python main.py``

Server端Python版本:  **Python3.10以上版本** 

**注意:** 使用前请使用 **pip install** 安装下列模块依赖：
````
websockets
asyncio
logging
string
urllib.parse
base64
Crypto
````
或使用此指令：

``pip3 install -r requirements.txt``

****
#### 关于客户端：

代码库内的``index.html``即客户端，仅包含在线客户端的使用，有更多需要可自行开发

网页客户端默认语言为英文，可自行翻译或提交 issue 让我搞个中文版

***
欢迎大佬协助编写本库，如果觉得有意思麻烦给个star呗！

部署时需要注意：
如果网页配置了ssl证书，那么后端Server也应当配置SSL证书以便于通过wss链接，否则可能会出现问题。
