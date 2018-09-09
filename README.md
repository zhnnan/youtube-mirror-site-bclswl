# YouTube Mirror
## You2PHP

**用于Ｈｅｒｏｋｕ以部署ＹｏｕＴｕｂｅ镜像站**

**This project is to deploy YouTube Mirror on HEROKU.**

提供现成的两个 YouTube API（2018年9月9日再次更新API，请注意）：

> AIzaSyBy2VkQXTgCWkfWfgejVUcKH5GuO2DFAds

> AIzaSyAurg5k-lp9qQxA_IpC5x48YZ3-cslEQ5Q

You2PHP原版中有一个名为4k.php的脚本，实质上，4k.php是一个在线代理脚本。本人并不提倡滥用Heroku的免费服务，故将其移除。**另，这份源码中`<head>`部分加上了`nofollow`标签，这样可以有效防止搜索引擎抓取。这是原版里所没有的。**

Fork 此项目后，请前往修改 `/web/config.php` ，填入上述 API 中的任意一个，以及您的网站信息，然后将其部署至 Heroku。

## 备注

Youtube API是有每日固定配额的，如果您发现你的网站出现突然无法获取视频等情况，请等待至美国太平洋时间午夜12点后再试
