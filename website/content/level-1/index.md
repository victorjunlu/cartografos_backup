---
title: "Level 1 - Build 级别1 - 建立 "
description: >
   You have a baseline cloud native implementation in place and are in pre-production.
   您已经完成了一个基础的云原生实现，并处于预生产阶段。
---

## <i class="fas fa-users"></i> People 人员

### People Overview 人员概览

Cloud native framework is driving your business and technical goals. You and your team are new to the technology, however do have some basic technical understanding and some pre-existing qualifications. Your business leaders understand the benefits of cloud native.
云原生框架正在推动您的业务和技术目标。您和您的团队对这项技术还很新，但是具备一些基本的技术理解和一些现有的资质。您的业务领导人了解云原生的好处。

### Organizational Change 组织变革

As you transform, you will have limited organizational support and will be in a proof of concept (POC) phase or be focused on only one application.
在您进行转型时，您将有限的组织支持，可能处于概念验证（POC）阶段或仅专注于一个应用程序。

### Teams and Decentralization 团队和分权化

Teams are exploring cloud native tooling, primarily Kubernetes. However, this is not just for the sake of exploring, but rather it is with the goal of reaching production. All work is generally taking place within a formal MVP program.
团队正在探索云原生工具，主要是Kubernetes。然而，这并不仅仅是为了探索，而是为了达到生产目标。所有的工作通常都是在一个正式的MVP计划中进行。

### Security 安全

The people implementing cloud native will need to focus on security. Default security settings will be used and will work in pre-production. You’ll spend time identifying your open source security posture and conduct a security POC of the pre-production environment so that both Dev, Ops and security understands what is required in cloud native workloads.

实施云原生的人员需要专注于安全。将使用默认安全设置，并在预生产中发挥作用。您将花费时间确定开放源代码的安全立场，并对预生产环境进行安全性POC，以便开发、运维和安全人员了解云原生工作负载所需的要求。

### Developer Agility 开发者敏捷性

Your organization is committed to decentralization and will employ “teams of teams”. This is an essential requirement of your people. Across the different levels of maturity, people will be implementing tools for automated testing, metrics and feedback. 

Developers may have learned about Agile Manifesto and adopted Scrum Framework without necessarily including Operations. Developers may attempt to resolve external dependencies themselves, slowing down feedback, with incomplete features per sprint.

您的组织致力于分权化，并将雇用“团队的团队”。这是您的员工的一个重要要求。在不同的成熟度水平上，人们将实施自动化测试、指标和反馈工具。

开发人员可能已经了解敏捷宣言并采用了Scrum框架，但并未必然包括运维。开发人员可能会尝试自行解决外部依赖关系，从而减缓反馈速度，并导致每个迭代中的功能不完整。

### Upskilling Developers 提升开发人员的技能

The maturity of your people will include upskilling the development team. 

Your application team will be trained in 12 factor applications, microservice and cloud native patterns. You will also require developers who are quite comfortable with cloud native concepts and tooling such as kubectl in order to bootstrap your development team.

您的员工成熟度将包括提升开发团队的技能。

您的应用团队将接受12个因素应用程序、微服务和云原生模式的培训。您还需要拥有对云原生概念和工具（如kubectl）非常熟悉的开发人员来启动您的开发团队。

### CNCF Certifications CNCF 认证

Cloud Native Computing Foundation (CNCF) serves as the vendor-neutral home for many of the fastest-growing open source projects, including Kubernetes, Prometheus, and Envoy.

In order for you to build a sustainable ecosystems for cloud native infrastructure is it important to have your team invest in the CNCF Certifications. It is unlikely you’ll achieve certifications in level 1. 

云原生计算基金会（CNCF）是许多增长最快的开源项目（包括Kubernetes、Prometheus和Envoy）的供应商中立的中心。

为了构建云原生基础设施的可持续生态系统，您的团队投资于CNCF认证至关重要。您很可能不会在Level 1中获得认证。

## <i class="fas fa-cogs"></i> Process 流程

### Process Overview 流程概述

You will map application requirements, both functional (application features and code) and non-functional, such as performance, capacity, and availability, and define how your organization will scale. Feedback will be manual such as by Slack, email, and phone, and you’ll also remediate manually also. You will start to implement repeatability by defining your Git workflow. Platform and technology lifecycle and updates, particularly security updates, need to be applied on a regular basis as vulnerable systems pose specific risks. You will likely be applying these updates by hand on an adhoc basis, or using update systems included in distributions.

