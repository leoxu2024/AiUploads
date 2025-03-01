# AiUploads

AiUploads，一个又一个上传已设置本地文件夹的所有级联子文件夹的文件到指定的RAGFlow知识库，然后自动点击解析，直到完成所有文件处理。

V0.1.0：命令行执行批量处理

V0.2.0：新增网页方式

# 客户案例

1、我有10G文件，怎么样上传呢？

2、我上传文件到RAGFlow，太多了，今天要完成任务啊，怎么办？

# 因缘

批量自动化上传文档到RagFlow知识库
[RagFlow](https://github.com/infiniflow/ragflow)是一个基于 LLM 的问答系统，能够快速构建智能问答平台。然而，RagFlow 默认的知识库上传界面存在一些局限性：每次只能上传有限数量的文件，并且上传后还需手动启动解析流程，当需要上传大量文件时，这样的操作便显得有些繁琐。
为了简化这一过程，编写了一个脚本，该脚本可以遍历指定目录，自动逐个将文档上传至 RagFlow 知识库，并立即启动解析。当一个文档解析完成后，脚本将自动上传并解析下一个文档。特别是在需要上传大量文件时，这显著减少了人工干预，避免了手动分批上传和解析的等待时间。

# 特色功能说明

1、批量自动化无人值守上传文档到智能知识库

2、支持从wiseflow采集到的数据定时增量上传到智能知识库

3、可定时执行批量处理任务

4、可使用网页方式进行参数配置、执行批量处理、查看待重试列表

# 工具截图

![微信图片_20250301105952](https://github.com/user-attachments/assets/68b79673-ecbb-4522-a912-b0ad9db6a1e4)
![微信图片_20250301110101](https://github.com/user-attachments/assets/a7814ab4-20b1-44cc-9e37-d3faa960b7e9)
![微信图片_20250301110026](https://github.com/user-attachments/assets/a63f4bec-7bcb-4e7b-ae18-fc844f49ba12)
![微信图片_20250301110021](https://github.com/user-attachments/assets/8bc7a817-6960-4d3d-909c-e031e98c0527)
![微信图片_20250301110017](https://github.com/user-attachments/assets/426a9533-9cb8-44f7-ab75-c3468f9956aa)


# 需求提交

请到[issues](https://github.com/leoxu2024/AiUploads/issues)里提交问题及需求

# 远程一对一部署服务

需要有偿远程一对一部署服务，请添加微信jzhfuwu2024






