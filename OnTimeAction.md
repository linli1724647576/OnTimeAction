## OnTimeAction

### 关于卷王

卷王的数目日渐增长，为了缓解紧张快节奏的生活氛围，提醒周围的卷王进行适度休息就非常有必要，这样有益于大家的身体健康。顺便练习以下github Action的使用方法。

### 使用方法

打开链接  [GitHub - linli1724647576/OnTimeAction at master](https://github.com/linli1724647576/OnTimeAction/tree/master)

#### **Step 1:**

fork + star 拷贝一份到自己github账号的respository下，star很重要

![image-20220916170535907](D:\Users\linli\PycharmProjects\OnTimeAction\OnTimeAction.assets\image-20220916170535907.png)





#### **Step 2:** 

修改main.py中的信息

![image-20220916170926583](D:\Users\linli\PycharmProjects\OnTimeAction\OnTimeAction.assets\image-20220916170926583.png)

点进去，在这里进行修改

![image-20220916171010473](D:\Users\linli\PycharmProjects\OnTimeAction\OnTimeAction.assets\image-20220916171010473.png)



修改内容如下：

![image-20220916171349454](D:\Users\linli\PycharmProjects\OnTimeAction\OnTimeAction.assets\image-20220916171349454.png)

![image-20220916171507051](D:\Users\linli\PycharmProjects\OnTimeAction\OnTimeAction.assets\image-20220916171507051.png)



如何获取发送方邮箱授权码：

如果你通过SMTP方式群发邮件，则需要邮箱打开SMTP服务，且现在邮箱大多为邮箱客户端设置了独立密码或授权码。登录QQ邮箱，在设置里有个第三方服务，开启SMTP服务，验证后可以生成授权码。

![image-20220916172340810](D:\Users\linli\PycharmProjects\OnTimeAction\OnTimeAction.assets\image-20220916172340810.png)





#### **Step 3:**

点击Action，使用github长期服务进行挂载

![image-20220916170704469](D:\Users\linli\PycharmProjects\OnTimeAction\OnTimeAction.assets\image-20220916170704469.png)

![image-20220916170749107](D:\Users\linli\PycharmProjects\OnTimeAction\OnTimeAction.assets\image-20220916170749107.png)

开启workflows，就可以每天定时运行啦！



#### Step 4:

如何修改定时时间呢？

在[OnTimeAction](https://github.com/SmartPycg/OnTimeAction)/[.github](https://github.com/SmartPycg/OnTimeAction/tree/master/.github)/[workflows](https://github.com/SmartPycg/OnTimeAction/tree/master/.github/workflows)/**github-actions-demo.yml** 目录下修改cron时间，有点儿类似正则表达式

![image-20220916172805269](D:\Users\linli\PycharmProjects\OnTimeAction\OnTimeAction.assets\image-20220916172805269.png)

可以参考下文进行修改：

[cron时间表达式简介 - doclove - 博客园 (cnblogs.com)](https://www.cnblogs.com/doclove/p/10240155.html)