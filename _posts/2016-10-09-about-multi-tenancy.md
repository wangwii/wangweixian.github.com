---
layout: post
title: "关于多租户架构"
tagline: "Multi-tenancy technology in PasS"
comments: false
category: "Architecture"
tags: [设计, 架构]
---
{% include JB/setup %}

多租户（Multi Tenancy/Tenant）是一种软件架构，它是指：
`
运行单个软件实例，但却可以为多个组织服务。在这种架构中，应用程序被设计成能将自己的数据、配置进行虚拟的分区，从而使得每个租户都感觉到自己是在一个私有的、可定制化的应用实例上工作。

要让一个软件支持多租户并非易事，不仅要对它的软件架构进行相应的修改，还需要对它的数据库结构进行特殊的设计，同时在安全和隔离性方面也要有所保障。
`
使用多租户架构：
* 优点：IT资源使用效率的提升，以及节省IT资产的投入成本
* 缺点：系统架构变的更复杂，数据安全的保护更困难；


多租户架构的设计牵涉到两个层面：
* 数据
* 应用/平台