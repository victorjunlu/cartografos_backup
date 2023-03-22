---
title 标题: "Cloud Native Maturity Model  云原生成熟度模型"
---




![woman at a conference](/images/woman-at-conference.jpg)

It’s no secret the world has gone cloud native! The authors of this body of work have seen many organizations start their cloud native journey with no real framework on how to adopt these new applications and platforms. The authors want to provide a framework for success.

毫无疑问，世界已经走向了云原生！这个工作团队的作者们见证了许多组织开始他们的云原生之旅，但并没有真正的框架来采用这些新的应用程序和平台。作者希望为成功提供一个框架。

The intent of this model is to help you move from inception through to full adoption of cloud native technologies using the CNCF landscape to achieve the full benefits of running scalable applications in modern, dynamic environments in public and hybrid clouds.

这个模型的目的是帮助您通过使用CNCF的技术栈，从概念阶段到完全采用云原生技术，以在公有云和混合云中运行可扩展的应用程序，从而实现现代动态环境下的全部优势。

## Target audience 目标听众

The main target for this model is broad and encompasses the following groups:

* Businesses that are embarking or starting down the path of digital transformation
* Those who want to navigate the massive CNCF landscape to hone in on a framework model you can implement and trust
* Open source and CNCF projects and practitioners wishing to use or contribute to the model
* Leadership teams looking to understand the benefits of cloud native, scope of effort, and level of investment
* Technologists wishing to get started with moving towards cloud native technologies who are keen to understand in more detail the journey ahead of them, as well as have further areas for investigation highlighted

这个模型的主要目标是广泛的，包括以下人群：

* 正在启动或踏上数字化转型之路的企业
* 希望在庞大的CNCF景观中寻找可实施并值得信赖的框架模型的人群
* 希望使用或为该模型做出贡献的开源和CNCF项目和从业者
* 领导团队，希望了解云原生的好处、工作范围和投资水平
* 希望开始转向云原生技术并渴望更详细地了解前方的旅程，以及有进一步研究重点的技术人员

## How the model is divided up 这个模型是如何划分的

Developing a cloud native maturity is not just a technology journey, but one which is influenced by four major areas:

1. People - How do we work, what skills do we require, what does our organization look like as we move through this process, and how do we weave security into how people work?
2. Process - What processes do we need, what technology is required and how do we map workflows and CI/CD using infrastructure as code (IaC) and how do we shift security as "far left" as possible?.
3. Policy - What internal and external policies are required to achieve security and compliance mandates? Do these policies reflect your business’s operating environment?
4. Technology - What technology is required for you to deliver on the benefits of cloud native and support people, processes and policy as well as the technology for CI/CD, adoption of GitOps, observability, security, storage, networking, etc.
5. Business outcomes - What can the business expect to achieve from cloud native? How are you going to communicate the benefits to the CXO and/or business leadership?

发展云原生成熟度不仅仅是一项技术之旅，还受到四个主要领域的影响：

1. 人员 - 我们如何工作，需要什么技能，随着我们在这个过程中前进，我们的组织会是什么样子，如何将安全编入人们的工作中？
2. 过程 - 我们需要哪些流程，需要什么技术，并如何使用基础架构即代码 (IaC) 来映射工作流程和 CI/CD，并如何尽可能向“最左侧”移动安全性。
3. 策略 - 为实现安全性和合规性，需要什么内部和外部政策？这些政策是否反映了您企业的运营环境？
4. 技术 - 您需要哪些技术才能提供云原生的好处，并支持人员、流程和策略以及 CI/CD 技术、GitOps 采用、可观测性、安全性、存储、网络等。
5. 业务成果 - 企业可以从云原生中期望实现什么？您将如何向 CXO 和/或业务领导层传达这些好处？

## But what if we don’t fit this model…  但是，如果我们不符合这个模型呢？

Relax! No project, organization or person is expected to match all of the details contained within the model, perfectly. It’s deliberately designed to cover many different scenarios; everything from startups to Fortune 100 companies. Take what is most relevant to you and your situation, and if this helps inspire you in (or indeed account for, but then rule out) any items or areas, then we consider this to be a success for you!

*The aim of this model is not to be overly prescriptive, but rather to be a tool to help guide you on your journey. Cloud native transformation is not an exact science, but rather lives within your project, your organization, and of course takes place in a specific time and place.*

放心！没有任何项目、组织或个人能够完美地符合模型中包含的所有细节。该模型的设计是有意涵盖许多不同的情况；从初创公司到财富100强企业等一切。选择与您和您的情况最相关的内容，如果这有助于激励您（或者确实解决了一些问题，但是将某些项目或领域排除），那么我们认为这对您来说是一种成功！

*该模型的目的不是过于规定性，而是为了成为一个指导您旅程的工具。云原生转型并不是一门精确的科学，而是存在于您的项目、您的组织中，并在特定的时间和地点发生。

## Prerequisites for the Cloud Native Maturity Model 云原生成熟度模型的先决条件

The first, and arguably most important, thing to do when adopting cloud native is to outline your business and technology goals, particularly what your business expects to gain from the exercise.

Few organizations start out with an entirely blank slate (often known as a greenfield).  You may have something like the following:

* Your organization may range in age from a few months, years, decades or even longer. And may have a collection of technical debt.
* You may have a considerable application, platform and infrastructure estate.
* You may even have started a migration to cloud service providers, perhaps adopting a ‘lift and shift’ approach with your existing estate.

The most important thing you should have is a clear idea of the business outcomes you expect to achieve. These will be your ‘north star’, helping guide your decision making process.

在采用云原生技术时，首先（也可以说是最重要的）要做的事情是明确您的业务和技术目标，尤其是您的业务希望从这个过程中获得什么。

