# agentPlanner
基于 LangGraph 和 LangChain 构建的智能旅行行程规划系统，支持多 Agent 协作、流式响应、预算控制和地图可视化。

ps:为了尽快从0-1的搭建与实现目标功能，本项目借助cursor 使用 vibe coding实现部分功能，目前所有流程均可以跑通，后续还会完善新的功能，另外地图的key次数用完了，地图未能显示。

#核心功能
智能行程规划: 根据目的地、日期、偏好自动生成详细行程
预算控制: 支持设置预算范围，AI 会根据预算合理安排景点、餐饮和住宿
实时进度反馈: SSE 流式响应，实时展示 Agent 执行进度
地图可视化: 高德地图集成，展示景点位置和路线
多轮对话: 支持自然语言交互，逐步完善行程需求
行程持久化: 每次规划结果自动保存为 JSON 文件

#技术亮点
多 LLM 支持: DeepSeek、阿里云百炼、openai、openrouter等，可灵活切换
高德地图 API: POI 搜索、天气查询、酒店推荐、地理编码
类型安全: 后端 Pydantic + 前端 TypeScript 全栈类型校验
响应式 UI: Vue 3 + Element Plus，支持移动端

#环境要求
Python 3.12+
Node.js 18+

#效果呈现
<img width="553" height="298" alt="图片" src="https://github.com/user-attachments/assets/6f05deec-2b58-423d-af7b-8e9cce145a09" />
<img width="553" height="298" alt="图片" src="https://github.com/user-attachments/assets/6eeefbe2-7800-41e8-8be2-74d1b4606e6b" />
<img width="553" height="274" alt="图片" src="https://github.com/user-attachments/assets/0bdbf29a-15db-4e89-9e14-8475f2847e14" />
<img width="553" height="274" alt="图片" src="https://github.com/user-attachments/assets/7de63c62-9fc1-4382-87a1-8797d8a48934" />
<img width="553" height="349" alt="图片" src="https://github.com/user-attachments/assets/8120c3d6-4c23-4e02-96ac-f32442ed8142" />

#导出样例
<img width="2560" height="4814" alt="itinerary-广州" src="https://github.com/user-attachments/assets/3368d285-7809-4b06-ae9d-4dadff890863" />








