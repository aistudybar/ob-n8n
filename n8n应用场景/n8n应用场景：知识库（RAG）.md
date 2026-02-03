
---
目录：
上一页：
下一页：
关键词：
相关链接：[https://www.youtube.com/@n8n%E8%87%AA%E4%B9%A0%E5%AE%A4]()


---

# 【】

RAG AI Agent + n8n 組合技讓你效率暴增 10 倍
https://www.youtube.com/watch?v=PlVYcuT_vvE


Google Drive新增文件时触发工作流，获取文件ID，然后删除老旧文件去重，读取PDF文件
![image.png](https://repo.in4tree.com/2026/02/02_1770073898353.png)

AI节点：使用Embeddings模型，把文本内容转换为向量数据，然后存入向量数据库（Supabase既有向量数据又有正常栏位数据、比Pinecone好！）
![image.png](https://repo.in4tree.com/2026/02/02_1770074534370.png)

搭配Document Loader，进行切割、是否保留块之间的部分重叠
![image.png](https://repo.in4tree.com/2026/02/02_1770074873607.png)

![image.png](https://repo.in4tree.com/2026/02/02_1770075687537.png)


  
還在手動更新AI知識庫？不會 n8n 和 Flowise Document Store（只能手动！不支持Google Drive！可以用上面的例子替代完成），你的職場危機已經來臨！
https://www.youtube.com/watch?v=7UvGfxlwg0c

如何知道当前知识库有哪些文件？
当文件有更新或修改，如何更新知识库？

![image.png](https://repo.in4tree.com/2026/02/02_1770081942062.png)

例如网站爬虫
![image.png](https://repo.in4tree.com/2026/02/02_1770082426833.png)


![image.png](https://repo.in4tree.com/2026/02/02_1770082485520.png)

![image.png](https://repo.in4tree.com/2026/02/02_1770082545727.png)
![image.png](https://repo.in4tree.com/2026/02/02_1770082611392.png)

![image.png](https://repo.in4tree.com/2026/02/02_1770083359313.png)


？？？？？？？？？
# 知识库优化

https://www.reddit.com/r/flowise/comments/1bpgta5/flowise_help_for_beginners/
我正在尝试使用 Flowise 部署我的第一个网站聊天机器人。它基于 RAG 算法，但我仍然无法获得“准确”的回复。我基本理解了所有步骤，但就是无法得到准确的回复。我使用了 PDF 文件阅读器、Pinecone 矢量数据库、text-embedding-3-small、GPT 3.5 Turbo 等。请问有什么建议可以帮助我改进提示、代理、流程等等，从而获得更准确的结果？我了解过使用重叠提示策略的自适应 RAG，但想知道是否还有其他方法可以尝试？谢谢！



# 【知识库RAG】

https://www.youtube.com/watch?v=Tn1k0pg2pEc

通过表单接收PDF/CSV/JSON
分割成每1,000个Token一个片段
生成向量，然后存储到向量数据库中
并且使用文件名作为这个文档的唯一键
添加元数据：上传日期、文件类型

集成一个聊天机器人，根据知识库内容回答提问

![image.png](https://repo.in4tree.com/2026/01/31_1769927468304.png)


---

？？？？？【网站爬虫】输入网址、自动抓取网站的全部网页
AI最强辅助！n8n+crawl4ai工作流，一键抓取任意网站！搭建RAG知识库+MCP自动化，让你的AI更准！更强
https://www.youtube.com/watch?v=Y6C7kpNSrd4

---

？？？？？n8n搭建RAG系统：构建超灵活知识库 + 全能AI客服！本地部署+实战！
https://www.youtube.com/watch?v=LOWYPjSmFi4

