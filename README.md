# 💌 Date Invitation

一个浪漫、轻量、支持手机端交互的约会邀请网页。

点击“愿意”后会显示庆祝页面；当用户尝试点击“不要”时，按钮会随机移动。


## 🌐 在线预览

https://157543.github.io/date-invitation/


## ✨ 功能

- 💗 点击“愿意”进入成功页面
- 😝 “不要”按钮会自动躲避鼠标和手指
- 🎉 成功后显示爱心与庆祝动画
- 📱 支持手机、平板和电脑
- 🖼️ 可以替换成自己的照片
- ✏️ 可以自由修改标题、文案和按钮文字
- 🚀 使用 GitHub Pages 免费部署
- 📦 不需要服务器和数据库


## 📁 项目文件

date-invitation/
├── index.html
├── FullSizeRender.jpeg
└── README.md

index.html：网页的全部代码
FullSizeRender.jpeg：网页中展示的照片
README.md：项目介绍和使用说明


## 🛠️ 本地运行

下载项目后，直接使用浏览器打开：

index.html

推荐使用：

- Safari
- Chrome
- Edge
- Firefox

注意：在某些文件预览器中打开时，JavaScript 可能不会执行。建议使用真正的浏览器打开。


## 🖼️ 更换照片

将新照片上传到仓库，然后修改 index.html 中的图片文件名：

<img class="illustration photo" src="FullSizeRender.jpeg" alt="照片">

例如，新照片名称是：

our-photo.jpg

则修改为：

<img class="illustration photo" src="our-photo.jpg" alt="我们的照片">

照片文件名、大小写和后缀必须完全一致。


## ✏️ 修改网页文字

在 index.html 中可以找到并修改以下内容。


### 邀请标题

<h1>愿意和我约会吗？</h1>


### 邀请文案

<p class="subtitle">
  我认真想了很久，还是觉得应该亲口问你。<br>
  所以……你的答案是？
</p>


### 成功页面文字

<h2>你真的答应了！</h2>

<p>
  那就说定啦 💕<br>
  时间和地点，我来认真安排。
</p>


## 🚀 GitHub Pages 部署

1. 打开仓库的 Settings。
2. 进入 Pages。
3. 在 Build and deployment 中选择：

Source: Deploy from a branch
Branch: main
Folder: /(root)

4. 点击 Save。
5. 等待 GitHub 完成部署。

网站地址通常为：

https://你的GitHub用户名.github.io/仓库名称/

本项目地址：

https://157543.github.io/date-invitation/


## 🔄 更新网页

每次修改并提交 index.html 后，GitHub Pages 会自动重新部署。

如果网页仍然显示旧内容，可以在链接末尾添加版本参数：

https://157543.github.io/date-invitation/?v=2

也可以继续修改数字：

?v=3
?v=4
?v=5

这样可以减少浏览器缓存的影响。


## 🔒 隐私提醒

当前仓库是公开仓库，因此仓库中的照片和代码都可能被任何人查看。

请不要上传以下内容：

- 身份证件
- 家庭住址
- 手机号码
- 账号密码
- 其他敏感个人信息


## 💖 项目说明

这个项目使用原生 HTML、CSS 和 JavaScript 编写，没有使用第三方框架，适合用于：

- 约会邀请
- 表白页面
- 纪念日惊喜
- 生日祝福
- 情人节网页
- 个性化互动页面
