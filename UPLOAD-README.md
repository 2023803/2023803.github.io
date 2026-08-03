# bulbzhong 主页部署包（少于 100 个文件）

本包严格沿用 acad-homepage 的页面结构与视觉样式，但已将 SCSS 预编译为
`assets/css/main.css`，因此不再需要上传 `_sass` 目录。

## 上传方式

1. 解压 ZIP。
2. 打开仓库主页，选择 `Add file` → `Upload files`。
3. 进入解压后的文件夹，选中里面的全部内容后拖入上传区。不要直接上传 ZIP，
   也不要把最外层文件夹作为一个子目录上传。
4. 提交信息填写 `Deploy bulbzhong academic homepage`，提交到 `main` 分支。
5. 等待 GitHub Actions 中的 Pages 构建完成。

`_config.yml` 已排除旧的 `_sass` 与 `assets/css/main.scss`，即使仓库里仍残留
部分旧文件，也不会再触发缺少 Breakpoint/Susy 的构建错误。
