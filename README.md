# GitHub markdown 显示深色模式或者浅色模式

GitHub 可以通过在图片链接末尾添加 `#gh-light-mode-only` 和 `#gh-dark-mode-only` 来指定浅色模式深色模式。

下面代码虽然添加了 2 张图片，但是 GitHub 会根据末尾的查询参数只显示一张对应的图片。

```md
![GitHub 浅色模式](./github-light.svg#gh-light-mode-only)
![GitHub 深色模式](./github-dark.svg#gh-dark-mode-only)
```

![GitHub 浅色模式](./github-light.svg#gh-light-mode-only)
![GitHub 深色模式](./github-dark.svg#gh-dark-mode-only)

[GitHub 浅色模式](./github-light.svg#gh-light-mode-only)
[GitHub 深色模式](./github-dark.svg#gh-dark-mode-only)

## 参考链接

- [GitHub 官方文档：Specifying the theme an image is shown to](https://docs.github.com/cn/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#specifying-the-theme-an-image-is-shown-to)
