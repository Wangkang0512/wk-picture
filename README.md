wk-picture
wk-picture 是一个基于 Vue 3、Spring Boot、COS 和 WebSocket 构建的智能协同云图库平台，旨在为个人用户、企业团队和管理员提供高效的图片管理与协作功能。

🖼️ 项目简介
该平台支持用户上传、检索、管理和协同编辑图片，适用于以下场景：

公共图库：所有用户可公开上传和检索图片素材，适用于表情包网站、设计素材网站、壁纸网站等。

个人空间：用户可将图片上传至私有空间，进行批量管理、检索、编辑和分析，作为个人网盘、相册或作品集。

团队协作：企业可开通团队空间，邀请成员共享图片并实时协同编辑，提高团队协作效率，适用于企业活动相册、内部素材库等。

管理员功能：管理员可上传、审核和管理图片，并对系统内的图片进行分析。

⚙️ 技术栈
后端：Java、Spring Boot、MyBatis-Plus、MySQL、Redis、Caffeine、ShardingSphere、Sa-Token、WebSocket

前端：Vue 3

其他：Jsoup（数据抓取）、COS（对象存储）、AI 绘图大模型接入


📦 项目结构


wk-picture/
├── httpTest/             # HTTP 测试相关文件
├── sql/                  # 数据库脚本
├── src/                  # Java 源代码
├── .gitignore            # Git 忽略文件配置
├── README.md             # 项目说明文档
└── pom.xml               # Maven 项目配置


🚀 快速开始
环境要求
Java 11 或以上版本

Node.js 14 或以上版本

MySQL 5.7 或以上版本

Maven 3.6+

安装步骤
克隆项目：

git clone https://github.com/Wangkang0512/wk-picture.git
cd wk-picture
配置数据库：

在 MySQL 中创建数据库，并执行 sql/ 目录下的脚本初始化数据表。

修改 application.yml 文件中的数据库连接配置。

构建并运行后端：


./mvnw clean package
java -jar target/wk-picture-*.jar
构建并运行前端：

进入前端项目目录（假设为 frontend/）：


cd frontend
npm install
npm run serve
📄 文档与支持
项目目前处于开发阶段，详细文档和使用指南将在后续更新中提供。

🤝 参与贡献
欢迎社区开发者参与项目的开发与优化：

提交 Issue 或 Pull Request

提出功能建议或报告 Bug

优化文档或添加示例