您将会映射应用程序要求，包括功能性（应用程序特征和代码）和非功能性要求，如性能、容量和可用性，并定义组织如何扩展。反馈将是手动的，例如通过Slack、电子邮件和电话，您还将手动进行纠正。您将开始通过定义Git工作流程来实现可重复性。需要定期应用平台和技术生命周期和更新，特别是安全更新，因为易受攻击的系统会带来特定的风险。您很可能会按需手动应用这些更新，或使用发行版中包含的更新系统。


### CI/CD  CI/CD（持续集成/持续交付）

Central to your cloud native transformation is the adoption of CI/CD. CI/CD helps you build, test and deploy applications based on modern software development practices. Your CI/CD process will mature over time.

If you do CI/CD, you need to transform this into your cloud native environment. That includes taking existing best practices and building upon them.

在您的云原生转型过程中，CI/CD的采用至关重要。CI/CD可以帮助您基于现代软件开发实践构建、测试和部署应用程序。随着时间的推移，您的CI/CD流程将会不断成熟。

如果您正在使用CI/CD，您需要将其转换为您的云原生环境。这包括采用现有的最佳实践并在其基础上建立。

### Change Control 变更控制

Change control will need to be implemented to control your deployments.
You have no change control process in place. Instead changes are performed based on ad-hoc requests.

需要实施变更控制以控制您的部署。

您目前没有变更控制流程，而是根据临时请求执行更改。

### Security 安全

Incorporating security tooling and practices into your cloud native environment, whether through a practice or a process, as early as possible is crucial to keeping your cloud native environment secure. We often use the term ‘shift left’ to refer to bringing a practice, whether relating to testing or security, into a process as early as possible. Security is covered in all sections of the Cloud Native Maturity Model and each section with People, Process, Policy and Technology can be combined to support the security team as they seek to mature the organization’s cloud native security.

Take action: your security journey starts here. Consider security in all aspects of implementation and make it a first class citizen.
 
将安全工具和实践尽早地纳入到您的云原生环境中，无论是通过实践还是流程，对于保持您的云原生环境的安全至关重要。我们通常使用“向左移动”这个术语，来指在流程的尽早阶段引入测试或安全等实践。安全涵盖了云原生成熟度模型的所有部分，每个部分包括人员、流程、政策和技术，都可以结合起来支持安全团队，使其在成熟组织的云原生安全方面取得进展。

采取行动：您的安全之旅从这里开始。在所有实施方面考虑安全，并使其成为第一流公民。


### Audit and Logs  审计和日志

Your process will include logging and auditing. This can be based on internal requirements or support your compliance mandates.

Manual log scraping is likely ad-hoc and you may not have a central logging point or SIEM.

你的流程将包括日志记录和审计。这可以基于内部要求或支持你的合规性要求。

手动的日志收集可能是临时的，你可能没有集中的日志记录点或安全信息和事件管理系统（SIEM）。

## <i class="fas fa-edit"></i> Policy 策略

### Policy Overview 策略概述

We recognize policy adoption is a gradient. Every organization has a different risk appetite. Use this document as a guide to how you can define and enforce policy. By level 5, you will have achieved full policy maturity, however your mileage may vary.

You will have a limited set of documented policies in place to support services you're building in the cloud.

我们意识到策略采纳是一个渐进的过程。每个组织的风险承受能力都不同。使用本文档作为指南，了解如何定义和执行策略。到达级别5，您将实现完全的策略成熟度，但实际情况可能有所不同。

您将制定有限的文件化策略以支持您在云中构建的服务。

### Policy Creation 策略创建

You will need to translate your organization’s policies and compliance requirements to your cloud native environment.

Spend time understanding your application's functional and architectural requirements.

你需要将你的组织策略和合规要求转化为云原生环境中的规则。

花时间了解你的应用程序的功能和架构要求。

### Compliance 合规性

You will need policies in place to achieve compliance especially in highly regulated industries. For compliance, there is a gradient of what you will achieve.

Spend time understanding your compliance requirements: CIS, NIST, PCI for example. Design SLOs and priorities for compliance. This will take time and may not be a pre-production requirement, but will increase as you move to production.

您需要制定策略以实现合规性，特别是在高度监管的行业。对于合规性，您将实现的内容是渐进的。

