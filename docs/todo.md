# v4.0.0

下一版本的更新计划

## ✨ 新功能

- ✅ 新增自定义系统 Prompt 功能
- ✅ 支持火山引擎 TTS 和音色切换能力
- ✅ 添加 MIT license

## 💪 优化

- ✅ 登录凭证过期后自动刷新 token https://github.com/idootop/mi-gpt/issues/76
- ✅ 优化网络请求错误重试策略（消息/播放状态轮询）
- ✅ 移除 TTS 不发音字符（emoji）
- ✅ 优化 db 路径查找方式

## 📚 文档

- ✅ 添加系统 Prompt 模板字符串变量的说明
  - ✅ DAN 模式，猫娘等整活 prompt 的演示示例
  - ✅ Awesome prompt 征集
- ✅ 添加更新人设 Prompt 的使用说明（你是 xxx，你喜欢 xxx）
- ✅ 添加对其他品牌音箱的支持情况的说明 https://github.com/idootop/mi-gpt/issues/83
- ✅ 添加“小爱同学”唤醒词的相关说明 https://github.com/idootop/mi-gpt/issues/84
- ✅ 添加进入唤醒模式时小爱莫名开始播放歌曲的说明 https://github.com/idootop/mi-gpt/issues/71
- ✅ 添加部署和接入本地大语言模型的教程 https://github.com/idootop/mi-gpt/issues/82
- ✅ 添加获取小爱音箱 did 的相关说明
- ✅ 添加提示无法找到共享设备的相关说明
- ✅ 添加常见小爱音箱型号的支持情况和参数列表
- ✅ 添加 OpenAI 账号充值前可能无法使用 gpt-4 系列模型的相关说明
- ✅ 添加无需和小爱音箱在同一局域网下运行的说明
- ✅ 添加自定义 TTS 和音色的配置和使用教程
- 添加更详细的使用和配置视频教程
- 添加 302.AI Sponsor 链接

## ❤️ 感谢

- @LycsHub 推荐了使用 [simple-one-api](https://github.com/fruitbars/simple-one-api) 将其他模型的请求格式统一成 OpenAI 的格式，支持 Coze
- @shinedlc 实现了一个小爱音箱接入 [OpenGlass](https://github.com/BasedHardware/OpenGlass) 摄像头硬件 + 本机搭建 [Ollama](https://github.com/ollama/ollama) 模型的 [Fork](https://github.com/shinedlc/mi-gpt)