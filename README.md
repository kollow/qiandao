# 自动签到

很多网站都有签到的功能，每天你签到后可以获得一定的收益，用于该网站的一些功能获得。但是要每天去点真的很需要恒心与毅力。大家想获得收益，但是又每天不想去登陆点击，所以很多签到项目应运而生，其中比较著名的是[binux](https://github.com/binux) 的 [qiandao](https://github.com/binux/qiandao)

其实这些签到项目基本上就是爬虫功能的应用，所以我自己也就在这里写几个练练手。写这些项目的时候还是有好多心得体会的，都整理一下吧。

## 关于使用

如果使用 binux 的 qiandao 只要在他的网站上面将自己的信息保存就能自动签到了

而我这个是自己按需，将这些脚本部署到自己的VPS上面，建个自动化任务每天执行就OK了

## v2ex

一直是v2ex的用户，每天也会去点签到，终于有一天忍不住了，想自动签到了，又不想在其他网站留下自己的帐号密码，故就想自己写一个。

不过说实在的，v2ex的防自动登录还是做的比较到位的

* Headers 里面的 Refer, Origin
* username, password（post的key）, once 都是每次随机生成的

 > 另外由于2017年之后，v2ex都改成`https`了，所以好多的自动签到工具都失效了，大家也要注意

## 多看阅读

最近想看书，下了个`多看阅读`,上面有个签到的功能，好像可以积分换书，先在这里占个坑，后续完成
