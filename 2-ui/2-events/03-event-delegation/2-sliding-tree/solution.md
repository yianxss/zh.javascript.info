解决方案分为两个部分。

1. 将每个树节点的标题都包装到 `<span>` 中。然后我们可以在 `:hover` 上使用 CSS 样式，并精确地处理文本上的点击事件，因为 `<span>` 的宽度恰好是文本的宽度（与没有宽度不同）。
2. 为 `tree` 的根节点设置一个处理程序，来处理 `<span>` 标题上的点击事件。
