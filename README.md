# 生日祝福 H5

这是一个适合手机端和微信内浏览器打开的静态生日祝福页，首页文件是 `index.html`。

## 本地预览

直接双击 `index.html` 即可打开。

## 自定义内容

打开 `index.html`，找到底部脚本中的 `CONFIG`，修改这些字段即可：

- `friendName`：朋友名字
- `headline`：首屏大标题
- `subtitle`：副标题
- `letterTitle`：生日信标题
- `letterLines`：生日信正文
- `signature`：署名
- `wishes`：祝福标签

## 部署到 GitHub Pages

仓库里已经带好了 GitHub Pages 的工作流文件：

- `.github/workflows/deploy-pages.yml`

你只需要：

1. 在 GitHub 新建一个仓库。
2. 把当前目录所有文件上传到仓库根目录。
3. 确保默认分支是 `main`。
4. 进入 GitHub 仓库的 `Settings` -> `Pages`。
5. 在 `Build and deployment` 中选择 `GitHub Actions`。
6. 提交到 `main` 后，等待 Actions 运行完成。
7. 打开生成的网址，通常会是：
   `https://你的用户名.github.io/仓库名/`

## 微信分享说明

- 微信里通常不允许网页自动播放音乐，所以页面里保留了手动播放按钮。
- 想发给朋友时，直接把 GitHub Pages 生成的链接分享到微信即可。
