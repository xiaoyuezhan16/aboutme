# 薛彦泽 - 个人作品集网站部署指南

## 📁 文件夹内容

```
portfolio-website/
├── index.html          # 网站主文件
├── 薛彦泽.png         # 个人头像
└── 小红书账号.png    # 小红书二维码
```

## 🚀 在线部署方案(推荐)

### 方案一:GitHub Pages(免费,推荐)

**优点**: 完全免费、稳定、专业、支持自定义域名

**步骤**:

1. **注册GitHub账号**(如果还没有)
   - 访问: https://github.com
   - 点击 "Sign up" 注册

2. **创建新仓库**
   - 登录后点击右上角 "+" → "New repository"
   - 仓库名称填写: `portfolio-xue-yanze` (或你喜欢的名字)
   - 选择 "Public" 公开仓库
   - 点击 "Create repository"

3. **上传文件**
   - 在仓库页面点击 "uploading an existing file"
   - 将 `portfolio-website` 文件夹中的所有文件拖入
   - 在 "Commit changes" 处填写提交信息,如 "Initial commit"
   - 点击 "Commit changes" 绿色按钮

4. **启用GitHub Pages**
   - 进入仓库 → 点击 "Settings" (设置)
   - 左侧菜单找到 "Pages"
   - 在 "Build and deployment" 下:
     - Source 选择: "Deploy from a branch"
     - Branch 选择: `main` (或 `master`) 和 `/ (root)`
   - 点击 "Save"

5. **获取网站链接**
   - 等待1-2分钟,刷新页面
   - 顶部会显示: "Your site is live at https://你的用户名.github.io/portfolio-xue-yanze/"
   - 这个链接就可以发给HR了!

---

### 方案二:Netlify(最简单)

**优点**: 超级简单、拖拽即用、自动HTTPS

**步骤**:

1. 访问: https://www.netlify.com/

2. 注册账号(可以用GitHub账号直接登录)

3. 将 `portfolio-website` 文件夹**直接拖拽**到Netlify网站上

4. 等待几秒钟,就会生成一个链接,如: `https://random-name.netlify.app`

5. 可以点击 "Change site name" 修改为更易记的名字

---

### 方案三:Vercel(类似Netlify)

**步骤**:

1. 访问: https://vercel.com/

2. 注册并登录

3. 点击 "New Project"

4. 上传 `portfolio-website` 文件夹或导入GitHub仓库

5. 自动生成链接: `https://your-project.vercel.app`

---

## 📱 如何分享给HR

### 方式一:直接发送链接
```
您好,这是我的个人作品集网站:
https://你的用户名.github.io/portfolio-xue-yanze/

里面包含了我的简历、工作经历、技能以及50+篇AI领域稿件作品。
```

### 方式二:生成二维码
1. 将你的网站链接复制到在线二维码生成器:
   - 草料二维码: https://cli.im/
   - 联图二维码: https://www.liantu.com/

2. 下载二维码图片,可以放在简历或名片上

### 方式三:添加到邮件签名
```
薛彦泽 | 内容主管
📧 xueyanze_hello@163.com | 📱 136-9339-5232
🌐 个人作品集: https://你的用户名.github.io/portfolio-xue-yanze/
```

---

## ✅ 部署后检查清单

- [ ] 在手机和电脑上都打开链接测试
- [ ] 检查头像和二维码是否正常显示
- [ ] 点击所有导航按钮确认功能正常
- [ ] 测试几个文章链接是否能正常跳转
- [ ] 在不同浏览器(Chrome/Safari/Firefox)中测试

---

## 🎯 推荐方案

**最推荐**: GitHub Pages
- ✅ 完全免费
- ✅ 链接最专业
- ✅ 不会被封禁
- ✅ 支持自定义域名(将来如果想用)

**最快**: Netlify
- ✅ 拖拽即用
- ✅ 无需学习Git
- ✅ 2分钟搞定

---

## 💡 提示

1. **选择GitHub Pages的话**,记得将仓库设置为Public(公开),这样HR才能访问
2. **链接示例**: `https://xueyanze.github.io/portfolio/`
3. **可以同时使用多个平台**作为备份
4. 建议将链接保存在手机备忘录,随时可以分享

---

## 🆘 需要帮助?

如果遇到问题,检查:
1. 文件是否都上传成功?
2. GitHub仓库是否设置为Public?
3. 文件名是否正确(特别是中文名的图片)?

需要技术支持可以联系!
