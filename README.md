# 3D 个人作品集网站
一个基于 HTML/CSS/JavaScript 开发的 3D 交互式个人作品集网站，支持简历下载、GitHub 跳转等功能，部署在 Vercel 平台，可全网公开访问。

## 🌟 网站预览
- 在线访问：[[https://3-d-personal-portfolio-website.vercel.app](https://3-d-personal-portfolio-website.vercel.app)](https://3-d-personal-portfolio-website.vercel.app/)
- 预览截图：
  <img width="1832" height="912" alt="image" src="https://github.com/user-attachments/assets/05184088-adad-4b67-bbae-019afae28979" />
  <img width="648" height="392" alt="image" src="https://github.com/user-attachments/assets/c66586da-0c5b-4490-b057-c371385c855b" />



## 📋 核心功能
| 功能 | 说明 |
|------|------|
| 3D 交互式布局 | 基于 CSS 3D 变换实现的立体盒子布局，支持鼠标/点击切换不同板块（首页/关于/简历/作品/联系） |
| 简历下载 | 点击按钮直接下载 PDF 格式简历，纯前端实现无需后端 |
| GitHub 跳转 | 一键跳转到个人 GitHub 主页，新窗口打开不跳离网站 |
| 响应式适配 | 适配电脑、手机等不同设备尺寸，保证核心功能正常展示 |

## 🛠 技术栈
- **前端基础**：HTML5 + CSS3 + JavaScript（原生，无框架）
- **核心特性**：CSS 3D Transform、CSS 动画、原生 JS 事件处理
- **部署平台**：Vercel + GitHub（自动部署，无需手动配置服务器）


## 📁 项目结构
```
3-d-personal-portfolio-website/
├── index.html          # 主页面（核心结构 + 功能逻辑）
├── style.css           # 样式文件（3D 布局 + 响应式 + 按钮/表单样式）
├── script.js           # 交互逻辑（3D 切换 + 表单提交 + 下载/跳转处理）
├── resume.pdf          # 简历 PDF 文件
├── img/                # 图片资源（头像、作品展示等）
    ├── me.png
    ├── work1.png
    └── work2.png



## 🎨 样式
- 主色调：默认使用 `#0ef`（青蓝色）作为高亮色，可在 `style.css` 中全局替换为个人偏好的颜色；
- 3D 动画：调整 `style.css` 中 `.box` 类的 `transition` 时长、`rotateY` 角度，修改 3D 切换的动画效果；
- 响应式：在 `style.css` 的 `@media` 媒体查询中，调整不同屏幕尺寸下的布局、字体大小等。

## 📞 联系我
- Email：1556624230@qq.comqq.com
- GitHub：[[https://github.com/你的GitHub用户名](https://github.com/你的GitHub用户名)](https://github.com/seven0409)

---

### 总结
1. 这份 README 覆盖了网站的**核心功能、技术栈、部署方式、自定义配置**等关键信息，符合开源仓库的规范；
2. 所有需要自定义的部分都标注了明确的替换提示，你只需替换括号内的内容即可直接使用；
3. 包含「常见问题」板块，方便后续排查部署或使用中的问题，也便于其他开发者（如有）理解项目。

你可以将这份 README 文件命名为 `README.md`，上传到 GitHub 仓库的根目录，既完善了仓库信息，也能让访问者快速了解你的网站功能和使用方式。
