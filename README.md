# 吕松霖个人主页

本仓库用于托管吕松霖（Song-Lin Lv）的个人学术主页，基于 Jekyll 与 AcadHomepage 修改。


## 访问链接

仓库名为 `solex-lv.github.io` 后，主页访问地址为：

```text
https://solex-lv.github.io/
```

## 本地预览

```bash
bash run_server.sh
```

然后打开 `http://127.0.0.1:4000`。

## 主要文件

- `_config.yml`: 站点元信息与侧边栏个人信息.
- `_data/navigation.yml`: 顶部导航.
- `_pages/about.md`: 主页内容.
- `assets/css/main.scss`: 主题与页面样式.
- `images/profile-placeholder.svg`: 临时头像占位图；后续可替换为个人照片，必要时同步更新 `_config.yml` 中的 `author.avatar`.
