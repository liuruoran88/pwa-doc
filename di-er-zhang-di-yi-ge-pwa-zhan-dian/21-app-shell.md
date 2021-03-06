## 2.1 App Shell 架构

该部分主要是为了减少页面的白屏时间，提升用户的交互体验。

### 2.1.1 什么是 App Shell ?

App Shell 架构，通俗的理解可以说是页面的架构，即页面的一个基本结构划分，如图 2-1 所示。从理论上讲，App Shell 是支持用户界面所需的最小的 HTML、CSS 和 JavaScript，如果能够将这些文件缓存在本地，并在用户重复访问时即时、可靠地提供给用户，从而避免用户每次重新加载大量页面资源导致的长时间白屏。所以并不是每次用户访问时都要从网络加载 App Shell，而只需要从网络中加载必要的页面内容或数据等。

### 2.1.2 App Shell 划分?

。。。。。

### 2.1.3 App Shell 怎么开发?

App Shell 架构是构建 Progressive Web App 的一种方式，这种应用能可靠且即时地加载到您的用户屏幕上，与本机应用相似。

App“shell”是支持用户界面所需的最小的 HTML、CSS 和 JavaScript，如果离线缓存，可确保在用户重复访问时提供即时、可靠的良好性能。这意味着并不是每次用户访问时都要从网络加载 App Shell。 只需要从网络中加载必要的内容。

对于使用包含大量 JavaScript 的架构的单页应用来说，App Shell 是一种常用方法。这种方法依赖渐进式缓存 Shell（使用服务工作线程）让应用运行。接下来，为使用 JavaScript 的每个页面加载动态内容。App Shell 非常适合用于在没有网络的情况下将一些初始 HTML 快速加载到屏幕上