
### 运行Hugo
在你的站点根目录执行 Hugo 命令进行调试：

``` bash
 hugo server --theme=hyde --buildDrafts
```

### 创建文章
创建一个 about 页面：

``` bash
hugo new about.md
```
about.md 自动生成到了 content/about.md 

#### 正文内容
内容是 Markdown 格式的，+++ 之间的内容是 TOML 格式的，根据你的喜好，你可以换成 YAML 格式（使用 --- 标记）或者 JSON 格式。

创建第一篇文章，放到 post 目录，方便之后生成聚合页面。

```
hugo new post/first.md
```

### 部署
假设你需要部署在 GitHub Pages 上，首先在GitHub上创建一个Repository，命名为：coderzh.github.io （coderzh替换为你的github用户名）。

在站点根目录执行 Hugo 命令生成最终页面：

$ hugo --theme=hyde --baseUrl="http://coderzh.github.io/"