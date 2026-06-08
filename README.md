基于Streamlit+DeepSeek实现AI智能伴侣聊天功能，包含会话管理、流式输出、性格自定义等核心模块。

🎯 核心功能

实时流式对话：基于 DeepSeek 大模型，支持逐字输出的聊天体验，模拟真实对话节奏

会话管理系统：可创建、切换、删除多个对话会话，自动记录每一次对话的时间戳

数据持久化：使用 JSON 文件存储会话数据，应用重启后历史记录不丢失

安全配置管理：通过环境变量隔离敏感信息（如 API 密钥），避免代码泄露风险

极简交互界面：基于 Streamlit 快速搭建，无需复杂前端知识，操作直观易用

✅ 技术栈
streamlit	快速构建 Web 交互界面，实现聊天窗口、侧边栏控制等前端功能
openai	对接 DeepSeek API（兼容 OpenAI 接口规范），处理大模型对话请求与流式响应
os	读取系统环境变量，配合 python-dotenv 安全管理 API 密钥等敏感配置
datetime	生成会话时间戳，记录对话创建与更新时间
json	实现会话数据的本地序列化与持久化存储

✅ 运行方式
1. 配置环境变量DEEPSEEK_API_KEY
2. 安装依赖：pip install streamlit openai python-dotenv
3. 启动：streamlit run 04.ai_parther_2.py
