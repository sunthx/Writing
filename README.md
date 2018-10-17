# simple-hugo

> a simple theme for hugo

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
theme="hugo-writing"

[menu]
    [[menu.main]]
        identifier = "index"
        name = "index"
        title = "主页"
        url="/"
        weight = 1

[params]
    Icp = "京ICP备17034094号-1"

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