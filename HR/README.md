# HR

人力资源运营系统专题。

本专题用于沉淀从用人需求、招聘、人效评估、人才库、面试、入职、入转调离、薪酬福利绩效到数据报告的完整 HR 运营系统设计能力。

这个专题关注的不是单个人事流程，而是把 HR 相关业务拆成一套可配置、可追踪、可复盘的运营系统资产。

---

## 专题目标

HR 专题要证明三类能力：

- 能把分散的人事动作整理成完整员工生命周期流程
- 能把招聘、入职、薪酬、绩效、人效等节点转成可管理的数据结构
- 能用案例、方法和模板支持实际业务落地，而不是只停留在制度说明

---

## 目录结构

HR
├── README.md
├── cases/
│   ├── A-hr-operating-system/
│   ├── B-employee-lifecycle/
│   ├── C-payroll-and-cost/
│   └── D-performance-and-org-effectiveness/
├── methods/
│   ├── 01-recruitment-and-demand-validity-method.md
│   ├── 02-personnel-lifecycle-method.md
│   ├── 03-performance-and-org-effectiveness-method.md
│   └── 04-payroll-and-cost-method.md
└── templates/
    ├── 01-recruitment-demand-template.md
    ├── 02-candidate-interview-template.md
    ├── 03-onboarding-checklist-template.md
    ├── 04-personnel-change-template.md
    ├── 05-payroll-check-template.md
    └── 06-performance-review-template.md

---

## 管理主线

人力资源运营不是单一流程，而是一条贯穿员工全周期的管理链路：

用人需求提出
-> 招聘需求有效性判断
-> 人效与编制评估
-> 招聘需求确认
-> 招聘发布
-> 简历收集
-> 候选人入库
-> 面试评估
-> 录用判断
   -> 不通过：进入人才库 / 暂不录用记录
   -> 通过：进入 offer 与入职流程
-> 入职准备
-> 试用期管理
-> 转正
-> 调岗 / 调薪 / 调级
-> 绩效评估
-> 薪酬福利核算
-> 离职
-> 人员数据归档
-> 人效与组织效率分析

---

## 当前案例

### 1. cases/A-hr-operating-system/

HR 运营系统总案例。

用于展示如何从公司用人需求出发，设计一套贯穿招聘、人才库、面试、入职、员工生命周期、薪酬绩效和人效分析的完整 HR 运营系统。

重点展示：

- 用人需求入口
- 招聘需求有效性判断
- 人才库设计
- 面试状态流转
- 入职衔接
- 员工生命周期管理
- 薪酬绩效数据沉淀
- 人效数据输出

### 2. cases/B-employee-lifecycle/

员工生命周期案例。

用于展示员工从入职、转正、调岗、调薪、绩效、离职到档案归档的流程标准化设计。

重点展示：

- 入职资料收集
- 试用期节点
- 转正流程
- 调岗调薪流程
- 离职交接
- 档案归档
- 数据留痕

### 3. cases/C-payroll-and-cost/

薪酬与人工成本案例。

用于展示薪酬核算、人工成本分摊、部门成本归集和薪酬复核流程。

重点展示：

- 薪酬字段设计
- 考勤与绩效数据关联
- 人工成本归集
- 部门成本分摊
- 薪酬复核
- 异常处理

### 4. cases/D-performance-and-org-effectiveness/

绩效与组织效能案例。

用于展示绩效数据、人效指标、部门效率和组织运营分析的流程设计。

重点展示：

- 绩效周期
- 指标收集
- 绩效评分
- 部门人效
- 人员结构分析
- 组织效率报告

---

## 方法文档

methods/ 用于沉淀 HR 流程设计中的判断逻辑。

当前方法包括：

- 01-recruitment-and-demand-validity-method.md：招聘需求与用人有效性判断方法
- 02-personnel-lifecycle-method.md：员工生命周期流程拆解方法
- 03-performance-and-org-effectiveness-method.md：绩效与组织效能分析方法
- 04-payroll-and-cost-method.md：薪酬与人工成本核对方法

方法文档重点回答：

遇到类似 HR 流程时，应该怎么拆？
哪些节点必须被记录？
哪些字段应该进入表单？
哪些状态需要可追踪？
哪些数据可以用于后续分析？

---

## 模板文档

templates/ 用于沉淀可复用的 HR 表单、清单和检查模板。

当前模板包括：

- 01-recruitment-demand-template.md：招聘需求模板
- 02-candidate-interview-template.md：候选人面试记录模板
- 03-onboarding-checklist-template.md：入职检查清单
- 04-personnel-change-template.md：员工异动模板
- 05-payroll-check-template.md：薪酬核对模板
- 06-performance-review-template.md：绩效复盘模板

模板文档重点回答：

下次遇到类似流程，可以直接复用什么？
需要收集哪些字段？
需要哪些检查项？
哪些信息必须留痕？

---

## 数据输出方向

HR 专题最终应能输出以下数据：

- 招聘需求数量
- 招聘需求通过率
- 候选人来源
- 面试通过率
- offer 通过率
- 入职完成率
- 试用期转正率
- 离职率
- 部门人工成本
- 人均成本
- 部门人效
- 绩效分布
- 人员结构变化

---

## 当前建设重点

当前优先补齐：

1. cases/A-hr-operating-system/
2. cases/B-employee-lifecycle/
3. cases/C-payroll-and-cost/
4. cases/D-performance-and-org-effectiveness/

然后再回头统一检查：

- methods/ 是否能支撑案例
- templates/ 是否能被案例复用
- HR/README.md 是否和根目录 README.md 保持一致

---

## 与根目录目标的关系

HR 专题是 process-assets 当前的核心建设模块之一。

它用于证明：可以把真实的人力资源管理经验，转成表单、流程、状态、权限、规则和数据报告，从而形成可展示、可复用、可扩展的流程数字化资产。
