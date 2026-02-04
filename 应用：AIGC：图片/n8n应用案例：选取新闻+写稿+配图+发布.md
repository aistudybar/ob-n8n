
  
n8n 自动运营个人网站！选取新闻+写稿+配图+发布，一次搞定！
https://www.youtube.com/watch?v=9eSVNmnhSiM

![image.png](https://repo.in4tree.com/2026/02/02_1770093211897.png)

选取新闻：NewsAPI

由新闻标题搜索相关的资料：tavily
![image.png](https://repo.in4tree.com/2026/02/02_1770091780049.png)


AI Agent：生成文章（输入专业提示词！）
![image.png](https://repo.in4tree.com/2026/02/02_1770092083959.png)

用OpenAI节点生成插图图片（比DALL-E更人性化！注重文字内容！）

用Edit Image节点：调整大小

Http节点：上传插图到WordPress媒体库（或R2存储桶等）
![image.png](https://repo.in4tree.com/2026/02/02_1770092745862.png)


Http节点：填写图片描述信息
![image.png](https://repo.in4tree.com/2026/02/02_1770092797368.png)
![image.png](https://repo.in4tree.com/2026/02/02_1770092847094.png)

Http节点：WordPress发布

Wait节点：10秒，Loop内等待10秒后再发送下一条！