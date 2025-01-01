# 为什么要写这本书

 作为一名逆向+PWN低手，据我在我所能接触到的比赛中观察到，随着CTF赛事的不断发展，逆向中非C/C++的逆向越来越多，譬如go、rust、python等语言逆向。在今年大大小小的比赛中，都出现了非C/C++的逆向和PWN（国赛go语言栈溢出、pyd逆向，长城杯pyd、pythonexe逆向等等），其中python逆向最是热门，也最是特殊的。

 Python的逆向十分特殊，它分为多种逆向，它分为pythonexe逆向，pyc逆向，和pyd逆向，其中pyc逆向较为简单，可以利用pycdc等脚本一比一的转化为python代码，而对于pyd和pythonexe逆向来说，虽然它和我们正常逆向差不多，但是其中存在不少python自定义的固定结构，这些结构是由Cython来生成的，他们存在着一定规律，如果不能很好了解他们，便会加大我们逆向的难度，反之，则会让我们的逆向变得轻而易举。

 而**市面上并没有什么教程来系统的教授如何做python逆向**，每个人都在“浑水摸鱼”般的进行学习，内容极其分散，导致不能很好的学习，于是这本书便出现了，它旨在创建一个共同的平台，来教授/交流Python逆向的经验、脚本、工具。

 当然这本书仅仅是写好了一个框架，还有很多内容还并没有很好的完善，加上作者的能力有限，不能做到面面俱到，在这里还麻烦各位师傅多多提交issue和pr，共同构造这本CTFRePyBook。

# 网页版🌏

为了各位师傅们能更简单的看到这篇教程，我将这篇教程放到的github page上，欢迎各位师傅！

[CTFPyReBook~](https://ctfpyrebook.github.io/CTFPyReBook/index.html)

# 本地构建方法📕

本书是由mdbook工具实现的，可以从github下载mdbook工具在clone下来的目录里直接运行

```shell
mdbook build
```

即可完成本地的构建，具体使用可以看mdbook的教程

# 贡献方法🖊

本书欢迎各位师傅们贡献，师傅们只需要在仓库内的src文件夹内编写markdown文件即可，然后把对应的markdown放入sumary即可，具体使用方法参考mdbook教程，也是十分的简单的。

[指南 - mdBook 文档 (hellowac.github.io)](https://hellowac.github.io/mdbook-doc-zh/zh-cn/index.html)

## QQ群
