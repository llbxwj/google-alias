google-alias
============
这是一个用 PHP 写的谷歌搜索, 主要使用 php 的 curl 和 preg 模块.
Google Alias 意为谷歌的替代品.
##部署##
部署非常简单, 你甚至不用做什么, 只要把你的代码上传到 VPS 或者 web host.
大家都知道 PHP 的免费主机非常多, 部署也非常便捷. 大范围的部署也不成问题, 即使被墙也能迅速的更换主机.
##配置##
config.php 里面有许多个性化的设置, 比如自定义 GET 的键名, 默认的每页结果数, 或者你可以自定义http的header, 是否开启安全搜索等等等
##功能##
1. 限制时间
2. 可定义每页结果数
3. 相关搜索
4. 设置地区和语言
5. url关键字加密
7. html内容加密, 可搜索敏感词
8. 谷歌搜索功能, 使用谷歌的可用ip, 前端会检测ip是否可用, 需要在google_avaiable_ip.txt中添加可用的ip, 用 | 分割.
6. 热键功能, 按`alt+j`可以获得搜索框的焦点, `alt+i`获得焦点并清空.
7. 返回新闻, 视频, 图片的搜索结果(未实现)
8. 兼容特殊搜索, 比如特定的文件(未实现)
9. 待续


##注意##
如果你想部署在自己的网站上, 一定要及时更新可用ip列表.


##BUGs##
1. 没有搜索结果时会报错(fixed)
2. 你找找看


##可用服务##
1. http://googlealias.com
2. http://googlealias.890m.com
3. http://googlealias.tk
3. http://tjt.pagebit.net
6. http://tjt.bugs3.com //不再更新
7. http://tjt.hol.es //不稳定
