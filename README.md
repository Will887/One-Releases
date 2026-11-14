# One-Releases

One App 安装包发布仓库（只放安装包，不含源码与更新日志）。

## 下载最新版

打开发布页：<https://github.com/Will887/One-Releases/releases/latest>

| 文件 | 大小 | 适用 |
|---|---|---|
| `One_<版本>_arm64.apk` | 约 18.5 MB | 绝大多数手机（64 位）；应用内「检查更新」读取这个 |
| `One_<版本>_universal.apk` | 约 18.7 MB | 全量包（32 + 64 位），老机型或不确定架构时用 |

安装后打开「我的会员」→「立即开通」→ 选套餐 → 扫码付款 → 在弹窗里粘贴微信账单里的**真实交易单号** → 等待管理员审核，通过后自动开通。

## 版本规则

- 标签：`vX.Y.Z`
- 标题：`One vX.Y.Z`
- 资产：`One_X.Y.Z_arm64.apk`、`One_X.Y.Z_universal.apk`
- **只发大包**（关闭 R8，功能完整，约 18.5 MB）；不再发布 7 MB 压缩小包