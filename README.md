# 云服务项目展示网页 Demo

这是一个简单的静态网页 Demo，用于展示云服务、云运维、自动化脚本和项目案例。

## 文件说明

- `index.html`：网页主体内容
- `styles.css`：网页样式

## 本地预览

直接双击 `index.html`，或者在浏览器里打开它即可。

如果你安装了 Python，也可以在当前目录启动一个本地服务：

```bash
python3 -m http.server 8080
```

然后访问：

```text
http://localhost:8080
```

## 发布到 GitHub Pages

1. 新建一个 GitHub 仓库。
2. 上传 `index.html`、`styles.css` 和 `README.md`。
3. 进入仓库的 `Settings`。
4. 打开 `Pages`。
5. Source 选择 `Deploy from a branch`。
6. Branch 选择 `main`，目录选择 `/root`。
7. 保存后等待 GitHub 生成访问地址。

## 可修改内容

- 把 `CloudOps Demo` 改成你的项目名称
- 把服务卡片改成你的真实服务内容
- 把 `demo@example.com` 改成你的邮箱
- 把案例列表改成你的实际项目经验
