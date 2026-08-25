# GameWander

GameWander 的 GitHub Pages 官网：介绍旗下小游戏，并提供各 App 的技术支持与隐私政策页面。

线上地址：<https://gongzhxu.github.io/gamewander/>

## 目录结构

```
index.html                  # 首页：介绍所有游戏
teascore/
  index.html                # TeaScore 介绍页（营销网址）
  support/index.html        # TeaScore 技术支持
  privacy/index.html        # TeaScore 隐私政策
justdecide/
  index.html                # 我来定（JustDecide）介绍页（营销网址）
  support/index.html        # 我来定 技术支持
  privacy/index.html        # 我来定 隐私政策
assets/style.css            # 共享样式
```

## 启用 GitHub Pages

1. 在 GitHub 仓库 `gongzhxu/gamewander` → **Settings → Pages**。
2. **Source** 选择 `Deploy from a branch`，分支选 `main`，目录选 `/ (root)`。
3. 保存后等待部署完成（约 1 分钟）。

## App Store 里填写的网址

| 字段 | 网址 |
| --- | --- |
| 技术支持网址（中文） | `https://gongzhxu.github.io/gamewander/teascore/support/` |
| 技术支持网址（英文） | `https://gongzhxu.github.io/gamewander/teascore/support/?lang=en` |
| 隐私政策网址（中文） | `https://gongzhxu.github.io/gamewander/teascore/privacy/` |
| 隐私政策网址（英文） | `https://gongzhxu.github.io/gamewander/teascore/privacy/?lang=en` |
| 营销网址（可选） | `https://gongzhxu.github.io/gamewander/teascore/` |

**JustDecide（我来定）**：

| 字段 | 网址 |
| --- | --- |
| 技术支持网址（中文） | `https://gongzhxu.github.io/gamewander/justdecide/support/` |
| 技术支持网址（英文） | `https://gongzhxu.github.io/gamewander/justdecide/support/?lang=en` |
| 隐私政策网址（中文） | `https://gongzhxu.github.io/gamewander/justdecide/privacy/` |
| 隐私政策网址（英文） | `https://gongzhxu.github.io/gamewander/justdecide/privacy/?lang=en` |
| 营销网址（可选） | `https://gongzhxu.github.io/gamewander/justdecide/` |

> 页面默认显示简体中文，带 `?lang=en` 时显示英文，与 App Store Connect 的双语字段一一对应。

## 新增一个游戏

1. 新建 `<slug>/`（如 `justdecide/`），复制 `teascore/` 下的 `support/` 和 `privacy/` 结构，替换文案与邮箱。
2. 在首页 `index.html` 的 `.games` 区块加一张 `game-card`。
