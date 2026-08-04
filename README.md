💌 Date Invitation

一个浪漫、轻量、支持手机端操作的多步骤约会邀请网页。

访问者点击“当然愿意”后，可以依次选择约会日期、约会时间和想吃的食物，最后生成一份完整的约会计划。


🌐 在线预览

https://157543.github.io/date-invitation/


✨ 网页功能

💗 点击“当然愿意”进入约会安排流程

😝 “不要”按钮会自动躲避鼠标或手指

📅 可以选择具体约会日期

⚡ 可以快速选择明天、三天后或下周

🕰️ 可以选择预设时间

⌚ 支持自定义具体时间

🍲 可以选择火锅、烤肉、日料、西餐等食物

🎉 完成后自动生成约会计划

📋 可以一键复制约会计划

💕 页面带有爱心和彩带动画

📱 支持手机、平板和电脑

🚀 使用 GitHub Pages 免费部署

📦 不需要服务器或数据库


📁 项目文件

date-invitation/
├── index.html
├── FullSizeRender.jpeg
└── README.md


文件说明

index.html

网页的完整 HTML、CSS 和 JavaScript 代码。


FullSizeRender.jpeg

网页首页显示的照片。


README.md

项目介绍和使用说明。


💗 使用流程

访问者打开网页后，会依次完成以下步骤：

第一步：回答是否愿意约会

第二步：选择约会日期

第三步：选择约会时间

第四步：选择想吃的食物

第五步：查看完整约会计划

第六步：复制约会计划并发送给对方


📅 日期如何计算

网页中的以下快捷日期不是固定日期：

明天

三天后

下周


这些日期会根据访问者打开网页时，手机或电脑上的本地日期自动计算。

例如：

今天是 2026 年 8 月 4 日

明天是 2026 年 8 月 5 日

三天后是 2026 年 8 月 7 日

下周是 2026 年 8 月 11 日


第二天重新打开网页时，这些日期也会随之变化。

访问者也可以通过日期选择器，自己选择其他日期。


时区说明

日期以访问者设备上的本地时间为准。

如果两个人位于不同国家或时区，“今天”和“明天”可能对应不同的日期。

例如，一个人在中国，另一个人在德国，两个人打开网页时看到的当前日期可能不同。


🕰️ 时间如何计算

网页中的预设时间目前是固定的：

午餐：11:30

下午：14:30

晚餐：18:30

晚上：20:00


这些时间不会随着当前时间自动改变。

访问者也可以使用“自定义时间”功能，选择任意具体时间。

最终生成的约会计划会显示访问者实际选择的时间。


🍽️ 食物选项

网页目前提供以下选项：

火锅

烤肉

日料

西餐

甜品和咖啡

你来决定


选择后，食物类型会出现在最终的约会计划中。


📋 最终约会计划

完成所有选择后，网页会生成类似下面的内容：

💌 我们的约会计划

📅 日期：2026年8月5日星期三

🕰️ 时间：18:30

🍽️ 吃什么：火锅

说好了，不许反悔 💗


点击“复制约会计划”后，可以将内容复制到剪贴板，然后通过微信、WhatsApp、Instagram、短信或其他聊天软件发送给对方。


🖼️ 更换照片

网页当前使用的照片文件是：

FullSizeRender.jpeg


对应的网页代码是：

<img class="photo" src="FullSizeRender.jpeg" alt="我们的照片">


更换照片的方法：

第一步：将新照片上传到 GitHub 仓库。

第二步：确认照片和 index.html 位于同一个目录。

第三步：打开 index.html。

第四步：点击铅笔图标编辑代码。

第五步：找到图片代码。

第六步：将 src 后面的文件名修改成新照片的文件名。

第七步：点击 Commit changes 提交修改。


例如，新照片名称为：

our-photo.jpg


图片代码应该修改为：

<img class="photo" src="our-photo.jpg" alt="我们的照片">


照片文件名、大小写和后缀必须完全一致。

例如：

photo.jpg

Photo.jpg

photo.jpeg

photo.png


这些会被网页视为不同的文件。


✏️ 修改邀请标题

在 index.html 中找到：

<h1>愿意和我约会吗？</h1>


可以修改为：

<h1>周末愿意和我一起出去玩吗？</h1>


也可以修改为：

<h1>愿意和我一起吃晚餐吗？</h1>


或者：

<h1>这周愿意和我见面吗？</h1>


✏️ 修改邀请说明

在 index.html 中找到：

<p class="subtitle">
  我认真想了很久，还是觉得应该亲口问你。<br>
  所以……你的答案是？
</p>


可以替换成自己的内容，例如：

