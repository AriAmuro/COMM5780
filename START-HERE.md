# Aria 的作品集：使用说明

这是原创、轻量的 HTML/CSS 草稿模板，不需要安装软件包，网站内容为英文。

## 1. 本地打开
下载仓库 ZIP 并解压，在文件夹中双击 index.html。四个菜单链接可以切换页面。也可以在 VS Code 中打开文件夹，用 Live Server 预览。

## 2. 文件与作用
- index.html：首页
- about.html：自我介绍
- work.html：作品与可展开的项目说明
- contact.html：联系页面，目前链接到公开 GitHub 个人主页
- portfolio.css：所有页面的配色、字体、布局、手机适配
- .nojekyll：让 GitHub Pages 直接发布静态文件

## 3. 第一次发布
打开 https://github.com/AriAmuro/COMM5780/settings/pages
在 Build and deployment → Source 中选 Deploy from a branch。
Branch 选 main，文件夹选 /(root)，点击 Save。
发布后通过 Pages 页面的 Visit site 查看。默认地址为 https://ariamuro.github.io/COMM5780/ 。首次发布或更新可能需要约 10 分钟。
当前文件上传不等于 Pages 一定已经启用，以 Settings → Pages 显示的状态为准。

## 4. 以后怎样修改
在 GitHub 打开目标 HTML 文件 → 点击铅笔 Edit → 修改英文文字 → Commit changes。
或者下载全部文件，在 VS Code 修改，随后在 GitHub 的 Add file → Upload files 上传修改后的文件。确保 index.html 在仓库最外层，不要把整套文件多包在一层文件夹里。
配色在 portfolio.css 开头的 :root 中修改：--paper 是底色，--ink 是主文字与按钮，--green 是绿色装饰。

## 5. 增加自己的图片
上传例如 artwork.jpg 到仓库根目录，在 HTML 中加入：
<img src="artwork.jpg" alt="A short description of my artwork" style="max-width:100%;height:auto">
使用你自己的图片，或有明确使用许可的图片。当前所有图案为 CSS 装饰，没有使用他人的作品图片。

## 6. 添加邮箱
contact.html 中找到 “My email contact will be added here soon.”，将其替换为：
<a href="mailto:YOUR_EMAIL">Email me</a>
把 YOUR_EMAIL 换成你愿意公开的邮箱。mailto 会打开访问者的邮件软件，不是网站后台收件系统。

## 7. 参考模板与学习资料
- Story：https://html5up.net/story （单页展示）
- Strata：https://html5up.net/strata （作品集）
- GitHub Pages 官方说明：https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
现成模板请遵守各自授权条款；此草稿是为 Aria 单独编写的简化版本。

## 8. 内容说明
作品区是明确标注的占位区域，尚未展示完成项目。未来先添加 1–3 个真实作品，每个写清 Title / What I made / My role / What I learned，再逐步完善。当前联系页没有发布私人邮箱或电话号码。
