# cyfxlj.github.io

Yifan Chen 的个人主页：https://cyfxlj.github.io

基于 [luost26/academic-homepage](https://github.com/luost26/academic-homepage) 模板（MIT License）。

## 改哪里

| 内容 | 文件 |
| --- | --- |
| 名字、职位、简介、邮箱、教育/经历/奖项 | `_data/profile.yml` |
| 照片 | 覆盖 `assets/images/photos/portrait.jpg` |
| 学校/机构 logo | 放进 `assets/images/badges/`，再在 `_data/profile.yml` 里引用 |
| 新闻 | `_news/`，一条新闻一个 `.md` 文件 |
| 论文 | `_publications/<年份>/`，一篇论文一个 `.md` 文件 |
| 论文作者加粗、链接 | `_data/authors.yml` |
| 导航栏 | `_data/navigation.yml` |
| 首页显示哪些模块 | `_data/display.yml` |

## 本地预览

需要 Homebrew 的 Ruby 3.3（`brew install ruby@3.3`）。第一次先装依赖：

```bash
PATH=/opt/homebrew/opt/ruby@3.3/bin:$PATH bundle install
```

然后启动预览，打开 http://localhost:4000 ：

```bash
PATH=/opt/homebrew/opt/ruby@3.3/bin:$PATH bundle exec jekyll serve
```

## 发布

推送到 GitHub 仓库 `cyfxlj.github.io` 的 `main` 分支，1～2 分钟后网站自动更新。
