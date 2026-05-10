# 境心客户陪伴系统

这是可直接部署到 GitHub Pages 的静态网页版本。

## 文件说明

- `index.html`：客户经理使用的主系统，可新增、编辑、导入导出本地数据。
- `share.html`：推荐人手机打开的只读共享页。
- `.nojekyll`：告诉 GitHub Pages 不要用 Jekyll 处理文件，避免静态页面异常。

## GitHub Pages 设置

把本目录内全部文件上传到 GitHub 仓库根目录，然后进入：

`Settings` → `Pages`

设置为：

- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/ (root)`

保存后等待 1-3 分钟。

## 部署后的地址

假设仓库名是 `jingxin-client-companion`，你的 GitHub 用户名是 `yourname`：

主系统：

```text
https://yourname.github.io/jingxin-client-companion/index.html
```

推荐人共享页：

```text
https://yourname.github.io/jingxin-client-companion/share.html
```

## 生成推荐人手机链接

1. 打开部署后的 `index.html`
2. 点击「线上地址」
3. 填入部署后的 `share.html` 地址
4. 点击「共享查看」
5. 复制“推荐人手机可打开链接”
6. 发给推荐人

## 数据提醒

- 主系统数据保存在当前浏览器本地。
- 推荐人看到的是你生成链接那一刻的数据快照。
- 客户或活动更新后，需要重新点击「共享查看」生成新链接。
- 推荐人共享页是只读页面，不能修改你的本地数据。
