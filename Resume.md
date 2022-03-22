# 孙翔宇

## 基本信息

- Phone: +86 15526679740
- Email: 1339184537@qq.com
- Github: <a href='https://github.com/FuzzyFade'>Rhuzerv</a>
- Blog: <a href='https://www.notion.so/Area-51-Alien-WTF-Records-8739165b5efd4e32b6704f55e51c0511'>Area-51-Alien-WTF-Records</a>
- Birth: 10/05/2000

## 教育经历

### 南昌大学

- 专业: 物理学 (211 本科)
- 预计毕业日期: 2022 年 6 月

## 技能树

### 前端领域技能
- 跨端框架及其业务场景 Cross Platform
- 前端框架开发与调优 Framework
- 状态管理策略 State Manager
- Low Code
- 在线协同场景（ot / crdt）
- Nodejs 服务端开发

### 关键词
- Typescript | ES6+
- ReactJS
    - FC Components | Hooks
    - React Native | Taro
    - NextJS
    - Webpack ｜ Vite ｜ Snowpack
    - Redux | Zustand | Jotai
- NodeJS
    - Express | Fastify | Eggjs
    - MongoDB | Mongoose | MySQL
    - NestJS
- Docker | Docker-compose
- linux | Git

## 工作经历

### <a href='https://tech.taobao.org/'>阿里巴巴集团·淘系技术部</a> <i>前端框架开发</i>

淘系前端架构团队 Rax & ICE

- 负责集团基础通用研发框架的开发与维护，推动技术演进的同时，保证基础研发设施的高可用性
- 主推 icejs 2.0 构建侧 / 运行时 / Native ESM / 状态管理 等能力的开发与重构，积极落地前端架构技术领域最佳实践
- 帮助集团其他开发同学优化项目构建时体验，并解决大型项目运行时的性能瓶颈
- 参与团队影响力和开源文化建设、以及团队开源项目的迭代和维护

### <a href='https://www.tencent.com/'>腾讯科技 (深圳) 有限公司</a> <i>前端开发</i>

PCG 移动商业产品部·前端团队

- 建设内部可视化在线搭建平台，负责组件化能力开发, 支撑百万级别落地页流量转化
- 开发 feflow 脚手架插件，联动敏捷开发平台和代码仓库，规范需求处理，防范不合规操作发生概率，并降低手工操作负担

### <a href='http://team.ncuos.com/'>南昌大学家园工作室</a> <i>主管</i>

校园互联网工作室 · 研发 + 设计 + 团队主管

- 负责制定技术架构选型、基建选型与建设路线，引入并推广落地 TypeScript、Git Flow、Code Review、CI/CD 自动部署体系。
- 制定新人培养方案，论证技术学习路线体系，并牵头建设团队知识库。
- 作为 owner 开发和设计工作室旗下多数产品和游戏。旗下多数产品触达校内 98% 用户，产品累计用户量过近百万。

## 项目经历

### <a href='https://incu.ncuos.com/'>南大家园</a>

一款同学校友社交 + 校园服务类 APP, 累计用户 16W+

- 基于 React Native 构建的跨端应用，减少前端 to 客户端的学习成本和重复逻辑的开发成本。
- 重构老项目，并针对性能过低的组件和场景进行优化，制定新版本过渡期向下兼容整体技术方案。
- 日常进行开发与维护，对于特定问题会及时调研并沉淀解决方案。
- 牵头项目管理和代码评审任务，重新制定完整的 Workflow，建设 CI/CD 集成与自动部署体系，使得迭代和开发速度大大提升。
- 开发 <a href='https://github.com/ncuhome/mincu'>mincu</a> 微应用 SDK，实现原生和 Web 通信功能，扩展内嵌页面调用原生 API 的能力。

### <a href='https://github.com/alibaba/ice'>飞冰 · ICE</a>

基于 React 的渐进式研发框架

- 负责设计与开发 ESM 研发模式，优化运行时下的快速调试体验
- 重构框架运行时逻辑，开发通用多主题方案和调试方案，拓展框架能力

### 腾讯看点代码大赛 (赛方) 比赛平台 

状态管理优化 / 需求开发

- 抛弃传统 Context / 重复定义数据接口的状态管理模式，调研新解决方案，提出并使用 Zustand 来解决组件间共享状态和复用异步事件问题。
- 设计并封装 hooks 实现代码包上传等功能，使该逻辑能够被其他组件复用。针对代码回溯系统的路由功能进一步完善。

### Let‘s Pin

多人在线联机拼图游戏·全栈开发

- 使用 Snowpack React TypeScript Zustand Socket-io 技术栈。
- 针对实时在线协同原理有一定思考，调研 OT | CRDT 前后端解决方案并有所想法。最后结合 CvRDT 针对项目场景采用「版本矩阵」方案解决冲突。
- 对 socket-io 封装了更 Reactable 的 hooks 方案，并拓展了 socket-io 的懒加载能力。
- 对项目进行性能分析，通过懒加载、Suspense 等手段，大幅减少了首屏时间，提升用户体验。
- 实现 建立房间｜组队功能｜多人在线拼图｜排行榜功能，活动实时在线人数 200+。

### 香樟祺·NCOV

校园疫情管控平台

- 使用 Taro + 云函数实现核心业务模块的前后端逻辑，至今稳定运行，保障校方在疫情期间准确了解学生健康状态。
- 使用 TypeScirpt Serverless 云函数实现后端逻辑，保证可在短期内快速开发与迭代，是该项目最初版本开发周期为一周以内的基础所在。
- 构建项目整体基座，关注目录结构和代码复用，使得开发和维护期间轻松应付学校复杂多变的需求。
- 优化云函数查询算法以保证服务的稳定性。提升数据加载的速度，使服务从 17s 的加载速度优化到 300ms 以内。


### Nowhere

校园失物招领

- 负责全栈开发该应用所有功能，为团队前端全栈化铺垫道路。
- 基于 NestJS + GraphQL 构建后台服务，通过类 Spring 的 AOP + DI 模式提高了开发和迭代效率。

## 其他

- 爱好沉淀博客和技术文章
- 经常在知乎和 Discord 等社区帮助他人解答与交流技术问题和经验
- 不断打破边界，涉及交互设计、平面设计、精细运营与产品方法论等领域
