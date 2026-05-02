# 禁漫天堂自动签到

基于 [Breeze-plugin-JmComic](https://github.com/deretame/Breeze-plugin-JmComic) 开发的 GitHub Actions 自动签到工具。

## 相关链接

- Breeze 漫画阅读器: https://github.com/deretame/Breeze
- 插件源码: https://github.com/deretame/Breeze-plugin-JmComic

## 功能

| 功能 | 说明 |
|------|------|
| 每日自动签到 | 通过 GitHub Actions 自动完成每日签到 |

## 自动签到配置

1. Fork 本仓库
2. 进入仓库 **Settings** → **Secrets and variables** → **Actions**
3. 添加以下 Secrets：
   - `JM_ACCOUNT`：禁漫天堂账号
   - `JM_PASSWORD`：禁漫天堂密码
4. 签到任务将在每天北京时间 **07:00** 自动执行
5. 也可以手动触发：进入 Actions 页面 → 选择 **禁漫天堂每日自动签到** → 点击 **Run workflow**
