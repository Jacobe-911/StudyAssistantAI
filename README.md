# StudyAssistantAI
一个基于 OpenAI Agents 和 LangGraph 的 AI 学习助手，探索多智能体在知识检索、推理与任务自动化中的协作能力。
📚 StudyAssistantAI

一个基于 OpenAI + LangGraph + RAG 的智能学习助手，支持 知识问答、模拟试卷、自动评分、学习分析，并通过 Streamlit 提供交互界面。

✨ 项目简介

StudyAssistantAI 是一个面向学习和企业培训场景的 AI Agent 应用。
用户可以上传自己的学习资料（PDF / DOCX / PPTX），系统会自动解析、向量化，并存入向量数据库（支持 OpenSearch 和 FAISS）。

在此基础上，项目提供以下功能：

📂 知识管理：上传学习资料，构建知识库

🤖 智能问答：基于 RAG（检索增强生成）的问答助手

📝 模拟试卷：根据知识点生成试卷，用户在线作答

✅ 自动评分：对用户答案进行打分，并生成反馈

📊 学习分析：根据答题结果评估知识掌握程度，给出个性化学习建议

🔧 技术栈

LLM 模型：OpenAI GPT-4 系列

Agent 框架：LangGraph

检索增强：RAG (OpenSearch / FAISS)

后端服务：FastAPI

前端交互：Streamlit

文件解析：pdfplumber, python-docx, python-pptx
