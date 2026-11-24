# images

个人图床仓库 —— 配合 PicHoro 等上传工具，为博客与文档提供长期稳定的图片外链。

## 外链格式

```
https://raw.githubusercontent.com/Breeze88-hub/images/main/<path>
```

示例（可直接在 Markdown / HTML 里用）：

```markdown
![图](https://raw.githubusercontent.com/Breeze88-hub/images/main/blog/11381710212758_.pic.jpg)
```

## 目录约定

| 路径 | 用途 |
|---|---|
| `blog/` | 博客正文插图（Hexo `source` 引用的长寿命图片） |
| 根目录 | 临时 / 杂项图片，上传工具默认落点（PicHoro 直接上传） |

## 注意

- **不要重命名或用 Git 改写历史**。文件名是上传工具生成的随机串，改名会直接把所有已发布文章里的外链打掉。
- 这里的图片是公开可访问的，不要上传含隐私或凭据的截图。
