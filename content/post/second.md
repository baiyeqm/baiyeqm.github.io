---
title: "Java 开发者的磁盘管理经验"
date: 2022-12-19T13:36:20+08:00
draft: false
---

Hugo 有时候会有点问题，看不见 post.

今天我想来聊聊 Java 开发者的一些电脑存储管理的经验。

第一呢，是IDEA的 idea.properties 文件中的几个路径，比如插件存放的路径，索引的路径。这些都可以修改。如果使用默认配置的话，时间长了，C 盘很容易被占满。

第二个呢，是关于 Maven 的本地仓库。也不要放在 C 盘。IDEA 每次打开新的工程师会使用自己默认的 Maven 配置，我们可以新建一个打开项目的模板，在里面配置自己的Maven仓库位置和配置。

第三个，关于 JDK 版本的管理。我们可能会用到多个 JDK，从 1.6, 1.8, 11 到 17 等。可以用一个专门的文件夹来存放JDK。

