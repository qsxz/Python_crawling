## 爬取问题答案
登录知乎之后，想要爬取某个问题下的答案还是挺简单的<br>
以`如何评价即将发布的小米 8？`为例
虽然页面是动态加载的，不过仔细研究就可以发现`数据`都是在一个js文件中返回的<br>
![描述](https://github.com/kunkun1230/Python_crawling/blob/master/%E7%99%BB%E5%BD%95%E7%9F%A5%E4%B9%8E/Screenshots/answers.png)
只要不停地修改`offset`来get红色位置的链接就好了<br>
![描述](https://github.com/kunkun1230/Python_crawling/blob/master/%E7%99%BB%E5%BD%95%E7%9F%A5%E4%B9%8E/Screenshots/answers1.png)
已经根据问题网页的情况进行了update，运行程序，输入想要爬取问题的id就可以爬取此问题下所有的回答啦