<p class="subtitle">
  有一件事情，我想认真地问你。<br>
  这周愿意和我一起出去玩吗？
</p>


修改时不要删除开头的 p 标签和结尾的 p 标签。


🕰️ 修改预设时间

在 index.html 中搜索以下内容：

data-value="11:30"

data-value="14:30"

data-value="18:30"

data-value="20:00"


例如，将晚餐时间从 18:30 修改成 19:00，可以将对应部分修改为：

<button class="option" type="button" data-value="19:00">
  <span>🌆</span>
  <span>晚餐 · 19:00</span>
</button>


data-value 是最终约会计划中保存和显示的时间。

按钮中显示的文字是访问者在网页上看到的内容。

修改时间时，建议将这两个位置同时修改。


🍕 修改食物选项

例如，将“火锅”修改为“披萨”，可以将代码修改为：

<button class="option" type="button" data-value="披萨">
  <span>🍕</span>
  <span>披萨</span>
</button>


其中：

data-value 是最终约会计划中显示的内容。

第一个 span 是食物图标。

第二个 span 是按钮上的文字。


例如，将“西餐”修改为“中餐”：

<button class="option" type="button" data-value="中餐">
  <span>🥢</span>
  <span>中餐</span>
</button>


例如，将“甜品和咖啡”修改为“奶茶”：

<button class="option" type="button" data-value="奶茶">
  <span>🧋</span>
  <span>奶茶</span>
</button>


🛠️ 本地运行

下载项目后，可以直接使用浏览器打开：

index.html


推荐使用以下浏览器：

Safari

Google Chrome

Microsoft Edge

Firefox


某些聊天软件、文件预览器或应用内浏览器可能不会运行 JavaScript。

如果网页能够显示，但是按钮不能点击，请使用 Safari、Chrome、Edge 或 Firefox 打开。


🚀 GitHub Pages 部署

第一步：打开 GitHub 仓库。

第二步：点击 Settings。

第三步：进入 Pages。

第四步：找到 Build and deployment。

第五步：将 Source 设置为：

Deploy from a branch


第六步：将 Branch 设置为：

main


第七步：将文件夹设置为：

/(root)


第八步：点击 Save。

第九步：等待 GitHub 自动完成部署。


网站地址通常为：

https://你的GitHub用户名.github.io/仓库名称/


本项目的网站地址为：

https://157543.github.io/date-invitation/


🔄 更新网页

每次修改 index.html 后，都需要点击：

Commit changes


GitHub Pages 会自动重新部署网页。

通常需要等待几十秒到几分钟。

如果网站仍然显示旧版本，可以在网站地址后添加版本参数。


例如：

https://157543.github.io/date-invitation/?v=2


之后可以继续更改数字：

https://157543.github.io/date-invitation/?v=3

https://157543.github.io/date-invitation/?v=4

https://157543.github.io/date-invitation/?v=5


版本参数不会改变网页内容，只是帮助浏览器重新读取最新页面，减少缓存造成的问题。


💾 数据保存说明

当前网页没有连接服务器或数据库。

访问者选择的日期、时间和食物，只会暂时保存在当前打开的网页中。

关闭或刷新网页后，选择结果可能会被清除。


当前网页不会自动：

将结果发送到邮箱

将结果发送给网页作者

将结果保存到 GitHub

将结果保存到数据库

记录访问者身份

记录访问者的选择

通知网页作者有人打开网页


访问者需要点击“复制约会计划”，然后手动将结果发送给对方。


📱 手机使用说明

网页支持 iPhone、iPad 和 Android 手机。

建议使用 Safari 或 Chrome 打开 GitHub Pages 网站。

如果网页从 Instagram、微信或其他应用内打开后不能正常操作，可以点击浏览器菜单，然后选择：

在 Safari 中打开

或者：

在默认浏览器中打开


🔒 隐私提醒

当前 GitHub 仓库是公开仓库。

任何人都有可能查看仓库中的：

网页代码

图片

文件名称

提交历史

README 内容


请不要上传：

身份证件

家庭住址

手机号码

账号密码

银行卡信息

私密聊天截图

包含敏感信息的照片

其他不希望公开的内容


如果网页中使用了真人照片，请确认照片适合公开展示。


💻 使用技术

本项目使用以下技术：

HTML

CSS

JavaScript

GitHub Pages


本项目没有使用第三方前端框架。

不需要安装服务器。

不需要购买域名。

不需要配置数据库。


💖 适用场景

这个网页可以用于：

约会邀请

表白页面

纪念日惊喜

情人节邀请

生日活动邀请

聚餐选择

旅行计划选择

个性化互动网页


📄 使用许可

This project is for personal and educational use.

本项目主要用于个人展示、学习和非商业用途。