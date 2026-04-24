# 雨三文的科技周刊

> 每周一期，记录 AI、生活、科技与工具的观察与思考。

🔗 **在线阅读**：[https://yusanwen-code.github.io/](https://yusanwen-code.github.io/)

## 内容方向

- **AI 前沿**：AI 工具、模型更新、应用案例
- **生活观察**：科技对生活的思考、个人体验
- **科技动态**：行业新闻、产品发布
- **工具推荐**：好用的软件、网站、服务
- **推荐阅读**：文章、视频、书籍推荐

## 技术栈

- [Hugo](https://gohugo.io/) — 静态站点生成器
- [PaperMod](https://github.com/adityatelange/hugo-PaperMod) — 主题
- [GitHub Pages](https://pages.github.com/) — 托管与部署

## 本地开发

```bash
# 预览
hugo server -D

# 构建
hugo --minify
```

## 发布流程

1. 在 `content/issues/` 下创建新的周刊文章
2. 本地预览确认
3. `git commit` 并 `git push`
4. GitHub Actions 自动构建并部署

## License

内容采用 [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) 许可协议。
