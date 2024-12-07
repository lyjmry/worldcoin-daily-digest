# Worldcoin Daily Digest

自动获取 Worldcoin 相关信息并生成每日资讯总结

## 功能特点

- 自动收集 Worldcoin 官方 Twitter 最新动态
- 自动获取 Worldcoin 官方博客更新
- 收集生态系统信息
- 使用 AI 生成每日总结
- 自动生成适合微信公众号的文章

## 使用方法

1. 复制 `.env.example` 到 `.env` 并填写必要的 API 密钥
2. 在 GitHub Secrets 中配置必要的环境变量
3. 启用 GitHub Actions

## 配置说明

需要配置以下环境变量：

- `TWITTER_API_KEY`
- `TWITTER_API_SECRET`
- `TWITTER_ACCESS_TOKEN`
- `TWITTER_ACCESS_SECRET`
- `OPENAI_API_KEY`

## 目录结构

```
worldcoin-daily-digest/
├── collectors/          # 数据收集模块
├── processors/          # 数据处理模块
├── summaries/          # 生成的摘要存储
├── .github/workflows/  # GitHub Actions 配置
├── config.py          # 配置文件
└── main.py            # 主程序
```