# CLAUDE.md — chedong.github.io

车东个人主页（GitHub Pages），Beautiful Jekyll 主题，remote_theme 直接使用，无需本地构建。见 `_config.yml`、`index.md`、`README.md`。

## 分支约定

- **default branch 是 `main`**：push 一律 `git push origin main`，main 是唯一主干。
- **不要 push 其他分支名**（喂 `git push origin master`）：远程没有该分支时会意外创建一个非主干分支（myblog 的教训：default=main 却 push master，养出了旁支）。若日后决定调整 default 分支，再更新本节。
