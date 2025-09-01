侣行 - 智能旅游出行管家顾问
项目简介
"侣行" 是我在学习了langchain框架后，在今年4-6月的时间里陆陆续续完成的一个小型的人工智能对话模型，覆盖了langchain框架的核心模块，适合没有llm基础、想学习大模型应用开发的同学学习了解，属于入门级项目，注意里面的value-key（大模型、以及高德地图）需要自己申请使用，代码里的已过期
这是一款基于 Spring Boot 和 Vue 开发的智能旅游出行管家顾问应用，旨在为用户提供全方位的旅游规划服务。通过该应用，用户可以查询旅游城市的景点、住宿、美食等信息，获取个性化旅游路线推荐，并可预约一对一的旅游指导服务。



功能特点
查询目标旅游城市的景点介绍、住宿推荐、特色美食
提供目标城市的交通方式、旅游联系方式及最佳旅游季节信息
查询天气预报、气候特点及年平均气温
推荐 2025 年不同季节热门旅游线路及小众旅游目的地
提供不同季节适宜的旅游装备建议及天气变化应对方案
根据用户预算和时间安排，推荐高性价比、体验丰富或轻松休闲的旅游方案
支持旅游规划一对一沟通预约服务

技术栈
后端：Spring Boot 3.5.0、Java 17、Maven
前端：Vue 3、Tailwind CSS、Font Awesome
AI 集成：LangChain4j
地图服务：高德地图 API
存储：Redis（用于聊天记忆存储）

项目结构
plaintext
consultant/
├── consultant/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/itheima/consultant/
│   │   │   │   ├── config/        # 配置类
│   │   │   │   ├── tools/         # 工具类（如预约服务）
│   │   │   ├── resources/
│   │   │   │   ├── static/        # 前端静态资源
│   │   │   │   ├── system.txt     # 系统提示配置
│   │   ├── test/                  # 测试类
│   ├── pom.xml                    # Maven配置
├── .idea/                         # IDE配置文件

## 安装与使用前提条件
JDK 17 或更高版本
Maven 3.6+
现代浏览器

安装步骤
克隆仓库
bash
git clone https://github.com/yourusername/consultant.git
cd consultant

构建项目
bash
cd consultant
mvn clean package

运行应用
bash
java -jar target/consultant-0.0.1-SNAPSHOT.jar

访问应用
打开浏览器，访问 http://localhost:8080
使用说明
首页提供旅游相关功能入口，可直接输入问题咨询
可通过侧边栏的 "出行工具" 查看路况和天气信息
如需个性化服务，可预约一对一旅游指导（需提供姓名、电话、时间等信息）

联系方式
如有问题或建议，请联系：[19935809799@163.com]
