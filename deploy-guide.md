# 🚀 GitHub Pages 部署指南

## 📋 部署步骤

### 1. 创建GitHub账号
如果还没有GitHub账号，请先到 [github.com](https://github.com) 注册

### 2. 创建新仓库
1. 登录GitHub后，点击右上角的 "+" 号
2. 选择 "New repository"
3. 仓库名称建议：`growth-dashboard` 或 `personal-growth-tracker`
4. 设置为 **Public**（公开仓库才能使用免费的GitHub Pages）
5. 勾选 "Add a README file"
6. 点击 "Create repository"

### 3. 上传文件
有两种方式上传文件：

#### 方式A：网页上传（推荐新手）
1. 在仓库页面点击 "uploading an existing file"
2. 将以下文件拖拽到上传区域：
   - `成长仪表板生成器.html` → `dashboard.html`（主应用文件）
   - `index.html`
   - `README.md`
3. 在底部填写提交信息：`Add growth dashboard files`
4. 点击 "Commit changes"

#### 方式B：Git命令行
```bash
# 克隆仓库到本地
git clone https://github.com/你的用户名/growth-dashboard.git

# 进入仓库目录
cd growth-dashboard

# 复制文件到仓库目录
# 将 成长仪表板生成器.html, index.html, README.md 复制到这里

# 添加文件到Git
git add .

# 提交更改
git commit -m "Add growth dashboard files"

# 推送到GitHub
git push origin main
```

### 4. 启用GitHub Pages
1. 在仓库页面点击 "Settings" 标签
2. 在左侧菜单找到 "Pages"
3. 在 "Source" 部分选择 "Deploy from a branch"
4. 选择 "main" 分支
5. 文件夹选择 "/ (root)"
6. 点击 "Save"

### 5. 获取访问链接
- 几分钟后，你的网站将在以下地址可用：
- `https://你的用户名.github.io/仓库名称`
- 例如：`https://zhangsan.github.io/growth-dashboard`

## 📱 二维码生成

网站部署成功后，你可以：

1. **自动生成**：访问 `index.html` 页面会自动显示二维码
2. **手动生成**：使用在线二维码生成器
   - 推荐：[qr-code-generator.com](https://www.qr-code-generator.com/)
   - 输入你的GitHub Pages链接
   - 下载二维码图片

## 🔧 自定义域名（可选）

如果你有自己的域名：

1. 在仓库根目录创建 `CNAME` 文件
2. 文件内容写入你的域名，如：`growth.yourdomain.com`
3. 在域名DNS设置中添加CNAME记录指向 `你的用户名.github.io`

## 📊 使用统计

GitHub Pages提供基本的访问统计：
- 在仓库页面点击 "Insights" → "Traffic"
- 可以看到访问量和访客数据

## 🔄 更新网站

当你需要更新工具时：
1. 修改本地的HTML文件
2. 重新上传到GitHub仓库
3. GitHub Pages会自动更新（通常需要几分钟）

## 🎯 推广建议

### 社交媒体分享
```
🌟 我创建了一个个人成长追踪工具！
📊 五大模块全覆盖：计划、运动、学习、阅读、情绪
📱 手机电脑都能用，数据可视化超直观
🔗 在线体验：https://你的用户名.github.io/growth-dashboard
#个人成长 #自我管理 #数据可视化
```

### 制作宣传图
- 截取工具界面截图
- 添加二维码和网址
- 突出核心功能特点

### 建立用户社群
- 创建微信群交流使用心得
- 收集用户反馈持续改进
- 分享成长数据模板

## ❓ 常见问题

**Q: 为什么网站打不开？**
A: 请检查：
- GitHub Pages是否已启用
- 文件是否正确上传
- 等待几分钟让部署完成

**Q: 可以使用私有仓库吗？**
A: GitHub Pages对私有仓库需要付费订阅

**Q: 如何统计访问量？**
A: 可以集成Google Analytics或使用GitHub自带的统计功能

**Q: 网站加载慢怎么办？**
A: GitHub Pages在国内访问可能较慢，可以考虑使用CDN加速

---

🎉 **恭喜！你的个人成长工具现在可以在全世界访问了！**