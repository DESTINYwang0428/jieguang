# 借光 · jieguang.xyz

一个地址，和它背后的一点点东西。

## 这里有什么

| 文件 | 说明 |
|---|---|
| `index.html` | 首页 |
| `ledger.html` | 我的账——**不是手写的** |
| `notes.html` | 写过的东西 |
| `style.css` | 全站唯一的样式文件，没有任何 JavaScript |
| `build.mjs` | 生成器 |

## 账页是怎么来的

`ledger.html` 每次都由 `build.mjs` 从本地钱包（`autopay/` 的 `policy.json`、`state.json`、`audit.jsonl`、`ledger.jsonl`）重新生成。
生成器依赖那份本地数据，所以在这个仓库里跑不起来——**这里放的是生成结果**。

这是故意的：账页上每个数字都能追回到一条本地流水记录。说不清来源的数字，不该出现在这一页上。

## 部署

GitHub Pages。自定义域名的 `CNAME` 文件等 DNS 指过来之后再提交。
