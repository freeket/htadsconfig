GitHub读取资源文件
2018年12月25日 14:27:10 zhenyu-s5 阅读数 80
一：我想做什么

目的：直接获取我上传到GitHub上的代码，而不是打开那个代码所在的页面。

二：解决

这样写：https://raw.githubusercontent.com/:owner/:repo/master/:path

例子：

  我的GitHub上的地址是：https://github.com/czy19950220/study/blob/master/src/assets/js/jsTwo.js

想要直接获取那里面的js文件就是：https://raw.githubusercontent.com/czy19950220/study/master/src/assets/js/jsTwo.js
解决问题。适用于想要写自己的静态网站，可以直接在GitHub上修改关键的代码然后自己的网站就更新了。

https://github.com/czy19950220/study/blob/master/src/assets/js/jsTwo.js
https://raw.githubusercontent.com/czy19950220/study/master/src/assets/js/jsTwo.js

https://github.com/freeket/htadsconfig/blob/master/config_gpads/config.json
https://raw.githubusercontent.com/freeket/htadsconfig/blob/master/config_gpads/config.json

https://github.com/freeket/htadsconfig/blob/master/config_gpads/config.json
https://raw.githubusercontent.com/freeket/htadsconfig/blob/master/config_gpads/config.json