---
title: 用 Chaos Mesh 测试 Apache APISIX 的恢复能力
url: https://apisix.apache.org/articles/Test-Apache-APISIX-Resilience-With-Chaos-Mesh
date: '2021-08-06'
author: ''
feed_url: https://apisix.apache.org/articles/rss.xml
---
Apache APISIX 是领先的 API 网关 OSS 之一。APISIX 使用了不同种类的测试，包括单元、e2e 和模糊测试，当一些不正常但不可避免的情况发生时，例如网络故障、IO 压力或 pod 故障，APISIX 会如何表现。因此，在这里我们使用 Chaos Mesh，一个基于 Kubernetes 的混沌工程平台，可以顺利地注入不同种类的混沌，并将其整合到我们的 CI 管道中。在这个讲座的最后，听众会了解到混沌工程会在哪些方面给 API 网关带来好处，以及如何将混沌网整合到你自己的测试管道中。
