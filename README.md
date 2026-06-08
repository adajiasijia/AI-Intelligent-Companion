基于Streamlit+DeepSeek实现AI智能伴侣聊天功能，包含会话管理、流式输出、性格自定义等核心模块。

✅ 核心功能
- 实时流式聊天，模拟真实微信对话体验
- 可自定义AI伴侣的昵称和性格设定
- 完整的会话历史管理：新建、加载、删除会话
- 会话数据本地JSON持久化存储，重启不丢失
- 侧边栏控制面板，操作直观便捷

✅ 技术栈
- 前端/后端：Streamlit 1.30+
- 大模型：DeepSeek V4 Pro
- 依赖库：openai, python-dotenv

✅ 运行方式
1. 配置环境变量DEEPSEEK_API_KEY
2. 安装依赖：pip install streamlit openai python-dotenv
3. 启动：streamlit run 04.ai_parther_2.py
