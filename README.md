# 前言(必看)
## 频道：https://t.me/KingRan521
君子慎独，不欺暗室， 卑以自牧，含章可贞。 

大丈夫立于天地之间， 当仰天地浩然正气， 行光明磊落之事。 

克己，慎独，守心，明性。 

以克人之心克己， 以容己之心容人。

言尽于此，不想解释也不想回答！！！

建议不要使用本库。免生是非！！！

建议不要使用本库。免生是非！！！

建议不要使用本库。免生是非！！！



KR
完整库，集合可用脚本，账号互助，不添加助力池，适用于青龙面板。

频道：https://t.me/KingRan521  

国内鸡：（TX云等）

修改青龙 config.sh 文件中的GithubProxyUrl参数为：
GithubProxyUrl=""

https://gh.fakev.cn/
https://hub.fastgit.xyz/
https://hub.0z.gs/
没有代理的可以使用上面镜像站

然后拉库命令填写下方代码：

ql repo https://gh.fakev.cn/KingRan/KR.git "jd_|jx_|jdCookie" "activity|backUp" "^jd[^_]|USER|utils|function|sign|sendNotify|ql|JDJR"

或者：
ql repo https://hub.fastgit.xyz/KingRan/KR.git "jd_|jx_|jdCookie" "activity|backUp" "^jd[^_]|USER|utils|function|sign|sendNotify|ql|JDJR"

国外鸡直接填写下方代码

ql repo https://github.com/KingRan/KR.git "jd_|jx_|jdCookie" "activity|backUp" "^jd[^_]|USER|utils|function|sign|sendNotify|ql|JDJR"

最近遇到使用代理加速拉库会出现卡更新的情况。
出现类似图片情况的解决方案：进入容器文件夹后点击repo文件夹删除整个库文件后重新拉库即可。


#### 无互助池，无需配置互助码，账号之间内部互助。

### 目前有加密的如下（不放心请禁用）

1.jd_zdjr.js   （组队瓜分）

2.jd_cjzdgf.js （组队瓜分）

3.jd_zjd.js   （赚京豆）

4.jd_fan.js  （粉丝互动）

5.jd_js_sign.js （极速版签到提现）

6.jd_jx_sign.js （京东-京喜双签）

7.jd_computer.js （电脑配件通用任务）

#### 另外涉及开卡均有部分加密。


### 拉取(js py ts)青龙 config.sh 文件中修改

ql repo命令拉取脚本时需要拉取的文件后缀，直接写文件后缀名即可

`RepoFileExtensions="js py ts"`


### 腾讯云活动：

2核2G4M/40RMB/一年，仅限新用户，一个实名可以注册3个新用户账号

抢购地址：https://sourl.cn/RFwHRZ


### 取关店铺和商品 使用说明（待完善）
通过设置变量`UN_SUBSCRIBES`来进行`商品一次性取消数量`, `店铺一次性取消数量`, `商品取关忽略列表`, `店铺取关忽略列表`四项内容的自定义设置，以'&'、回车或'\n'隔开。

|      设定项      |   类型   |            说明            | 示例                             |
| :--------------: | :------: | :------------------------: | -------------------------------- |
|  商品取消数/次   |   数字   |     默认20，为0不取消      | 20                               |
|  店铺取消数/次   |   数字   |     默认20，为0不取消      | 19                               |
| 商品取关忽略列表 | JSON数组 | 按商品详情页的商品编号设置 | ["100016814096", "100009667851"] |
| 店铺取关忽略列表 | JSON数组 |       按店铺名关键字       | ["华硕", "丽台京东自营旗舰店"]   |


