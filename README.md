### **2025春季-Web应用程序开发课程项目**

**要求：**  
本课程需要独立开发一个**完整的 Web 应用**，采用**SpringBoot + Vue** 进行**前后端分离**开发，涵盖课程的核心知识点。可以从以下**示例主题**中选择一个，或自行确定符合要求的主题。

---

## **示例主题**

### **1. 任务管理系统（Task Management System）**
- **功能**：
    - 创建、编辑、删除任务，支持任务描述、截止日期、优先级设置。任务可以分配给特定用户或团队，支持任务负责人变更。
    - 任务状态（待处理、进行中、已完成）实时更新，支持任务进度条。任务截止前自动提醒（邮件/短信/站内通知）。
    - 任务完成率、平均完成时间、团队任务分布等统计图表。
- 适用场景：个人时间管理、团队协作工具。

### **2. 在线学习平台（Online Learning Platform）**
- **功能**：
    - 课程管理：教师可创建课程，上传视频和测验。
    - 学生学习进度追踪，支持作业提交与自动评分。
    - 讨论区互动，支持学习数据可视化统计。
- 适用场景：在线教育、课程管理。

### **3. 个人记账系统（Personal Finance Tracker）**
- **功能**：
    - 记录收入与支出，支持分类管理。
    - 预算设定与超支提醒，月度财务统计分析。
    - 可视化趋势图，支持数据导出（CSV/PDF）。
- 适用场景：个人财务管理、预算规划。

### **4. 在线投票系统（Online Voting System）**
- **功能**：
    - 用户创建投票，支持单选/多选与截止时间。
    - 匿名投票与权限控制，防止重复投票。
    - 结果实时统计，可视化展示投票趋势。
- 适用场景：学校社团、公司内部决策。

### **5. 电影推荐系统（Movie Recommendation System）**
- **功能**：
    - 电影信息展示，支持用户评分与评论。
    - 个性化推荐系统，基于用户行为推荐影片。
    - 搜索与分类筛选，热门电影趋势分析。
- 适用场景：电影爱好者、内容推荐。

### **6. 代码片段分享平台（Code Snippet Sharing）**
- **功能**：
    - 用户分享代码片段，支持多语言语法高亮。
    - 搜索、分类、收藏代码，支持在线讨论。
    - 代码运行沙盒，提供安全执行环境。
- 适用场景：程序员社区、学习资源共享。

### **7. 二手交易平台（Second-Hand Marketplace）**
- **功能**：
    - 用户发布商品，支持图片上传与分类浏览。
    - 站内私信、留言功能，促进买卖沟通。
    - 交易管理，支持支付与用户评价系统。
- 适用场景：校园二手市场、闲置物品交易。

### **8. 智能文档助手（AI-Powered Document Assistant）**
- **功能**：
    - 用户上传 PDF / Word 文档，AI 进行摘要提取、关键词提取。
    - 支持**问答功能**，用户可以对文档内容提问，LLM 进行回答。
    - 语法纠错、文本改写、智能分类。
- **适用场景**：论文阅读、企业文档管理、合同分析。

### **9. AI 代码审查系统（AI-Powered Code Review）**
- **功能**：
    - 用户提交代码，系统使用 LLM 进行代码质量分析，提供优化建议。
    - 检测潜在 Bug、代码风格、性能优化点，并自动修正部分代码。
    - 支持多种编程语言（Python、Java、JavaScript）。
- **适用场景**：开发团队代码审查、编程作业自动评分。

### **10. AI 语音转写与摘要系统（AI Speech-to-Text & Summarization）**
- **功能**：
    - 用户上传语音文件（如会议录音、采访录音），AI 进行**自动转写**。
    - AI 进行摘要提取、关键词提取，生成可视化报告。
    - 可支持多语言（中文、英文等）。
- **适用场景**：会议记录、新闻采访、学术研究。



---

## **项目开发要求**
### **1. 后端（SpringBoot）**
- **RESTful API 设计**：采用 `SpringBoot + Spring MVC` 进行 API 开发。
- **数据库**：使用 **MySQL / PostgreSQL**，使用 `Spring Data JPA` 进行持久化。
- **身份认证**：使用 `Spring Security + JWT` 或 `OAuth2` 进行用户身份验证。
- **业务逻辑**：后端需遵循**Controller-Service-Repository** 分层架构，使用 `AOP` 进行日志记录。
- **AI / LLM 接口**：
    - 可使用 OpenAI API、Gemini API、Llama API 进行 LLM 交互。
    - 可结合 Hugging Face 开源模型，部署本地 AI 服务。

### **2. 前端（Vue3 + TypeScript）**
- **Vue3 + Vite**：搭建前端项目，使用 `Vue Router` 进行页面导航。
- **状态管理**：使用 `Vuex` 或 `Pinia` 进行全局状态管理。
- **UI 设计**：使用 `Element Plus` 或 `Ant Design Vue` 进行界面美化。
- **数据可视化**：可使用 `ECharts` 进行数据统计展示（适用于财务管理、健康管理等）。
- **前后端交互**：使用 `Axios` 进行 API 请求，并做好错误处理。

### **3. 其他技术要求**
- **API 文档**：使用 `Swagger` 或 `Postman` 生成接口文档。
- **测试**：使用 `JUnit` 进行单元测试，使用 `Postman` 测试 API。
- **部署**：可以使用 **Docker** 容器化后端，或者将前端打包并部署到 `Nginx` 上。

---

## **作业评分标准（100 分）**
| 评分维度 | 评分权重 | 评分标准 |
|----------|---------|----------|
| **功能完整性** | 30 分 | 实现所有核心功能，确保前后端交互流畅 |
| **代码质量** | 20 分 | 代码清晰、模块化，符合 Java 和 Vue 规范，合理使用注释 |
| **数据库设计 / AI & LLM 集成** | 15 分 | 设计合理，表结构规范，支持增删改查; // 结合 AI或LLM 提供智能化功能，如自动生成、问答、数据分析 |
| **前后端交互** | 15 分 | API 设计良好，前后端对接流畅，符合 RESTful 规范 |
| **UI 设计** | 10 分 | 界面简洁美观，用户体验良好 |
| **测试与部署** | 10 分 | 提供 API 文档，有测试用例，能正常运行 |

---

## **提交要求**
1. **GitHub/Gitee仓库**（包含完整代码和 README 说明）。
2. **说明文档**：
    - **数据库/AI业务流设计文档**（ER 图 + 主要表结构）/ （系统架构图+ 时序图）。
    - **API 文档**（Swagger / Postman）。
    - **系统截图**（展示关键功能）。
    - **运行及部署说明**（如何运行前后端代码）。

---

## **截止日期** 2025年06月03日 24:00
