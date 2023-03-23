---
title: Level 2 - Operate 第二级 - 运营
description: The cloud native foundation is established and you are moving to production. 描述：云原生基础已经建立，您正在转向生产。
---

## <i class="fas fa-users"></i> People 人员

### People Overview 人员概述

Individuals are actively invested in training and skills. The outcome is that small pockets of SMEs and expertise are appearing. DevOps has started to appear with inclusion of cloud skill engineers and developer groups offering platform skills. Cloud Native efforts are also owned by members of leadership.

个人积极投入培训和技能。结果是出现了小型的SMEs和专业知识团队。DevOps已经开始出现，包括云技术工程师和开发人员团队提供平台技能。云原生的努力也由领导成员拥有。

### Organizational Change 组织变革

Organizational change is happening. You will define project teams, create agile project groups and have quick feedback/testing loops.
组织变革正在发生。您将定义项目团队，创建敏捷项目组，并拥有快速反馈/测试回路。

### Teams and Decentralization 团队和去中心化

We are starting to formalize central services and responsibilities, including the consolidation of tooling, as well as the culling or evaporation of non-cloud native tooling.
我们开始正式化中央服务和责任，包括工具的整合，以及淘汰或消除非云原生工具。

### Security 安全

Your team needs to focus on who is responsible for Kubernetes cluster security and how it will be managed. That will require the inclusion of the security team.
您的团队需要关注谁负责Kubernetes集群的安全以及如何管理它。这将需要纳入安全团队。

### Developer Agility 开发人员敏捷性

The team is comfortable with technically challenging problems and how cloud native can help. There is an organizational commitment to decentralisation and automated testing of builds, with automated deployments to some environments.
团队对技术上具有挑战性的问题以及云原生如何帮助解决这些问题感到自在。组织致力于去中心化和构建的自动化测试，自动部署到某些环境。

### Upskilling Developers 开发人员技能提升

Your wider development team is able to operate the fundamentals of Kubernetes including:
- Connecting an operator to the Kubernetes API
- Become comfortable with Kubectl commands
- Understanding how to list and view resources
- Performing basic actions (mechanical actions with limited understanding of how it works)

您更广泛的开发团队能够操作Kubernetes的基本原理，包括：

- 将操作者连接到Kubernetes API
- 熟悉Kubectl命令
- 了解如何列出和查看资源
- 执行基本操作（机械操作，对其工作原理的理解有限）


### CNCF Certifications CNCF 认证

Organizations may wish to consider the CKA and CKAD exams around level 2 and 3.
组织可能希望在 2 级和 3 级左右考虑 CKA 和 CKAD 考试。

#### Certified Kubernetes Administrator (CKA) 认证 Kubernetes 管理员 (CKA)

This program provides assurance that CKAs have the skills, knowledge, and competency to perform the responsibilities of Kubernetes administrators.
该计划确保 CKAs 具备执行 Kubernetes 管理员职责所需的技能、知识和能力。

#### Certified Kubernetes Application Developer (CKAD)  认证 Kubernetes 应用开发者 (CKAD)

This exam certifies that users can design, build, configure, and expose cloud native applications for Kubernetes.
该考试证明用户可以为 Kubernetes 设计、构建、配置和公开云原生应用程序。

## <i class="fas fa-cogs"></i> Process 流程

### Process Overview 流程概述

You’ll focus on production promotion of basic applications. This includes being well established with Git and CI. You are also instituting structured build and deployment processes that exhibit the qualities of a cloud and container native CI/CD system.

您将专注于基本应用程序的生产推广。这包括熟练掌握 Git 和 CI。您还将制定结构化的构建和部署流程，展示云和容器本地 CI/CD 系统的特点。


### CI/CD CI/CD（持续集成/持续交付）

For your application, you will institute structured build and deployment processes that exhibit the qualities of a cloud and container native CI/CD system.
对于您的应用程序，您将制定结构化的构建和部署流程，展示云和容器本地 CI/CD 系统的特点。

### Change Control  变更控制

Here you develop a fundamental understanding of the workflow from source control management (scm) to deployment and have access to merge/tag commits in scm to trigger deployments.
在这里，您将建立对从源代码管理（scm）到部署的工作流程的基本理解，并可以访问合并/标记提交以触发部署。

### Security 安全

Build security into your CI process including container scanning and configuration scanning.
将安全性纳入您的CI过程中，包括容器扫描和配置扫描。

### Audit and Logs 审计和日志

Spend time defining log aggregation.
花时间定义日志聚合

## <i class="fas fa-edit"></i> Policy 策略

### Policy Overview 策略概述
As your services approach production, you have initial policies agreed as standard and these are mostly documented.
当您的服务逐渐进入生产阶段时，您需要制定初始政策作为标准，并且大多数这些政策都需要有文件记录。

### Policy Creation 策略创建

Define initial resource metrics and start collecting data.
定义初始资源指标并开始收集数据。

### Compliance  合规性

Initial auditing, carried out manually or through simple scripts.
初始审计，可以通过手动或简单脚本进行。

## <i class="fas fa-server"></i> Technology 技术

### Technology Overview 技术概述

