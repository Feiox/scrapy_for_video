爬取国内各大视频网站的视频信息
------------------------------
    本项目始于2018-12-12
    欢迎诸位路过的朋友一起完善这个项目
    视频信息：电视剧，电影，动漫等的各种信息（标题，发布时间，年份，所属区域，导演，演员等信息）
    剧集信息：电视剧，动漫等的剧集信息（例如，《将夜》电视剧下每集的链接，即名称，以及片头，片尾时间等）
    更新信息：由于很多电视剧，动漫还在更新中，所以需要定时不断监控这些视频是否有更新。
 
交流QQ群:962607223 欢迎开发者加入
----------------------------------------
    有任何问题皆可加QQ群交流，或询问群主，我希望同各位一起学习，交流，公共完善这个项目。
   
使用说明
----------------------------------------
    git clone https://github.com/perfect-network/scrapy_for_video.git
    cd scrapy_for_video
    修改tv20181209/spiders/qq_spider.py 中的mysql信息
    再将mysql.sql导入到数据库
    然后保证已经将scrapy, math, json, requests, mysql-connector(若安装失败请百度，或私聊), time 这些库导入即可。。
    scrapy crawl qq #执行腾讯视频的爬虫
 
    
将要爬取的站点
-------------------------------
| 站点 | 链接 | 视频信息 | 剧集信息 | 更新信息 |
| :--: | :-- | :-----: | :-----: | :-----: |
| **腾讯视频** | <http://v.qq.com>          |✔|✔|✖|
| **爱奇艺**   | <http://iqiyi.com>         |✖|✖|✖|
| **优酷视频** | <https://www.youku.com/>   |✖|✖|✖|
| **芒果TV**   | <https://www.mgtv.com/>    |✖|✖|✖|
| **PPTV**     |  <http://www.pptv.com/>    |✖|✖|✖|
| **乐视TV**   | <http://www.le.com/>       |✖|✖|✖|
| **搜狐视频** | <https://tv.sohu.com/>     |✖|✖|✖|
| **咪咕视频** | <http://www.miguvideo.com> |✖|✖|✖|
| **华数TV**   | <https://www.wasu.cn/>     |✖|✖|✖|
| **风行TV**   |  <http://www.fun.tv/>      |✖|✖|✖|
| **暴风视频** |  <http://www.baofeng.com/> |✖|✖|✖|
| **BiliBili** | <https://www.bilibili.com/>|✖|✖|✖|
| **CCTV**     | <http://www.cctv.com/>     |✖|✖|✖|
| **看看视频**  | <http://www.kankan.com/>   |✖|✖|✖|
| **1905视频**  | <http://www.1905.com/>     |✖|✖|✖|