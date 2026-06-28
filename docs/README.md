# 汤液经法拟补（修订版）

> 张大昌 撰 · 姜宗瑞 辑  
> 2026年6月28日 修订

---

## 目录

- [前言（姜宗瑞）](./前言.md)
- [自传](./自传.md)
- [自序](./自序.md)
- [第一节 十二神方](./第一节-十二神方.md)
- [第二节 神方释义](./第二节-神方释义.md)
- [第三节 十方君臣佐使格式](./第三节-十方君臣佐使格式.md)
- [附录：十二神方与现传世古医书对照表](./附录-十二神方对照表.md)
- [附篇：张大昌先生侧记](./附篇-张大昌先生侧记.md)

---

## 资源下载

- [📄 下载 PDF 原档](./汤液经法拟补.修订版.20260628.pdf)
- [📁 下载所有 Markdown 源文件](https://github.com/gavin887/tangye-jingfa/archive/refs/heads/main.zip(将 USERNAME 替换为你的 GitHub 用户名)

---

## 部署到 GitHub Pages

本仓库已配置 **两套方案**，任选其一即可，均无需修改 Markdown 源文件：

### 方案一：Docsify（推荐 · 零构建 · 最简）

Docsify 直接在浏览器端渲染 Markdown，无需构建步骤。

**启用步骤：**

1. 将此仓库推送到 GitHub
2. 进入仓库 **Settings → Pages**
3. 在 **Source** 中选择 **Deploy from a branch**
4. Branch 选择 `main`，文件夹选择 `/docs`
5. 点击 **Save**

> 等待几分钟,访问 `https://gavin887.github.io/tangye-jingfa/` 即可。

已含文件：
- `docs/index.html` —— Docsify 入口
- `docs/_sidebar.md` —— 左侧导航栏
- `docs/_coverpage.md` —— 封面页
- `docs/.nojekyll` —— 防止 GitHub Pages 忽略 `_` 开头的文件

**功能特性：**
- ✅ 全文搜索（支持中文分词）
- ✅ 代码块一键复制
- ✅ 图片点击缩放
- ✅ 响应式布局（手机/平板/桌面）
- ✅ PDF 原档下载链接
- ✅ 零构建、零依赖

---

### 方案二：MkDocs Material（进阶 · 更丰富的主题）

> 需要启用 `.github/workflows/deploy.yml` 中的 GitHub Actions。

**启用步骤：**

1. 进入仓库 **Settings → Pages**
2. 在 **Source** 中选择 **GitHub Actions**
3. 推送代码到 `main` 分支，GitHub Actions 会自动构建并部署

**功能特性（额外增加）：**
- ✅ 即时导航（页面切换无刷新）
- ✅ 更好的搜索建议与高亮
- ✅ 暗色/亮色主题切换
- ✅ 可导出为 PDF 全文（安装 mkdocs-pdf-export-plugin）
- ✅ 更丰富的主题定制

---

## 本地预览

### Docsify 预览

```bash
# 安装 docsify-cli（需 Node.js）
npm i -g docsify-cli

# 启动本地服务器
docsify serve docs

# 访问 http://localhost:3000
```

### MkDocs 预览

```bash
# 安装依赖
pip install mkdocs mkdocs-material

# 启动本地服务器
mkdocs serve

# 访问 http://localhost:8000
```

---

**说明：** 本文档由 PDF 版《汤液经法拟补·修订版·20260628》整理为 Markdown 格式，按原书行文条理分章节编排，以利阅读与检索。