This marks your first step into production. You’ve worked hard to build your foundation in Level 1, and now you are moving to production. You might have started with something relatively small and simple, but this leap to production has certainly required you to address some significant steps. You’ll probably have had to incorporate monitoring and observability into your workloads. You’ll have brought key observability tooling in and started monitoring your clusters for standard metrics such as RAM, CPU etc. While you might be starting to evaluate application tracing, don’t worry about it too much if you have started to gather core metrics. Your focus here is on getting an application running in production and having enough platform resource, observability and operational capability to support it within your organization.
这标志着您迈入生产阶段的第一步。您在 Level 1 中努力构建了基础，现在正在进入生产阶段。您可能从相对较小和简单的东西开始，但是这次跃升到生产阶段肯定需要您解决一些重要的步骤。您可能已经将监视和可观察性纳入您的工作负载中。您将引入关键的可观察性工具，并开始监视集群的标准指标，例如RAM、CPU等。虽然您可能开始评估应用程序跟踪，但是如果您已经开始收集核心指标，不要过于担心。您的重点是使应用程序在生产环境中运行，并拥有足够的平台资源、可观察性和运营能力来支持它在您的组织内运行。

### Infrastructure 基础设施

Because production is your goal, you’ve built Kubernetes clusters for production with a focus on reliability and security.
由于生产是您的目标，因此您已经构建了针对可靠性和安全性的生产用 Kubernetes 集群。

### Container and Runtime Management 容器和运行时管理

You’re working in production now. You will experiment with tooling to augment the basics in production to help with security, policy management, workload misconfigurations, resource requests and limits. Key security practices for container hygiene are being incorporated.
您现在正在生产环境中工作。您将尝试使用工具来增强生产环境中的基础设施，以帮助处理安全、策略管理、工作负载错误配置、资源请求和限制等方面。正在纳入关键的安全实践以保持容器卫生。

### Application Patterns and Refactoring 应用程序模式和重构

You're in production, with your first APIs exposed. Consider developing a “microservices first” framework particularly if your first choice is always a microservices approach. If not, consider moving applications suitable for lift and shift or don't migrate the app until later.
您已经进入生产环境，首个API已经暴露出来。考虑开发“以微服务为先”的框架，尤其是如果您的第一选择总是微服务方法。如果不是，请考虑将适合升级和迁移的应用程序移动，或者等到以后再迁移该应用程序。

### Application Release and Operations 应用程序发布和运营

For your initial steps into production, you’ll be using CI or release tooling, kubectl and kustomize to potentially deploy your first smaller applications. It’s really important by now that you develop key skills in Kubernetes configuration.
在您初步进入生产环境时，您将使用CI或发布工具，kubectl和kustomize来部署您的首批较小的应用程序。现在非常重要的是，您需要在Kubernetes配置方面发展关键技能。

### Security and Policy 安全和策略

Ensure that your development and operations groups are following good practice with containers, secrets and security. Because you are in production, you will want to ensure that you have encryption as well and authentication and authorization addressed.
确保您的开发和运营团队在容器、秘密和安全方面遵循良好的实践。因为您处于生产环境中，所以您需要确保具备加密、身份验证和授权的功能。

### Testing and Issue Detection 测试和问题检测

Now that you are in production, you’ll be experimenting with tooling to help with security, policy management, workload misconfigurations, resource requests, limits and observability, in your staging or development environment.
现在您已经进入生产环境，您将在您的暂存或开发环境中尝试使用工具来帮助处理安全、策略管理、工作负载错误配置、资源请求和限制以及可观测性等方面。

## <i class="fas fa-building"></i> Business Outcomes 业务成果

Cloud native is now established and your technologists are moving to production. While the technical outcome of Level 2 is a fully functional application or group of applications migrated to cloud native tools and practices, the business outcomes are the ability to evaluate the benefits of the migrations. This is also the level that most customers/corporations get to and plateau. This is when a cloud native maturity model shows its true value.
云原生现在已经成熟，您的技术人员正在向生产环境转移。尽管第2级的技术结果是将应用程序或一组应用程序完全迁移到云原生工具和实践中，但业务结果是能够评估迁移的好处。这也是大多数客户/公司达到并停滞的级别。这时云原生成熟度模型展现出其真正的价值。

With your established KPIs from Level 1, you will measure success and communicate this to stakeholders.
通过你在Level 1建立的关键绩效指标，你将衡量成功并将其传达给利益相关者。

In the operation phase, you will be focused on moving to production. You’ll have established standards around technology, your people will be operating it and implementing policy and process. Your business outcome will be around production migration. The business leadership of your organization will want to understand what applications are being moved and why. Be able to clearly communicate the plans to your business leaders. Repeatable patterns will also emerge as teams operate in Level 2. These will be applied to your business outcomes so that benefits you see in one migrated application can be applied to another without as much as a heavy lift. These patterns will help streamline operations across your dev, sec and ops teams.
在操作阶段，你将专注于进入生产阶段。你会制定技术标准，你的团队将运作并实施策略和流程。你的业务成果将围绕生产迁移展开。你的组织业务领导层希望了解哪些应用正在移动以及为什么。能够清楚地向你的业务领导传达计划。随着团队在Level 2中的运作，可重复的模式也会出现。这些模式将应用于你的业务成果，以便在迁移另一个应用程序时，你能够从一个应用程序中看到的好处不需要太大的投入就可以得到应用。这些模式将有助于简化你的开发、安全和运营团队的运作。

Your KPIs can also include your return on investment ROI, but know that in Level 2, your ROI will be lower than when you reach Level 5. This is because you are investing a lot in acquiring tools, establishing the right team and skill set, whereas in Level 5 you are optimizing.
你的KPI还可以包括你的投资回报率ROI，但要知道在Level 2中，你的ROI将低于当你达到Level 5时。这是因为你在获得工具、建立合适的团队和技能方面投入了很多，而在Level 5中，你正在优化。
