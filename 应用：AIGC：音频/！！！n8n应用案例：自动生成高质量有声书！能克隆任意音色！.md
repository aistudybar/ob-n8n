
n8n神操作来了！一本电子书，自动生成高质量有声书！能克隆任意音色！完全免费的AI工作流！
https://www.youtube.com/watch?v=xDWRfvQMBDs

![image.png](https://repo.in4tree.com/2026/02/02_1770095374972.png)



![image.png](https://repo.in4tree.com/2026/02/02_1770093382607.png)

内容切分
使用Simple Vector Store（简单，但不支持永久持久化！）



文本转音频：F5 TTS（几秒声音样本就能克隆声音！长文本效果很好）
可以本地部署，无额度限制！但为演示方便，使用Hugging Fase上部署的免费F5 TTS服务（有额度限制！）
![image.png](https://repo.in4tree.com/2026/02/02_1770094183201.png)

![image.png](https://repo.in4tree.com/2026/02/02_1770094409466.png)

![image.png](https://repo.in4tree.com/2026/02/02_1770094497545.png)
上面代码需要gradio client库！

使用Execute Command节点运行上面的Pyson代码（因n8n的Python是运行在沙盒里的、无法添加其它库！所以不能用Code节点）

![image.png](https://repo.in4tree.com/2026/02/02_1770094796469.png)

重新定制一个带有gradio client库的docker，然后再运行n8n

如果要持久化保存这个docker，需要生成一个新的docker的镜像