花时间了解您的合规性要求：如CIS，NIST，PCI等。为合规性设计SLO和优先级。这需要时间，可能不是预生产的要求，但随着您进入生产，其重要性会增加。

、
## <i class="fas fa-server"></i> Technology 技术

### Technology Overview 技术概述

You’ll have your initial experimentation and adoption of Kubernetes. You’ll start with relatively basic tools and technology. You’ll assess your existing toolset to see how they fit within the new landscape (what plays well with cloud native, and what doesn’t?). You’ll have limited automation, but don’t worry, it’s coming! Your focus is on getting the baseline technology implemented, and you won’t be in production yet.

您将进行 Kubernetes 的初始实验和采用。您将开始使用相对基础的工具和技术。您将评估现有的工具集，看看它们在新的环境中适用程度（哪些工具能够很好地与云原生相容，哪些不能？）。您将有限的自动化，但不用担心，它即将到来！您的重点是实现基础技术，但还没有进入生产环境。


### Infrastructure 基础设施

You are building your cloud infrastructure either on-prem or off. It will pay dividends to consider early your supporting technology such as your network, firewalls and IAM, access controls and policies (and if you need to change them). Many topics will come out of your initial experimentation with Kubernetes, so ensure you keep track of these - they are the ‘breadcrumbs’ you will follow as you move towards cloud native. This will include RBAC policies, load balancer and/or ingress configuration, cluster dashboards, privileged access (or lack thereof!) and container logging. Your aim is to move away from ‘pets’ to ‘livestock’ so you invest in declarative solutions for your Infrastructure as a Service with Infrastructure as Code (IaC) tooling. If you do not have a consolidated DevOps practice at this level, bring your future operations team in to build familiarity.

您正在构建云基础架构，无论是在本地还是在云上。尽早考虑支持技术，如网络、防火墙、身份和访问控制以及策略（以及您是否需要更改它们），将对您产生回报。在与 Kubernetes 的初始实验中，将涉及许多主题，因此请确保跟踪这些主题，它们是您朝着云原生发展的“面包屑”。这将包括 RBAC 策略、负载均衡器和/或入口配置、集群仪表板、特权访问（或缺乏访问）和容器日志记录。您的目标是从“宠物”迁移到“家畜”，因此要使用基础设施即服务的声明性解决方案，并使用基础设施即代码（IaC）工具。如果在这个层面上您没有一个统一的 DevOps 实践，请让未来的运营团队参与构建以建立熟悉性。

### Container and Runtime Management 容器和运行时管理

Initially you’ll want to focus on just building containers. One of your first steps will be to add container builds to your CI for your application. You’ll also want to adopt a container registry for your images and you’ll need to consider versioning and tagging so that you can ensure you know exactly what code is in use.

初始阶段，你需要专注于构建容器。你的第一步将是将容器构建添加到应用程序的CI中。你还需要采用容器注册表来存储你的镜像，并需要考虑版本控制和标记，以确保你知道正在使用的代码的准确信息。

### Application Patterns and Refactoring  应用程序模式和重构

Start with a canonical microservice application if you can and confirm that it runs and that people are familiar with it. Attempt to start with a microservice application on your cloud native journey if you can. You can try an existing or monolithic application if this makes sense, as this will flush out tooling and dependencies you'll have for your journey to cloud native, such as kubectl, network connectivity and other topics.

Your business needs to review microservice patterns and architecture and look to understand the specifics for your applications. Non-functional requirements such as latency, resilience, scaling and third party tooling should definitely be considered. If you're transforming a monolith, this may impose significant redesign on the application as existing needs may not have the technical resources available. Consider your state management, as refactoring a monolith may require effort here. Try to ensure that the knowledge stays with the code, so make sure an existing developer familiar with the code participates in its migration to the cloud. Minimize divergence between cloud and your existing estate. This exercise will ensure all understand that it's a commitment to move to cloud native.

如果可能的话，可以从一个典型的微服务应用程序开始，并确认其运行正常且人们熟悉它。如果可能，尝试从微服务应用程序开始您的云原生之旅。如果有意义，可以尝试使用现有的单块应用程序，因为这将揭示您在云原生之旅中所需的工具和依赖项，例如 kubectl、网络连接和其他主题。

