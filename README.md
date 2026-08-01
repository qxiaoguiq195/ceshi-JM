# JMComic3 v2.0.30 Mod

去广告修改版（基于干净 v2.0.30 原版 + 唯一修改 `memberInfo:{ad_free:!0}`）

## 修改内容

- `assets/public/static/js/main.2d30d0cc.js`：`memberInfo:{}` → `memberInfo:{ad_free:!0}`（免广告标志）

## 打包

推送到 GitHub 后自动通过 Actions 打包，从 Artifacts 下载 APK。

- Debug: `debug.keystore`（密码 `android`）
- Release: `release.keystore`（密码 `123456`）
