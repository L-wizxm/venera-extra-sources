# Venera Extra Sources

这是一个仅包含官方 `venera-configs` 未收录条目的增量索引。

## 发布

1. 在 GitHub 创建一个公开仓库，例如 `venera-extra-sources`。
2. 将本目录中的 `index.json` 上传到仓库的 `main` 分支根目录。
3. 在 Venera 的漫画源仓库设置中填写：

   ```text
   https://cdn.jsdelivr.net/gh/<你的GitHub用户名>/venera-extra-sources@main/index.json
   ```

也可以使用 GitHub Raw 地址：

```text
https://raw.githubusercontent.com/<你的GitHub用户名>/venera-extra-sources/main/index.json
```

## 说明

- `index.json` 使用各源作者仓库中的脚本直链，不复制脚本文件。
- 第三方站点或解析规则发生变化后，源可能失效。
- 使用前请确认内容来源及使用方式符合当地法律和服务条款。