您的业务需要审查微服务模式和架构，并尝试了解应用程序的具体情况。一定要考虑诸如延迟、可靠性、扩展性和第三方工具等非功能性要求。如果要转换单块应用程序，则可能需要对应用程序进行重大的重新设计，因为现有的需求可能没有可用的技术资源。考虑您的状态管理，因为重构单块应用程序可能需要在此方面投入努力。请确保知识保留在代码中，因此确保熟悉代码的现有开发人员参与其迁移到云的过程。尽量减少云和现有资产之间的差异。此练习将确保所有人都明白这是一项承诺，要迁移到云原生。

### Application Release and Operations 应用发布和运营

Managing a cluster with Infrastructure as Code (IaC) is different to managing application release and deployment, however many of the same techniques and tools will be common to both.
When starting with Kubernetes, it is important that you start out with as much hands-on experience as possible. Initially you’ll be doing ad-hoc deployments with kubectl and kustomize.

使用基础设施即代码（IaC）来管理集群与管理应用程序的发布和部署是不同的，但许多相同的技术和工具将适用于两者。

在开始使用Kubernetes时，重要的是尽可能获得更多的实践经验。最初，您将使用kubectl和kustomize进行临时部署。

### Security and Policy  安全和策略

Start building your secured CI-CD pipeline if you don’t have one already and don’t forget that what you are doing today with VMs will end up quite different in the future
如果您还没有建立安全的CI-CD管道，请开始建立，并且不要忘记，您今天在虚拟机上进行的操作在未来会有很大的不同。.

### Testing and Issue Detection 测试和问题检测

When just starting out, much of your testing will be conducted manually on your business application that you’ve identified as your initial production candidate. With Kubernetes you’ll be focussing on your general network connectivity, and ensuring you’re able to deploy your applications. You will have smoke tests, and UAT testing.

刚开始时，您的大部分测试将在您已确定为初始生产候选的业务应用程序上手动进行。使用Kubernetes，您将专注于您的一般网络连接性，并确保您能够部署您的应用程序。您将进行冒烟测试和用户验收测试。

## <i class="fas fa-building"></i> Business Outcomes  业务成果

Level 1 of the Cloud Native Maturity Model is where your team has a baseline implementation in place and you are in pre-production. Here you will have completed a successful POC. Based on the POC, you should have initial findings on how cloud native will help improve your app. In a dev environment, you could, for example, have seen that:
- An app is using less resources (cost savings / more efficient use)
- A new feature shipped faster (faster time to market and thus increased revenue)
- There was no downtime (improved reliability for customers)
- Improved business continuity thanks to resilient cloud architectures

云原生成熟度模型的第一级是您的团队已经有了基本实现，并处于预生产阶段。在这里，您将完成一个成功的POC。基于POC，您应该对云原生如何帮助改进您的应用程序有初步的发现。在开发环境中，例如，您可能已经看到：

- 应用程序使用的资源更少（成本节约/更高效的使用）
- 新功能更快地发布（更快的上市时间，从而增加收入）
- 没有停机时间（改善客户的可靠性）
- 由于弹性云架构而改善了业务连续性

These are just examples, they are not a guarantee based on your environment as results may vary.

In this phase, you will determine how you’ll measure (your initial KPIs) the success of your cloud native journey; and just as important, how you will demonstrate it to stakeholders. This is a major outcome of Level 1 as the entire success of the journey should be mapped to this measurement. Remember it won't be immediate on day 1. Some quantitative and qualitative example KPIs may include:
- Reduced spend on app infrastructure by 25% by optimizing for cost
- Dev cost lowered by 10%
- Reduced team focus on app infrastructure by 15% by automating as much as possible
- Increased security for the application by automating CVE identification in containers
- Improve compliance as you can restrict and track access to the application; demonstrate compliance with SOC 2
- Accelerated development life cycles as you implement CI/CD pipelines shipping 10% more features per quarter
- Migrate plan - this will vary depending on your organization, but you should have a migration plan in place. Whether that’s to migrate one application first, or several, you should have this established.
- Improved customer experience measured by increased performance scores
- Elimination of information silos: departments no longer isolated; unique, integrated ecosystem in place.
- Alignment of business and IT goals: everyone is involved and aware, so that resources are better addressed to meet those goals efficiently.
- Increased internal communication: cross-pollination offers new perspectives with shared knowledge.

In this phase, it’s important that the business outcomes are examined and explained to business stakeholders. It should be a discussion with engineering leadership, the application owner (finance, marketing, etc), the CEO, and even the board. Without these discussions and alignment, maturing to the next phases will come with little appreciation and possibly even skepticism.
