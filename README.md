### 邵松

------

#### 个人信息

------

- 性 别：男 											  年 龄：27
- 手 机：15594555052                           邮 箱：songsshao@foxmail.com
- 专 业：计算机科学与技术                    岗 位：研发工程师

#### 工作及教育经历

------

- 博彦科技：前端开发⼯程师 					          2021.08.16 ~ 至今
- 神玥软件：软件开发⼯程师部⻔技术负责⼈	2019.07.03 ~  2021.08.13
- 安康学院 					 					                    2015.09.01 ~ 2019.06.24

#### 专业技能

------

- 熟练使用：React、JavaScript、HTML、CSS、TypeScript、Java
- 前端框架：Taro-UI、JQuery、Echarts、Antd、ThreeJS
- 前端服务层：Mobx、Redux
- 前端请求服务：Axios、Ajax、fetch
- 前端资源加载/打包⼯具：Webpack 、UmiJS、Vite
- 后端微服务框架：SpringBoot
- 后端服务框架：SpringMVC、Struct2
- 后端Jdbc层：MyBatis、Hibernate
- 框架：Django、Pillow、requests、urllib3、bs4、Selemiun、lxml
- 数据库：MySQL、Oracle、Redis、SqLite、memcache
- 服务器：Tomcat、Nginx
- 算法：快速排序、深度优先策略、贪心算法

#### 项目经历

------

1. 博彦科技 - 某某云开发平台 - 2020年9⽉⾄今
   - 职 责：主要负责项⽬开发、框架服务维护、⾃动化部署、处理程序紧急问题等职责
   - 内 容：在项⽬期间负责前端⻚⾯设计、开发、维护等。主要通过该项⽬对⾃⼰的个⼈技能有了⼀个较强的提升，对于⾃⼰的知识⾯有了⼀个更⾼层次的认知，使⽤第三⽅⼯具进⾏快速开发，采⽤React技术栈和其周边⼯具开发，项⽬架构采⽤umiJs + vite 协同开发模式。技术难度是项目系统结构复杂，系统代码老旧，改造升级难度大大增加。



2. 神玥软件 - ⼴东动态监管平台 - 2020年6⽉⾄2021年7⽉

   - 职 责：主要负责项⽬的开发、开发技术⽀持、框架服务、部署、处理程序紧急问题等职责

   - 内 容：在该项⽬中同样采⽤全后端分离架构，该项⽬中不同之处在于使⽤架构发⽣改变，增加使⽤接⼝获取数据、动态切换数据源等。

   - 项⽬架构：

     前端+展示服务后台+数据抓取服务端+定时器数据处理服务端+接⼝获取数据端+第三⽅数据获取服务端组成。

     在前端开发中，项⽬使⽤4层架构进程⻚⾯处理，临时数据存储使⽤session进⾏，使⽤有效⻚⾯数据传输保证⻚⾯独⽴性、依赖性降低、项⽬可扩展性增加、便与开发进⾏。

     在定时器数据处理服务端不同之处，在于其需要兼容多中不同数据源，主要包oracle、db2(及其as400版本)、MySQL等，兼容其不同语法进⾏处理，连接⼯具类处理，初始化连接等问题，后台数据报⽂传输使⽤某某加密⽅式实现。

     第三⽅接⼝程序实现主要是提供于第三⽅进⾏对接数据，汇总返回数据，进⾏数据统计，完成展示。

   - 技 术：React、antd、Spring、SpringBoot、mybatis、SpringSecurity、oauth2、Sqlite、MySQL、redis等。



