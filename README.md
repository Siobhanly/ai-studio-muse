# AI 工作室

10 个免费工具的自动化中枢：Kaggle（双 T4）、GitHub Actions、Simular Box、
Cloady、Supabase、OpenRouter、Cloudflare Workers、Google Colab、Cloudflare R2、Sakupa。

- 云电脑：Simular Box（桌面杂活）+ instabox-rss（常驻轮询）
- GPU：Colab T4 / Kaggle 双 T4
- 模型接口：OpenRouter，默认免费模型 nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free
- 数据与存储：Supabase + R2，Workers 做轻量网关
- 自动化：本仓 GitHub Actions（公开仓，标准 runner 分钟不限）

## 状态

- [x] Simular Box / instabox-rss 已唤醒
- [x] OpenRouter 已接通并测通
- [x] GitHub Actions 冒烟测试（.github/workflows/smoke-test.yml）
