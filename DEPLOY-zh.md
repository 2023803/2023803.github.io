# bulbzhong 主页部署说明

本目录基于 [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io)，并严格按照其中文文档完成个人化配置。

## 已修改内容

- `_config.yml`：标题、描述、仓库地址和作者信息
- `_pages/about.md`：双语个人介绍、研究兴趣、项目、荣誉、教育和足迹
- `_data/navigation.yml`：与主页板块匹配的双语导航
- `images/avatar.jpg`：个人头像
- `images/project-graph-transformer.svg`：项目配图
- `images/favicon-*` 等：由头像生成的网页图标

由于未提供 Google Scholar ID，自动引用爬虫暂时关闭；获得 ID 后可按照 `docs/README-zh.md` 恢复配置。

## 覆盖现有仓库

部署前请删除旧仓库中的 `index.html`、`index.md` 和旧主题文件，然后将本目录全部内容复制到仓库根目录，提交并推送到 `main`。

GitHub Pages 发布源应设置为 `main` 分支的 `/ (root)`。
