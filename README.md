# cnsentiDemo


这是使用streamlit库将中文情感分析[**cnsenti** 部署到网络世界，可**在线提供简单的中文文本的情绪及情感计算**。

> **streamlit库**(https://docs.streamlit.io/en/stable/)， 是目前简单易用的数据可视化web框架，比flask和django少了很多的扩展性，但是容易学习上手，适合初学者把玩。



[**网址**](https://cnsenti.herokuapp.com/)

[**使用教程** ](https://www.bilibili.com/video/bv17V411H7sZ)



<br>



# 网站

现在技术有限，该网站大致内容分为三部分

- 准备数据
- 数据分析
    - 情感分析
    - 词云图
- 谢谢支持



<br>





# 本地使用

本网站的**cnsentiDemo项目文件夹**的文件有



```
- main.py
- cnsenti_example.csv
- 大邓和他的Python.png
- requirements.txt
- 其他文件
```



将cnsentiDemo项目下载，在**电脑本地离线使用cnsenti的方法**

1. 下载解压到桌面desktop
2. 命令行, 执行 ``cd desktop/cnsentiDemo``
3. 命令行，执行 ``pip3 install -r requirements.txt``
4. 命令行, 执行 ``streamlit run main.py``
5. 根据命令行的提示，复制粘贴网址到桌面。我这里是 ``**http://localhost:8501**``
6. 浏览器打开效果就会与视频等同



上述过程中，Mac和Win会有一些缺点导致无法使用，需要根据命令行提示解决各自系统的小问题，例如



1. Win需要使用64位的Python
2. Mac可能需要安装Xcode-install
3. 其他可能的问题




<br>





# Web部署方法

如果想将自己的streamlit项目部署成网站，可以使用Heroku和github帮助你完成人生第一个小网站。操作方法：

1. 将写好的streamlit项目上传至github自有仓库
2. Heroku注册账号
3. 点击Heroku网页右上角New， 选择Create new app
4. 绑定github，连接github里的streamlit项目
5. 部署

部署方法也可参考  [Youtube视频](https://www.youtube.com/watch?v=zK4Ch6e1zq8&list=PLtqF5YXg7GLmCvTswG32NqQypOuYkPRUE&index=5)


# 如果

如果您是经管人文社科专业背景，编程小白，面临海量文本数据采集和处理分析艰巨任务，个人建议学习[《python网络爬虫与文本数据分析》](https://ke.qq.com/course/482241?tuin=163164df)视频课。作为文科生，一样也是从两眼一抹黑开始，这门课程是用五年时间凝缩出来的。自认为讲的很通俗易懂o(*￣︶￣*)o，

- python入门
- 网络爬虫
- 数据读取
- 文本分析入门
- 机器学习与文本分析
- 文本分析在经管研究中的应用

感兴趣的童鞋不妨 戳一下[《python网络爬虫与文本数据分析》](https://ke.qq.com/course/482241?tuin=163164df)进来看看~



# 更多

- [B站:大邓和他的python](https://space.bilibili.com/122592901/channel/detail?cid=66008)

- 公众号：大邓和他的python

- [知乎专栏：数据科学家](https://zhuanlan.zhihu.com/dadeng)
