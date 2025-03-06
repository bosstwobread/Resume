[Chinese Version](https://github.com/bosstwobread/Resume/blob/main/Resume-cn.md)
# Personal Information

- Lin Xisheng / Male / 1986
- Bachelor's Degree / Zhejiang Forestry University, College of Information Technology and Information Management
- Start of Work: 2008

- Desired Position: Software Engineer / Project Manager
- Desired Cities: Remote

- Phone: 13777365321
- Lindedin: [Homepage](https://www.linkedin.com/in/nelson-lin-05671834b/)
- Email: linxishengjiong@gmail.com
- GitHub: https://github.com/bosstwobread
- WeChat: bosstwobread
- Ability to do night shift and willing to work remotely

---

# Personal Highlights

- Proficient in abstract thinking and Agile software development, design principles and patterns, adapt to various future business scenario and provide flexibility to handle potential changes
- Possess capabilities in product requirements, design, architecture, development, and delivery
- 15 years of development, 10 years of architecture, and 8 years of technical team management experience
- Proficient/Familiar with most mainstream programming languages, 
- skilled in system architecture, components, databases, APIs, product design, front-end and back-end development, and system CI/CD deployment
- Received individual/team technical innovation awards from the company
- Achieved excellent science scores in school and won third prize in the zhejiang provincial physics competition

---

# Work Experience

## 2022.04-2025.2 (3 years) Zhejiang Hengtian Software Co., Ltd. (.NET/C#/VB/MSSQL/PostgreSQL/Windows command/AWS)

[Homepage](https://en.hengtiansoft.com/homepage)
### Job Responsibilities
- Tech lead responsible to assign tasks to Junior developer and perform code review and solve technical difficulties encountered
- Attend Daily stand up to debrief daily work and communicate with foreign clients effectively in a professional manner
- Nominated to serve as solution architect of  company internal .NET Core based solution to a general business scenario.

### Achievements
- Utilize automated Windows command scripts to achieve automatic deployment, as efficiency is improved by reducing the time consumed from one day to minutes
- Optimized hundreds of SQL based stored procedures, developed common function and simplified numerous SQL statements, removing repetitive code (~1k lines to few hundreds) to improve the maintainability and readability
- Established technical specifications documents and numerous technical guidance manuals for team development, training new developers

## 2013.04-2021.5 (8 years) Zhejiang Wanwei Space Technology Co., Ltd. (.NET/JAVA/NODE/PHP/Docker)

[Homepage](https://www.zjugis.com/home/index.html)
### Job Responsibilities
- Managed the E-Government platform department team, established company technical standards and responsible for flowcharts, database, architecture design and coding
- Platform-based project management, there are about dozens of projects based on this platform, responsible for some of the more technically difficult projects

## 2009.04-2013.04 (4 years) Eastern Communications Co., Ltd. (Javascript/.Net)

### Job Responsibilities
- Developed core functionalities for the company’s web GIS map engine
- Developed chart engines and related plug-ins
- Build a map tile background downloader

## 2005.09-2009.04 Zhejiang Forestry University, Information and Techonology Laboratory (C++)
[Homepage](https://www.zafu.edu.cn/)
### Job Responsibilities
- Developed software for the College of Information Technology
- Assisted teachers in teaching C++ software courses
- Assisted professors with graduation project guidance
- Social practice in poverty-stricken areas

### Achievements
- Developed independent software plugins such as pagination navigation and permission components
- Built a calendar plugin
- Help maintain the college management system, etc. 

---

# Main Projects

## State street SQL Server Reporting Services 2023.5-2025.2
- Help established and maintained the complex reporting system for State Street Registry Business Unit for daily fund operations and data reconciliation
- Manage the codebase for SQL Server reporting service project including SQLs and Reports which are used to implement complex business requirements and calculation logics, such as recursive algorithms
![reports](https://github.com/bosstwobread/Resume/blob/main/Resource/State%20street1.jpg "reports")

## Hengtian.net core architecture 2022.2-2023.4
- Company-level architecture, providing a fundamental framework for projects of the company
- Based on Dapr's microservice architecture, it is encapsulated for the company's business scenarios and optimizes the development process

## Backend Logic Configuration Framework (Node.js/Vue) 2021.9 - 2021.12
[git address](https://github.com/bosstwobread/YFormIntelligence)
### Framework Overview
- Provides a powerful and flexible way to build complex business applications, focusing on business logic through configuration rather than coding
- By studying the functions that can be realized by programming languages, the logic abstraction is split into technical instructions with the smallest granularity, and a low-code platform is built from the bottom up
- Use json configuration to implement full business logic, such as user authentication, CRUD and export, etc.
### Framework Highlights
- Configuration-driven development, most business functions are implemented through configuration, and those that cannot be implemented are solved by introducing business plug-ins
- The functions developed by configuration come with parameter legitimacy verification, logging, caching, etc.
- Extensible plug-in architecture
### Future Outlook
- Provide visual configuration
- Extend the accessible business plug-ins to non-Node languages, i.e. service mode, to support cross-language

# E-Government Platform (C#/.NET/JAVA/NODEJS/ORACLE/Docker) 2014.4-2021.5
[Demo Link](http://114.215.200.79:81/z_web_container/Home/blueIndex)

### Project Overview
- Provides a unified development platform for enterprise and government software, supporting language-independent customization development on WEB, APP, and hardware.
- Features include user organization permissions, a self-developed BMPS2.0 workflow engine, a reporting system, business-related middleware, large file storage, continuous deployment, customizable forms with flexible configuration, ensuring critical pages response times within 200ms.
- The platform has undergone three iterations, evolving from a C/S to a B/S and then from .NET version to Java version.
- Over dozens projects have been developed based on this platform, e.g. Wuxi's Four-in-One Platform, Taizhou's One Map, Ningbo's Land Consolidation, Juxian County's One Map in Shandong, and Xuzhou's Government OA, among others.

### Platform Highlights
- UI: Supports multi-project page fusion technology, which is similar to the componentization concept adopted by the react framework, but logically sharing is more convenient, different projects can directly use and consume without publishing components, by the way, I didn't know the react when I implemented this function
- Openness: More than 2000+ open APIs and 3000+ configurable options.
- Configuration Flexibility: All configurations support both forward and reverse configuration. e.g. permissions can be assigned via roles, or roles can be reversely configured via permissions.
- Deployment features: Support dual-channel deployment, automatic switching during downtime, hot updates, private deployment, system pre-release， i.e. full use of online real data for testing, and no user awareness.
- Cross-Platform: Support Linux/Windows dual-platform deployment and customization development in all mainstream languages.
- Multi-Database Support: Currently including ORACLE, domestic databases such as Hanhigh, and is scalable to MySQL/SQLServer/PostgreSQL and other relational databases.
- Workflow Engine: Supports gateways, single approval, multi-approval, series approval, parent-child workflows, splitting and merging; supports version management and pre-release testing in real data environments; supports SQL, RestAPI, and JavaScript script integration; Workflow monitoring, etc.
- Reporting System: Supports SQL and RestAPI as data sources; enables form, chart, and QR code design; includes export and print functionalities and so on.
- Distributed Big File Storage: Support utilizes multiple servers with encrypted file storage.
- Security: API calls require authorization from the authentication center, data packets are encrypted using HTTPS, and files are encrypted.
- UI Themes: Provides multiple themes, e.g. homepage styles; supports custom component style configurations and fully customized pages.
- Development document management: With code as the center, all technical documents are included in code review and reflected in the documents through relevant plug-ins.
- Third-Party Application Integration: Supports integrations with DingTalk, WeCom, SMS, Email, or customized third-party services.
- System Monitoring: Records all operations and API calls, generating user-friendly data and visual charts.
- Low-code platform: The design is basically completed, but it is stopped due to company strategy.
![workflow](https://github.com/bosstwobread/Resume/blob/main/Resource/egvm1.png "workflow")


## Panoramic Image Display (PHP/Javascript) 2016.4-2016.5
- Synthesize the pictures taken by drone and display the panorama.

## Data Migration (C#/ORACLE) 2013.4-2014.4
- Achieved configurable data migration, abstracting business migration relationships into configurable parameters based on different database characteristics (Oracle/MSSQL/MySQL), transfer of over a hundred million data records within a few minutes

## Eastcom WebGIS Web Map Engine (Javascript) 2009.4-2013.4
### Project Overview
- A fully self-developed WebGIS web map engine.
- Core functionalities include map projection algorithms, zooming, dragging (buffering), distance measurement, layers, and graphical elements (points, lines, polygons), with open interfaces.

### Engine Highlights
- Supports third-party map tile integration via analyzing tile slicing algorithms from platforms like Baidu and eCity.
- Map rendering supports real-time refresh of up to thousands of graphics elements, which is achieved by optimizing asynchronous refresh graphics elements, map positions, graphics element memory usage and related JavaScript native code
- Chart plugins support interactive drag-and-drop functionality, allowing users to move data points directly on graphs like line charts.
- Map-related operations and other algorithms are accurate to the pixel(e.g. some map software, there is a deviation of one or two pixels)
- Write a tile download tool to grab tiles of third-party maps

# Additional Amateur Projects
- WeChat Sudoku Mini application (Search '艺妍数独' on WeChat Mini application): A side project promised to my daughter during winter break; I personally think its design is superior to most similar games on the market.
- Chrome Bookmark Plugin: Allows users to quickly open their bookmark menu with a keyboard shortcut from any webpage. [Download](https://download.csdn.net/download/bosstwobread/7171427) | [Forum Post](https://bbs.csdn.net/topics/390755412?spm=1001.2014.3001.6377)
![chrome_plugin](https://github.com/bosstwobread/Resume/blob/main/Resource/chrome_plugin1.jpg "chrome_plugin")
- Cascading Folder Image Compression Tool (C#): Enables configurable compression rates and storage locations for bulk image compression. Used to save computer space

# Skills & Expertise

- Design: Agile software development, design principles and patterns
- Programming Languages: Node.js, .NET, PHP, Java, VUE, React, Python, C++, VB, Android
- Databases: Oracle, MySQL, PostgreSQL, MongoDB, MSSQL, SQLite
- Deployment: Linux, Docker
- Third-Party Integrations: Alibaba IoT, WeChat Pay, AWS, Qiniu Cloud, JPush, China Mobile, DingTalk, Gaode Maps
- Awards: Individual & Team Innovation Award, Provincial Physics Competition Third Prize

---

# Acknowledgment

Thank you for taking the time to read my resume. I look forward to get opportunity to work with you!
