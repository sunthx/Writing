# hugo-writing

> a simple theme for hugo

**Installation with Hugo**

```
$ cd your_site_path/
$ mkdir themes
$ cd themes
$ git clone https://github.com/sunthx/hugo-writing.git
```
**Configuration**

```xml
baseURL = "http://localhost:1313"
languageCode = "zh-cn"
title = "Sunthx Blog"

theme="hugo-writing"
    
[taxonomies]
    tag = "tags"
    category = "categories"

[params]
    categoryName = "categories"
    tagName = "tags"
    Icp = "京ICP证XXYX号"

[[params.social]]
    icon = "fa-github"
    icon_pack = "fab"
    link = "https://www.github.com/sunthx"

[[params.social]]
    icon = "fa-weibo"
    icon_pack = "fab"
    link = "https://weibo.com/runningdogman"
```

**ScreenShot**

![](images/screenshot.png)

**License**

MIT