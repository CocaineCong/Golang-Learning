@[TOC]

# 写在前面
> 这篇文章是我自己亲身经历这样去学go的，本人是从`20年的10月份`开始入坑go语言的，当时的资料真的少，现在关于go语言的资料已经很多了。
> 我就在把我自己的学习路线稍微梳理一遍，我个人觉得，学完之后，**像深信服，b站，得物什么的应该是没什么问题，** 但如果是`字节，腾讯，阿里这种就除了一些硬性条件之外，自己再刷多点题，背多点八股了。`

## 全部练习项目都在github这个仓库中`https://github.com/CocaineCong/Golang-Learning`

**适合大一、大二、或是其他语言转go的同学**

# 1. 【第一轮】基础部分
## 1.1 教程

Go语法这方面一定要注重好基础，比如数组，切片，map，chan这种基础的数据类型。

语法入门可以看这个 [入门教程](https://www.bilibili.com/video/BV1SS4y1T7kJ)，主要是挺新的这个教程。

![在这里插入图片描述](https://img-blog.csdnimg.cn/4bafac6684e4471791c59f924b1e0a2f.png)

附上我自己做的思维导图
![请添加图片描述](https://img-blog.csdnimg.cn/2254fcf934c742fbb2f1ae33932812de.png)

## 1.2 练习
可以选择 PTA 上面的题目来进行练习。

[PTA练习](https://pintia.cn/problem-sets/994805046380707840)

![在这里插入图片描述](https://img-blog.csdnimg.cn/3cb0e763329c48fd94d3b9ec5517f18a.png)

我的 Go语言入门 60题 专栏。[入门60题](https://blog.csdn.net/weixin_45304503/category_11294773.html)

![在这里插入图片描述](https://img-blog.csdnimg.cn/831f8ce0eb7f4395a35d812c5043987b.png)

# 2. 【第二轮】网络爬虫
## 2.1 教程
用 go 去做爬虫，主要是为了`了解http的请求与响应`，了解 web中参数的传递，页面的布局，点击逻辑等等... 为之后的web开发奠定基础用的。

同样的，我们也可以学习到并发爬虫，这样也用到了我们go语言`天生支持高并发`的特性。

这个是我录制的一个关于Go语言爬虫的练习 [Go语言爬虫](https://www.bilibili.com/video/BV1CR4y1g7wB/)

![在这里插入图片描述](https://img-blog.csdnimg.cn/e0901d3539084d729095ff34e07aca3e.png)
对应的案例的代码也放在了github上 [GitHub案例](https://github.com/CocaineCong/Go-Spider-Demo)

这个是我自己写的关于爬虫的一个思维导图的总结。
![请添加图片描述](https://img-blog.csdnimg.cn/832f52c810a24568b25d763ed484e90b.png?x-oss-process=image/watermark,type_ZHJvaWRzYW5zZmFsbGJhY2s,shadow_50,text_Q1NETiBA5bCP55Sf5Yeh5LiA,size_20,color_FFFFFF,t_70,g_se,x_16)


## 2.2 mod 管理第三方包

**到这里之后，我们可能会用到第三方的工具包，这时候我们就要用go mod去管理我们的第三方包文件了，而go mod如何去理解？**

这个视频我觉得讲的很不错了：[Go Mod理解](https://www.bilibili.com/video/BV1w64y197wo)


![在这里插入图片描述](https://img-blog.csdnimg.cn/71849a99e95944a5a05eebc49c885c75.png)

## 2.3 git 机制

那么我们之后还需要用到`git`，像`git`我们应该怎么学习呢？
我的建议是**git一定要自己多用，多记录一些常用的命令。**
教程的话，可以看看这个git教程：[GIT教程](https://www.bilibili.com/video/BV1FE411P7B3)

![在这里插入图片描述](https://img-blog.csdnimg.cn/671ecb2cb4424c1ab05a42500f18ab0e.png)

一开始用 git，我们可以先用熟 commit、push、pull 啥的，之后再用多一些在`项目版本的管理`上，之后我们就可以再学去做`解决冲突`。

# 3. 【第三轮】备忘录
接下来就到我们的后端开发了，前面`第一轮打好了基础`，`第二轮懂了一些网站的请求与响应`，接下来就可以进行开发了。

这一轮我们重点是放在规范上，比如**命名规范，项目结构规范，接口定义规范，返回规范**等等...

这一轮其实我们就做一个简单的备忘录而已。在熟悉规范的同时，`以练带学`，不断通过项目去学习框架，gin、gorm。

跟着敲就好了。

![在这里插入图片描述](https://img-blog.csdnimg.cn/c67f57e45bcb429985cb2319a5883c03.png)


视频：[gin+gorm备忘录 视频教程](https://www.bilibili.com/video/BV1GT4y1R7tX)
Github地址：[gin+gorm备忘录 源码](https://github.com/CocaineCong/TodoList)

# 4. 【第四轮】商城 or 视频网站
当我学习完规范之后，我们就开始深入学习业务了，这时候我们就可以开始做一个大一点的项目，比如商城，视频网站之类的。

这个时候我们就可以去接触redis、docker这些比较流行的技术了。

![在这里插入图片描述](https://img-blog.csdnimg.cn/340eb2e20be84ee3ac4f981c2be022ae.png)


[视频链接](https://www.bilibili.com/video/BV1Zd4y1U7D8)

[源码地址](https://github.com/CocaineCong/gin-mall)


# 5. 【第五轮】IM 即时通信
除了基础业务的处理之外，我们还要了解 websocket 通信，这个也是一个必不可少的技术。
![在这里插入图片描述](https://img-blog.csdnimg.cn/2d92b96c80dc4ad78feef93f903861e4.png)

[视频地址](https://www.bilibili.com/video/BV1BP4y1H7gV)
[Github源码地址](https://github.com/CocaineCong/gin-chat-demo)


# 6. 【第六轮】微服务
在学习完业务处理，ws处理之后，我们再开始微服务框架的学习。理解proto的作用，理解 rpc 的过程，服务发现，服务注册等等...

![在这里插入图片描述](https://img-blog.csdnimg.cn/6386a244d1ec4b08ad835624b4e05772.png)
[视频链接](https://www.bilibili.com/video/BV1fS4y177og)
[Github源码地址](https://github.com/CocaineCong/gRPC-todoList)

# 7.【第七轮】底层架构
在我们熟悉完上面的技术框架之后，我们有了广度，**在我们有了广度的条件下，我们可以往其中一个方向进行深度的专研。**

比如说 极客兔兔的手撕框架，可以自己找一个来实现。
这个就很完美了 [极客兔兔链接](https://geektutu.com/post/gee.html)
![在这里插入图片描述](https://img-blog.csdnimg.cn/a0569b9afd8a4d359846e6d383296d21.png)

这些是提升自己业务能力的一个方法流程，但是如果是要做工作、实习的话，还是另外的流程去学习，不单单是这个，`为什么我精通curd ？还找不到工作？` 这个我们下一次再总结说说，**因为这些其实只是入门而已，只是扩展我们的广度，还没能很好的深入学习。**



