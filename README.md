## OSINT FRAMEWORK

Osint Framework（开源情报查询框架）即通过在互联网中公开的信息进行一些事件的调查，它的优势显而易见就是不会与目标主体产生接触、关联，意味着你的调查将不会被他发现，这是不是听起来蛮有意思的！





## 功能介绍

功能大纲包括

- 用户名搜索
- 邮箱账户搜索
- 域名搜索
- IP地址搜索
- 图片/视频/文档搜索
- 社交网站搜索
- 即时通讯
- 身份信息核实
- 约会记录查询
- 电话号码查询
- 公开档案
- 商业档案
- 交通运输
- 高精度定位/地图
- 搜索引擎玩法
- 论坛/博客/IRC
- 档案资料
- 语言翻译
- 元数据
- 手机模拟器
- 数字货币
- 分类信息
- 编码/解码
- 工具
- 恶意文件分析
- 漏洞EXP & 修复建议
- 威胁情报
- OpSec
- 文档资料
- 训练



## 界面截图

其实这是一个非常全面的框架，对于网络安全初学者，是一个不错的探索模式，你可以通过这个框架找到各种你想要的信息源。

再或者，你是一名记者，通过OSINT框架，你可以更快的获得一些公开情报，甚至可以完成一些取证相关的工作。

![image-20220208091540553](https://github.com/B1gM8c/osint/blob/main/img/image-20220208091540553.png?raw=true)

我们拿其中的一个工具，举个例子，我们想找一下`fancypig`这个用户名注册过哪些社交网站，我们可以看这里，这里提供了很多相关工具

![image-20220208091553750](https://github.com/B1gM8c/osint/blob/main/img/image-20220208091553750.png?raw=true)

我们选择第一个`Namechk`工具，这里会打开一个新的网站，目测这里是爬虫实现的，超过90个社交网站账户收集

![image-20220208091618668](https://github.com/B1gM8c/osint/blob/main/img/image-20220208091618668.png?raw=true)

我们这里进行人机身份验证后，点右侧的搜索按钮，然后你就可以看到`fancypig`注册过哪些社交平台，比方说抖音TikTok

![image-20220208091633649](https://github.com/B1gM8c/osint/blob/main/img/image-20220208091633649.png?raw=true)



## 工具类型

Osint Framework下工具主要分为四种类型

- (T)代表需要在本地运行
- (D)代表是Google Dorking语法
- (R)代表需要注册才能使用
- (M)代表搜索需要单独编辑URL链接中的关键词



## OSINT框架其他科普

- [如何使用PhoneInfoga开源引擎搜集手机号信息？](https://www.iculture.cc/sg/pig=6289)
- [想成为侦探？如何通过一张图片找到护照编号？教你玩转Maltego](https://www.iculture.cc/sg/pig=6891)
- [【社工进阶】如何通过Twitter社交软件进行社工](https://www.iculture.cc/sg/pig=7638)



## 欢迎Pull Request

请按照下面的格式提交您使用过的优秀OSINT工具

```
{
  "name": "工具名称",
  "type": "url",
  "url": "http://example.com"
}
```

