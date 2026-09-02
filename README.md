# 叶再俊的个人学术网站

本项目是基于 Hugo Blox 构建的中文个人学术主页。

## 本地开发

```bash
pnpm install --frozen-lockfile
pnpm dev
```

本地预览地址为 <http://localhost:1313>。

## 生产构建

```bash
pnpm build
```

构建产物位于 `public/`，该目录仅供本地预览和 GitHub Pages 部署，不纳入版本控制。

## 主要内容

- `content/_index.md`：首页内容与板块顺序
- `data/authors/me.yaml`：首页展示的个人信息和教育经历
- `content/publications/`：论文元数据与 BibTeX
- `config/_default/`：网站配置
