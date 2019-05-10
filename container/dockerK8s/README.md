## doker 和 k8s
> [原文-->](https://github.com/googege/blog/container/dokerK8s/README.md)

所谓容器，就是一个一个的独立起来的进程，我们都知道进程之间是无法进行沾染的，所以如果使用一个个的容器封装起来的应用就可以独立开来，这就是容器技术。

通常我们使用virtual box等虚拟机，这是我们经常使用的虚拟机技术，但是太过于庞大，往往我们要制作整个的包括系统在内的很大的工程，所以，就太繁琐了，而且启动速度，
占用资源也相对较大，所以才用了容器技术

我们拥有了容器技术，往往就可以实现集群技术，什么是集群技术呢，就是一堆。那么我们该怎么控制这些容器呢？这个时候k8s就诞生了。k8s全程太长我没记住，不过他是由
谷歌开发并且开源的使用GO语言编写的一个系统。ps docker也是GO写的，go大法万岁。😘

**图文解释k8s** ：

![p](https://upload-images.jianshu.io/upload_images/13382653-c7872d6a360d9a36?imageMogr2/auto-orient/strip%7CimageView2/2/w/667/format/webp)

![p](https://upload-images.jianshu.io/upload_images/13382653-80f2268ac078fbc6?imageMogr2/auto-orient/strip%7CimageView2/2/w/672/format/webp)

这里我们要看一下 一个node中有很多内容，但是基本的操作是pod，这里面的docker等就是一个工具一样，所以这个时候又引出来了一句话：docker不是容器，docker是创建容器的工具。

![p](https://raw.githubusercontent.com/googege/blog/master/container/k8s-node.png)
![p](https://raw.githubusercontent.com/googege/blog/master/container/k8s-pod.png)


### docker

### k8s

### docker + k8s

> 感谢
https://blog.csdn.net/huakai_sun/article/details/82378856