3. 神玥软件 - 公积⾦监督管理云平台 - 2019年8⽉⾄2020年5⽉

   - 职 责：主要负责项⽬的开发、开发技术⽀持、框架服务、部署、处理程序紧急问题等职责

   - 内 容：在公积⾦监督管理云平台开发中，使⽤前后端分离架构。

   - 项⽬架构： 前端+展示服务后台+数据抓取服务端+定时器数据处理服务端组成。在前端开发中，使⽤React开发框架辅助antd、amap、echarts、mobx、Axios等，借助webpack打包压缩⽂件等技术实现前端开发任务。

     在后端技术⽀撑⽅⾯使⽤SpringBoot微服务框架，进⾏数据展示层⾯服务服务端程序编写。

     在数据获取⽅⾯，数据均来⾃于各现场数据库，编写定时器服务端程序，使⽤频率为5 分钟到1⼩时不等等⽅法策略实现，适⽤于各种不同的核⼼版本库，通过sqlite轻量级数据库进⾏数据暂存，等待公司客户端服务器抓取数据，该技术由于公司限制使⽤该⽅法策略实现，在程序实现⽅⾯使⽤mybatis解析SQL⽅式编写，xml配置⽂件进⾏SQL配置，通过dao4j进⾏xml解析获取对应sql，使⽤XMLScriptBuilder进⾏获取SQL处理⽣成sqlSource资源，根据sqlSource获取boundSql对象获取编译后带有占位符资源对象，获取占位符信息数据，替换对应参数完成可执⾏sql。

     在数据抓取客户端使⽤5分钟频率去更新数据，实时抓取数据与数据可进⾏⽐较并且进⾏更新。

     对接使⽤微型前端服务框架，加载第三⽅服务程序。

   - 技 术：React、antd、Spring、SpringBoot、mybatis、Sqlite、MySQL、redis等。



4. 个人项目 - 微信⼩程序API+停⻋场客户端编写 - 2018年11⽉⾄-2019年1⽉
   - 职 责：项⽬设计、需求、开发、部署等
   - 内 容：该项⽬主要使⽤微信⼩程序、Django框架、H5前端完成。后端基于Django框架，主要是在Django框架中进⾏setting.py 配置，url编写，数据库模型创建、映射⽂件，view视图编写，服务代码编写。Api返回数据序列化处理、json数据处理。进⾏停⻋场实时数据监控数据处理。并且使⽤window 2008 server R2 进⾏环境部署，服务器搭建使⽤ nginx+fastCGI+Django进⾏配置，使⽤https进⾏数据访问。
   - 职 责：负责编写model、admin、view、API编写、⽀付接⼝编写；
   - 开发⼯具、语⾔及框架：JetBrains PyCharm、MySQL、Dreamweaver、Photoshop、Python、Django、HTML、CSS、JavaScript、Ajax、jQuery、Bootstrap以及Python开源框架。
5. 个人项目 - 爬取wikipedia深度为3的超链接
   - 内 容：Wikipedia 深度为3的所有URL资源链接的获取（1000万条记录），采取进程的⽅法进⾏访问Wikipedia，根据深度优先策略进⾏URL第⼆层资源遍历获取第三层URL资源。在数据处理过程中，使⽤request2技术获取源码、解析拦截⽆⽤⽂件，使⽤lxml技术进⾏分离出需要数据，并且检测出可⽤链接， 后进⾏URL保存到本地资源。
   - 难 点：在获取Wikipedia 网站数据的时候需要处理反爬虫、过滤网站数据、获取需要的资源进行解析。

#### 获奖经历

------

- 博彦科技 - 技术之星
- 信息安全一级证书

#### ⾃我评价

------

- 爱 好：骑⾏、登⼭、旅游、⽻⽑球、篮球、乒乓球。
- 评 价：在我的从事计算机⾏业学习到⼯作也有6年之久，从刚开始对计算机的感兴趣到现在的⼯作，以及它成为了我⽣活不可或缺的⼀部分，都是⼀个变化和不多学习的过程，在这个过程中，经历了太多太多的苦难，从刚开始的⼀窍不通到现在的应⽤⾃如以及更深层次的了解，都是在不断⾃学中成⻓起来。需要这般⾃学就必须要有⾃学的动⼒和持之以恒的坚持都是不可缺少的。学习过程中不断的纠正⾃⼰学的⽅向，处理存在的问题以及快速处理问题的解决⽅法，都是⼀个能⼒的提升。 后还有就是对这个⾏业的热爱。

#### git数据分析

[![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=songsshao&show_icons=true)](https://github.com/anuraghazra/github-readme-stats) 

[![算法数据分析](https://github-readme-stats.vercel.app/api/top-langs/?username=songsshao)](https://github.com/SongsShao/niuke-hj)