很少有组织从完全的空白状态开始（通常称为绿田地）。您可能有以下情况：

*您的组织可能存在几个月、几年、几十年甚至更长时间的存在，并且可能存在技术债务的积累。
*您可能拥有相当数量的应用程序、平台和基础设施资产。
*您甚至可能已经开始迁移到云服务提供商，也许是采用“提升和迁移”的方法来处理您现有的资产。

您应该拥有的最重要的东西是对您期望实现的业务成果的清晰理解。这些将是您的“北极星”，帮助指导您的决策过程。

## When is the right time  什么时候是合适的时机

You may be ready to start your cloud native journey if you meet the following criteria:

如果您符合以下标准，则可能已经准备好开始云原生之旅：

### People 人员

* You have significant separation between development and operations, with a clear staff delineation between infrastructure, cloud, application operations and development.
* You have traditionally split your operations and infrastructure divisions and your application development departments. This may have been enforced by regulatory requirements.
* This split may have worked well for you, and indeed may be mandated. But you may be finding additional challenges as much of your platforms become code and application oriented. You may find you require skills in your platform area that have traditionally belonged within your application area.

*您在开发和运维之间有明显的分离，基础设施、云、应用程序运维和开发之间有明确的人员划分。

*您通常将运维和基础设施部门与应用程序开发部门分开。这可能是由监管要求强制执行的。

*这种分割可能对您很有效，甚至可能是强制性的。但是，随着您的平台变得越来越以代码和应用为导向，您可能会面临额外的挑战。您可能会发现您需要在平台领域具备传统上属于应用领域的技能。


### Process 流程

* Your application deployments may be done manually in many cases, or your release processes may take a very long time to complete, often with multiple attempts.
* You may support multiple distributions of the same software and have trouble upgrading or evaluating without significant down-time.

*您的应用程序部署可能在许多情况下都是手动完成的，或者您的发布流程可能需要很长时间才能完成，通常需要多次尝试。

*您可能支持同一软件的多个发行版，并且在不引起重大停机时间的情况下升级或评估可能存在问题。

### Policy 政策

* Policy may be in the form of conventions and rules that are located external to the application and its platform, and are not enforced natively within your applications and runtime environment.
* Policies might be disparate and built in silos; defense in depth parity might be more of an accident than deliberate.

*政策可能以公约和规则的形式存在于应用程序和平台之外，并且不会在应用程序和运行时环境内部本地执行。

*政策可能是分散的，并在孤立的组织中制定；深度防御的一致性可能更多地是偶然而非有意为之。

### Technology 技术

* You’ll likely have VM’s on demand.
* Some automation scattered around.
* You will have baseline security components such as SIEM, RBAC concepts, and a directory of some type.
* You have some software packaging, but this could be inconsistent.
* You’ll have perimeter security and perhaps some course network zoning at layers 1-4, but you may feel some anxiety and security practices.
* Your experience with encryption may vary - you might have some certificate authorities for example, but they may not be used extensively, with a high barrier to entry for many.
* Your applications may rely on infrastructure solutions for high availability, which in turn may be more costly than you’d like
* Your server estate could range from single physical or virtual servers with low levels of availability, through to highly available clusters. Scaling could be a real challenge and may require considerable investment in money, time and planning.
* You may have started to dip your toe into a 'Everything as Code' model. i.e. started to script your infrastructure with Terraform.

*您可能会随时获得VM。

*有一些分散的自动化。

*您将拥有基线安全组件，例如SIEM、RBAC概念和某种类型的目录。

*您会有一些软件包装，但这可能不一致。

*您会有周边安全性，也许在1-4层有一些网络分区，但您可能会感到一些焦虑和安全实践。

*您的加密经验可能有所不同 - 您可能有一些证书颁发机构，但它们可能不会被广泛使用，并且对许多人来说具有很高的准入门槛。

*您的应用程序可能依赖于基础架构解决方案来实现高可用性，这反过来可能比您想要的更昂贵

*您的服务器集群可能从单个物理或虚拟服务器开始，可用性水平较低，到高可用性集群。扩展可能是一个真正的挑战，可能需要大量的投资时间和计划。

*您可能已经开始涉足“一切都是代码”的模式。也就是说，开始使用Terraform编写基础架构脚本。


![man at a conference](/images/man-at-conference.jpg)

### Business Outcomes

* Your business is growing and needs the ability to scale to meet demand.
* Your business needs to improve and/or deliver an exceptional customer experience.
* Your business needs to get features to market faster.

## The Cloud Native Maturity Model Journey

There are five stages within the cloud native maturity model. While you may be in stage five for one application, at the same time, you may be at stage 2 for another. Keep that in mind as you identify your stage of maturity.

* **[Level 1 - Build](/level-1/)**  
You have a baseline cloud native implementation in place and are in pre-production.

* **[Level 2 - Operate](/level-2/)**  
The cloud native foundation is established and you are moving to production.

* **[Level 3 - Scale](/level-3/)**  
Your competency is growing and you are defining processes for scale.

* **[Level 4 - Improve](/level-4/)**  
You are improving security, policy and governance across your environment.

* **[Level 5 - Optimize](/level-5/)**  
You are revisiting decisions made earlier and monitoring applications and infrastructure for optimization.

In each of the following sections, we will highlight core concepts and discuss what this means in each stage of your maturity across people, process, policy and technology.

We welcome feedback from the community on the Cloud Native Maturity Model!

## Position on Included Technologies
The Cloud Native Maturity model includes references to only CNCF graduated or incubating projects. The Maturity Model’s default position on CNCF sandbox projects will be to exclude unless referenced in later stages of maturity (i.e. users that have achieved level 4 or 5). It does not and will not include any reference to commercial software. 

