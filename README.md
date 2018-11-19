# simple-hugo

> a simple theme for hugo

![](images/screenshot.png)

**Installation with Hugo**

```
$ cd your_site_path/
$ mkdir themes
$ cd themes
$ git clone https://github.com/sunthx/simple-hugo.git
```
**Configuration**

```xml
baseURL = "https://localhost:1313"
languageCode = "zh-cn"
title = "SUNTH'S BLOG"
theme="simple-hugo"

[menu]
    [[menu.main]]
        identifier = "index"
        name = "index"
        title = "主页"
        url="/"
        weight = 1

[params]
    Icp = "京ICP备XXX号-X"

[[params.social]]
    icon = "fa-github"
    icon_pack = "fab"
    link = "https://www.github.com/sunthx"

[[params.social]]
    icon = "fa-weibo"
    icon_pack = "fab"
    link = "https://weibo.com/runningdogman"
```

**License**

MIT
