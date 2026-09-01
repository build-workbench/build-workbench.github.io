# build-workbench.github.io

Build Workbench 组织门户站点。静态单页,由 GitHub Pages 托管于 <https://build-workbench.github.io>。

## 本地预览

```bash
python3 -m http.server 8000
```

然后访问 <http://localhost:8000>。

## 维护

- 新增/重命名项目后,同步更新 `index.html` 中的卡片。
- 项目介绍与分类以 `.github/profile/README.md` 为准,保持两者一致。