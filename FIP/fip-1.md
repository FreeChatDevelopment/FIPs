---
fip: 1
标题: FIP 目的和指南
描述: 社区的治理机制和运行方式指南，包括社区开发团队的指南和执行机制。
状态: 生效
类型: 机制
作者: Jack long （jacklong@freechat.world），Mia
创建时间: 2022-10-22
修改时间: 2022-10-23
---

[中文版](#1)

[English](#2)

<h2 id="1">中文版</h2>

## Freechat Github Fips: 

https://github.com/FreeChatDevelopment/FIPs/blob/main/FIP/fip-1.md

  | 提案时间 | 链接 | 结果 |
  |:-:|:-:|:-:|
  |2022-10-23|https://snapshot.org/#/freechatdao.eth/proposal/0x12e6f4caa70509bfe82254f6b805d39b9aff92135ab68ea2ea7cddacde0e6e3f|通过|

# FIP 目的和指南

## 什么是 FIP？

FIP 代表Freechat和FreechatDAO社区改进提案。 FIP 是向社区提供信息或描述Freechat和FreechatDAO社区或其流程或环境的新功能的设计文档。 FIP 应提供该功能的简明技术规范和该功能的基本原理。 FIP 作者负责在社区内建立共识并记录不同意见，并更新FIP的状态。

## FIP 原理

我们希望 FIP 成为提出新功能、收集社区对某个问题的技术意见以及记录已进入Freechat和FreechatDAO社区的设计决策的主要机制。因为 FIP 在版本化存储库中作为文本文件进行维护，所以它们的修订历史是功能提案的历史记录。

对于Freechat和FreechatDAO社区实施者来说，FIP 是跟踪其实施进度的便捷方式。理想情况下，每个实现维护者都会列出他们已经实现的 FIP。这将为最终用户提供一种方便的方式来了解给定实现或库的当前状态。

## FIP 类型

FIP 分为三种类型：

- **功能 FIP**
  
  描述影响大多数或所有Freechat和FreechatDAO社区实现的任何更改，例如——新功能的开发、功能的更改，收费费率规则、社区治理的更改等，提议的应用程序标准/约定或任何更改或添加这会影响使用Freechat和FreechatDAO社区应用程序的互操作性。标准功能 FIP 由五部分组成——创意草案、实施文档、技术实现、功能上线、功能下线。

   - **功能FIP编号定义**
  
     为方便区分每个FIP的类型，FIP编号作以下定义：
  
     功能性FIP头部数字：5
  
     （例如51、5001、50001、500001等）

   - **功能 FIP**的相关释义：
     -  **创意草案**：任何创意草案都应先进行讨论，草案状态可以进行随意更改。讨论链接：[ “创意草案”讨论](https://github.com/FreeChatDevelopment/FIPs/discussions/categories/%E5%88%9B%E6%84%8F%E8%8D%89%E6%A1%88)，并将创意形成可实施的文档，如产品原型、开发文档等，并通过社区提案进行文档投票并通过，该提案转变为实施文档。
     -  **实施文档**：创意草案通过社区提案决策后，将整理为可实施的FIP文档，社区开发团队将进行技术实现。
     -  **功能上线**：技术实现完成后，该草案对应的FIP状态变更为功能上线状态。
     -  **功能下线**：经过社区提案决定FIP下线，社区开发团队将移除FIP功能，将FIP转变为下线状态。

- **机制 FIP**
  
  描述围绕Freechat和FreechatDAO社区的流程或提议对流程（或流程中的事件、商业模式、治理方案）进行更改。适用于Freechat和FreechatDAO社区应用以外的领域。他们可能会提出一个实施方案，但不会针对Freechat和FreechatDAO社区的代码库；它们通常需要社区共识；任何机制 FIP 也被视为商业决策 FIP和社区治理 FIP。
  
  - **机制FIP编号定义**
  
     为方便区分每个FIP的类型，FIP编号作以下定义：
  
     机制性FIP头部数字：1
  
     （例如1、12、103、1004、10005、100006等）

  - **机制 FIP**的相关释义：
    -  **机制草案**：任何机制草案都应先进行讨论，草案状态可以进行随意更改。讨论链接：[ “机制草案”讨论](https://github.com/FreeChatDevelopment/FIPs/discussions/categories/%E6%9C%BA%E5%88%B6%E8%8D%89%E6%A1%88)，机制草案通过社区提案决策后，将整理为可实施的机制FIP文档，社区开发团队将进行技术实现或者社区执行。并转变为生效状态。
    -  **生效**：经过社区提案决策并通过的机制FIP为生效状态。
    -  **无效**：经过社区提案决策并通过的需要废弃的机制FIP为无效状态。
  
  - **信息 FIP**的相关释义：
    - **信息 FIP**描述Freechat设计问题和向FreechatDAO社区提供一般指南或信息，但不提出新功能。信息 FIP 不一定代表FreechatDAO社区的共识或建议，因此用户和实施者可以自由地忽略信息 FIP 或听从他们的建议。
    
    - **信息FIP编号定义**
  
       为方便区分每个FIP的类型，FIP编号作以下定义：
  
       信息性FIP头部数字：9
  
       （例如9、92、903、9004、90005、900006等）

## FIP 状态
- **FIP**状态分为以下类型：
  -  **功能FIP**状态分为：
草案、实施、上线、下线
  -  **机制FIP**状态分为：
草案、生效、无效
  -  **信息FIP**状态分为：
无状态

## FIP 流程图
FIP 执行的流程图

![FIP Status Diagram](./../assets/fip-1/1666553432767.jpg)

## 成功的FIP应包含什么？
每个FIP应该包含以下内容：

#### 前言
包含FIP编号、标题、描述、状态、类型、作者、链接、创建时间、修改时间元素。
  -  时间格式为：（YYYY-MM-DD）
  -  作者格式为： 呢称（Email）

#### 动机或者想法、创意等描述
动机、想法、创意、社区治理对于想要创新 Freechat和FreechatDAO社区 至关重要。它应该清楚地解释为什么现方式不足以解决用户需求的问题。
#### 实施细节（如产品原型、开发文档等）
实施细节通过描述设计的原理并形成可阅读的产品原型、开发文档等，方便社区用户阅读和理解，并快速推荐该草案进行社区提案，并形成实施文档快速的进行开发和执行。
#### 版权放弃声明
版权放弃 - FIP采用以太坊的许可协议进行声明，所有 FIP 必须在公共领域放弃版权，必须链接到许可文件并使用以下措辞：
#### Copyright and related rights waived via [CC0](https://github.com/ethereum/EIPs/blob/master/LICENSE.md)

## FIP的文件格式
每个FIP文件格式必须为Markdown文件，方便进行阅读和使用。
可使用模版进行快速编辑：
#### 模版：[fip-template](https://github.com/FreeChatDevelopment/FIPs/blob/main/fip-template.md)

## 提交社区提案格式

社区治理链接：[FeechatDAO](https://snapshot.org/#/freechatdao.eth)

为统一方便社区提案的阅读和内容，向社区进行提案时应遵从以下格式：

---

fip: FIP的编号（根据FIP编号规则定义）

标题: FIP的标题

描述: FIP的简短描述

类型: FIP的类型（功能、机制、信息）

作者: 编辑和创建FIP的作者

创建时间: YYYY-MM-DD

修改时间: YYYY-MM-DD

---

## Freechat Github Fips: 

https://github.com/FreeChatDevelopment/FIPs/blob/main/FIP/fip-1.md

释义：该选项链接至Github对应的FIP。示例如：FIP-1对应的Github地址。

提案内容：复制FIP的内容。如包含图片，请将提案内的图片修改为对应的FIP图片地址。

## 版权放弃声明
Copyright and related rights waived via [CC0](https://github.com/ethereum/EIPs/blob/master/LICENSE.md)

-------------------------

<h3 id="2">English</h3>

## Freechat Github Fips: 

https://github.com/FreeChatDevelopment/FIPs/blob/main/FIP/fip-1.md


  |Proposal Time|Links|Results|
  |:-:|:-:|:-:|
  |2022-10-23|https://snapshot.org/#/freechatdao.eth/proposal/0x12e6f4caa70509bfe82254f6b805d39b9aff92135ab68ea2ea7cddacde0e6e3f|Approved|

# Purpose and Guidelines of FIP

## What is FIP?

FIP stands for Freechat and FreechatDAO community improvement proposal. A FIP is a design document providing information to the community or describing a new feature for the Freechat and FreechatDAO community or its processes or environment. The FIP should provide a concise technical specification of the feature and a rationale for the feature. The FIP author is responsible for building consensus within the community, documenting dissenting, and updating the status of the FIP.

## FIP Rationale 

We intend FIPs to be the primary mechanisms for proposing new features, collecting technical input on an issue, and documenting design decisions that have gone into the Freechat and FreechatDAO community. Because FIPs are maintained as text files in a versioned repository, their revision history is the historical record of the feature proposal.

For Freechat and FreechatDAO community implementers, FIPs are a convenient way to track the progress of their implementations. Ideally, each implementation maintainer would list the FIPs they have implemented. This will provide a convenient way for end users to know the status of a given implementation.

## FIP Types

There are three types of FIP

- **Function FIP**
  
  A Function FIP describes any change that affects most or all Freechat and FreechatDAO implementations, such as— the development of new features, changes in functionality, fee rate rules, changes in community governance, proposed application standards/conventions, or any change or addition that affects the interoperability of applications using
  Freechat and FresschatDAO. Standard function FIPs consist of five parts -an idea draft, an implementation document, a technical implementation, a feature living, and a feature withdrawn.

   - **Function FIP Numbering Definition**
  
     For the convenience of distinguishing the type of each FIP, the FIP number is defined as follows:
  
     Function FIP header number: 5
  
     (For example, 51, 5001, 50001, 500001, etc)

   - **Function FIP related definitions:**
     -  **Idea Draft**：Any idea draft should be discussed first, and the status of the draft can be changed at will. The idea draft will be discussed in the Discussion link: ["Idea draft"](https://github.com/FreeChatDevelopment/FIPs/discussions/categories/%E5%88%9B%E6%84%8F%E8%8D%89%E6%A1%88)，and the idea draft will be formed into an implementable document, such as a product prototype, development document, etc., if the idea draft is approved through community voting, it will be formed into an implementation document.
     -  **Implementation Document**：After the idea draft is approved through the community proposal voting, it will be organized into an implementable FIP document, and the community development team will conduct the technical implementation.
     -  **Living**：After the technical implementation is completed, the corresponding FIP status changes to Living.
     -  **Withdrawn**：The community decides to withdraw the proposed FIP, the community development team will remove the FIP function, and the status changes to withdrawn.

- **Mechanism FIP**
  
  A Mechanism describes the process or proposed changes to the process (or events, business model, and governance scheme in the process) surrounding Freechat and FreechatDAO community. Mechanism FIP applies to areas other than Freechat and FreechatDAO community itself. They may propose an implementation, but not to Freechat and FreechatDAO’s codebase; they often require community consensus; any mechanism FIP is also considered a business decision FIP and a community governance FIP.
  
  - **Mechanism FIP Numbering Definition**
  
     For the convenience of distinguishing the type of each FIP, the FIP number is defined as follows:
  
     Mechanism FIP header: 1
  
     (for example, 1,12,103,1004,10005,100006 etc.)

  - **Mechanism FIP Related Definition:**
    -  **Mechanism draft**：Any mechanism draft should be discussed first, and the draft status can be changed at will. The mechanism draft will be discussed in the Discussion link: ["Mechanism draft"](https://github.com/FreeChatDevelopment/FIPs/discussions/categories/%E6%9C%BA%E5%88%B6%E8%8D%89%E6%A1%88), if it gets approved, it will be turned into an implementable mechanism FIP document, and the community development team will conduct technical implementation or community implementation. The status will change to valid.
    -  **Valid**：Community-approved mechanism FIP is valid.
    -  **Invalid**：Mechanism FIT needs to be removed is invalid.
  
  - **Information FIP Related Definition:**
    - **Information FIP** describes Freechat design issues and provides general guidelines or information to the FreechatDAO community but does not propose new features. Information FIP does not necessarily represent the consensus or recommendations, so users and implementers are free to ignore the information FIP or follow its advice.
    
    - **Information FIP Numbering Definition**
  
       For the convenience of distinguishing the type of each FIP, the FIP number is defined as follows:
  
       Information FIP header: 9
  
       (for example, 9, 92,903,9004,90005,900006 etc.)

## FIP Status
- **FIP**statuses are divided into the following types:
  -  **Function FIP** statuses are divided into:
     Draft, Implementation, Living, Withdrawn
  -  **Mechanism FIP** statuses are divided into:
     Draft, Valid, Invalid
  -  **Information FIP** statuses are divided into:
     statelessness

## FIP flow chart
FIP Execution Flow Chart

![FIP Status Diagram](./../assets/fip-1/1666553432767.jpg)

## What belongs in a successful FIP?
Each FIP should contain the following parts:

#### Header Preamble
Contains FIP number, Title, Description, Status, Type, Author, link, Created time, and Modified time.
  -  The time format is: （YYYY-MM-DD）
  -  The author format is: username (Email)

#### Description of motivation or ideas etc.
Motivation, idea, creativity, and community governance are critical to innovate Freechat and the FreechatDAO community protocol. It should clearly explain why the current protocol specification is inadequate to address user needs
#### Implementation details (e.g., product prototypes, development documentation, etc.)
Implementation details describe the rationale for the design and form readable product prototypes, development documents, etc. for easy reading and understanding by the community users. The creator makes community proposals and forms implementation documents for rapid development and execution.
#### Copyright Waiver
Copyright waiver - The FIP uses Ethereum's license agreement to make the declaration. All FIPs must be in the public domain. The copyright waiver Must link to the license file and use the following wording:
#### Copyright and related rights waived via [CC0](https://github.com/ethereum/EIPs/blob/master/LICENSE.md)

## FIP File Format
Each FIP file must be in a Markdown format. There is a template to follow:
#### Template：[fip-template](https://github.com/FreeChatDevelopment/FIPs/blob/main/fip-template.md)

## Format of submitting community proposals

Community Governance Link：[FeechatDAO](https://snapshot.org/#/freechatdao.eth)

In order to unify and facilitate the reading and content of community proposals, the following formats should be followed when making proposals to the community:

---

fip: FIP number (according to FIP number rules)

Title: FIP Title

Description: a short description of FIP

Type: type of FIP (function, mechanism, information)

Author: FIP creators and editors

Created time: YYYY-MM-DD

Modified time: YYYY-MM-DD

---

## Freechat Github Fips: 

https://github.com/FreeChatDevelopment/FIPs/blob/main/FIP/fip-1.md

Comments: This option links to the corresponding FIP in Github. e.g., FIP-1 corresponds to the Github address.

Proposal content: Copy the contents of the FIP. If it contains images, please change the images in the proposal to the corresponding FIP images address

## Copyright Waiver
Copyright and related rights waived via [CC0](https://github.com/ethereum/EIPs/blob/master/LICENSE.md)