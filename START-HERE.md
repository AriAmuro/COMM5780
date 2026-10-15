# Aria 的网站：简单修改指南

网站地址：https://ariamuro.github.io/COMM5780/

## 文件对应关系
- index.html：首页的两句英文和你的画
- about.html：头像和个人介绍
- work.html：三个本科项目的英文标题与二维码
- contact.html：邮箱
- portfolio.css：四页共用的字体、颜色和排版
- images/：网站用到的五张图片

## 在电脑上预览
从 GitHub 仓库点击 Code → Download ZIP，解压。用 VS Code 的 File → Open Folder 打开解压后的整个文件夹。在文件管理器中双击 index.html 即可在浏览器中预览。修改并保存文件后，刷新浏览器就能看到本地变化。

## 怎样改文字
在对应 HTML 文件中修改 <h1>、<h2>、<p> 标签之间的文字。请保留标签本身。

## 怎样改图片
把新图片放进 images 文件夹，然后修改 HTML 中 img 的 src 路径。alt 是图片内容的简短说明。

## 怎样改颜色
打开 portfolio.css。body 中 color 是文字颜色，background 是白色到灰蓝色的背景渐变。想换成纯白底，可以把 background 那一行改成 background: #fff;。

## 怎样更新在线网站
本地修改不会自动上传。进入 GitHub 仓库，使用 Add file → Upload files 上传改好的文件，保持原来的文件路径，再点击 Commit changes。也可以在 GitHub 中打开文件，点击铅笔直接编辑，最后 Commit changes。GitHub Pages 会自动发布更新。

## 作品标题对应
江中药业策划案：Jiangzhong Pharmaceutical / Campaign Proposal
《流量下的煎守》：Cooking Through the Hype / Food Documentary（展示用英文译名）
《宿舍规则怪谈》：Dormitory Rules: A Horror Story / AI Short Drama（展示用英文译名）

三个二维码使用上传的原图；首页的画另存为较小的 JPG 供网页加载，完整画面和比例保持不变。参考截图不会放进网站。
