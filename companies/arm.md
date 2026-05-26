# Arm (剑桥) 实习情报

> Arm Holdings (软银控股,2023 NASDAQ IPO) 是全球 IP 半导体核心,几乎所有 ARM 架构 SoC 的根源都在剑桥 Fulbourn Road 总部。Arm 是英国"硬科技"实习的旗舰品牌,**placement 文化极成熟**,有完整 3 / 6 / 12 个月 + 两年 Part-time Undergraduate Programme,Chinese / Indian 学生历史招聘量大。

## 1. 公司速览

| 项目 | 内容 |
|---|---|
| 总部 | 剑桥 Cambridge UK (Peterhouse Technology Park / Fulbourn Road) |
| 其他 UK 据点 | Manchester、Sheffield、Belfast、Warwick |
| 主营业务 | CPU IP (Cortex)、GPU IP (Mali)、NPU、AI ML、Server Chips (Neoverse) |
| 技术栈 | C / C++ / SystemVerilog / Python / Assembly,Linux kernel,LLVM/GCC |
| 实习时长 | **3 / 6 / 12 个月 placement** + 两年 Part-time Undergraduate Programme |
| 申请窗口 | 秋季 **9-10 月开放**,Rolling,12 月-1 月趋势上招满 |
| 起薪 | 实习: £22-26k (基础) 到 £34k+ (Master / 12 month) |

## 2. 实习岗位与方向

Arm 招聘按 **Engineering Function** 划分,每个 function 都有 Internship + Placement 双入口:

| 岗位类别 | 团队 / 方向 | 技术栈 |
|---|---|---|
| **Software Engineering Intern** | Compilers (LLVM/GCC)、OS Kernel、Tools (Mali Graphics)、Productivity Eng | C++、Python、Linux |
| **Hardware / Silicon Intern** | CPU (Cortex)、GPU (Mali)、SoC Integration、Physical Design | SystemVerilog、VHDL、TCL,Synopsys/Cadence EDA |
| **Machine Learning Intern** | ML Engineering、NPU IP、Compiler Optimization for ML | Python、PyTorch、TVM、MLIR |
| **Architecture Intern** | Architecture Technology Group、Performance Modeling | C++、Performance simulators |
| **Research & Education Placement** | Arm Research (Cambridge / Manchester) | 研究方向多样 |

## 3. 申请要求与签证

- **学历**: STEM 学位在读,本科 / 硕士均可;计算机 / EE / 物理背景
- **签证关键**:
  - Arm UK 是 Skilled Worker 持牌
  - **多数 placement 接受国际学生 (Student Visa 工作权)** — 历史上对 Chinese / Indian 学生开放程度极高
  - 12 个月 placement 必须能在 UK 学习 / 居留期间合法工作 (Tier 4 / Student Visa)
  - 非 UK 学生若需自带 sponsor,部分岗位可走 GAE / T5 但难度高
- **薪资 (Glassdoor / Indeed)**:
  - SWE Intern: 平均 ~£25,566 / 年 pro-rated
  - 25-75 percentile: £19.3k - £34.9k
  - 部分 Master / 12 month placement 可上 £30k+

## 4. 面试流程

```
1. Online Application + CV + Cover Letter
2. Online Assessment (HireVue 录像 + 性格 / 逻辑测试)
3. 技术 / 招聘官 chat (30-45 min)
4. Technical interview (1-2 轮 panel)
   - SWE: C / C++ 题、内存管理、Linker、Linux 系统编程
   - Silicon: Verilog、流水线 hazard、CDC、setup/hold
   - ML: 框架细节 (PyTorch internals)、模型量化、kernel fusion
5. Manager + Behavioral 终轮
```

通常 **3-5 周** 完成,Rolling 评估,先到先评。

## 5. 面经摘录

| 时间 | 岗位/城市 | 流程概述 | 题目/题型 | 结果 | 来源 |
|---|---|---|---|---|---|
| 2024 | Arm SDE Intern / Cambridge | OA + 2 技术轮 | C++ 内存模型、智能指针、tree DFS | / | 一亩三分地 |
| 2023 | Arm Intern Digital Interview | HireVue + 技术 | 录像 + 性格 + 简历深问 | / | 一亩三分地 |
| 2023-2024 | ARM-Graduate Design Engineer | 技术 panel | RTL / Verilog / 时序分析 | Offer | 一亩三分地 |
| 2023 | Compiler SE Cambridge/Manchester | 多轮 panel | LLVM IR、loop optimization | Offer (vs Amazon SDE) | 一亩三分地 instant |
| 2023 | Hardware Intern / Cambridge | OA + panel | CDC、metastability、Verilog 综合 | / | Bright Network |

> 中文社区 (一亩三分地) Arm Cambridge 面经丰富,印度社区 PrepInsta 也有大量 Hardware Intern 面经。

## 6. 文化与口碑

- **正向**:
  - **极佳的 mentor 制**: 95% 实习生说技能提升明显
  - 工程深度强 — 接触真实的 silicon production 流程
  - WLB 一流: 9-5 节奏、上下班时间灵活、剑桥城市适合学习
  - 转正率高 — 大量 Intern → Graduate Programme 直通
  - 国际学生友好度业内顶尖
- **挑战**:
  - 升职慢 — Big Tech 节奏对比下职业上升慢
  - 薪资天花板低于 FAANG
  - 部分团队遗留 C++03 / Perl 老代码

## 7. 重点准备清单

### Software / Compiler / Tools 方向
1. **C / C++ 深入**: 指针、内存对齐、Smart Pointer、RAII、Rule of Five
2. **OS / Linux 系统编程**: fork/exec、signal、mmap、syscall
3. **DSA**: LC Easy-Medium,树 / 图遍历高频
4. **Compiler 基础 (相关岗位)**: LLVM IR、SSA、寄存器分配
5. **架构知识**: ARM ISA 基础、流水线、cache、内存层次

### Silicon / Hardware 方向
1. **Verilog / SystemVerilog**: 时钟域、阻塞 / 非阻塞、CDC、metastability
2. **数字逻辑**: setup/hold、状态机、PLL
3. **EDA 工具**: Synopsys (DC、PrimeTime)、Cadence Innovus 基础概念

### ML 方向
1. **PyTorch internals**: autograd、CUDA kernel、custom op
2. **量化 / 剪枝**: INT8 quantization、QAT vs PTQ
3. **Compiler for ML**: TVM、MLIR、Triton

## 8. 总结评级

| 维度 | 评级 | 备注 |
|---|---|---|
| 信息丰富度 | 高 | 中英印社区面经均充足,placement 文化成熟 |
| 申请门槛 | 中 | 技术 bar 适中 (非 FAANG 难度) |
| Offer 转化预期 | 中-高 | International student 友好,招聘量大 |
| 推荐指数 | 强烈推荐 | UK 硬科技实习首选,国际学生最佳入口 |

> **建议**: Arm 是国际学生在英国"性价比最高"的 placement 入口之一。9-10 月一开放就立刻提交;CV 简洁突出 C++ / 硬件 / 系统编程经历;面试主考真正硬技能而非套路。

## 信息来源

- [Arm Internships Hub](https://careers.arm.com/internships)
- [Arm Early Careers](https://careers.arm.com/early-careers)
- [Arm UK Graduate & Intern Roles](https://careers.arm.com/arm-united-kingdom)
- [Arm SWE Internship Posting](https://careers.arm.com/job/cambridge/software-engineering-intern/33099/86948783744)
- [Arm Hardware Internship Posting](https://careers.arm.com/job/cambridge/hardware-engineering-intern/33099/86948783712)
- [Arm Research Placement 2025](https://www.brightnetwork.co.uk/graduate-jobs/arm/research-and-education-placement-cambridge-2025)
- [Arm Cambridge Intern Salaries Glassdoor](https://www.glassdoor.com/Intern-Salary/Arm-Cambridge-Internship-Salary-EI_IE7834.0,3_IL.4,13_IM1028.htm)
- [一亩三分地 Arm SDE Intern](https://www.1point3acres.com/bbs/thread-1026982-1-1.html)
- [一亩三分地 Arm Digital Interview](https://www.1point3acres.com/bbs/thread-930627-1-1.html)
- [一亩三分地 Arm Compiler SE](https://instant.1point3acres.com/thread/693667)
- [Semiconductor Jobs UK Placement Guide](https://semiconductorjobs.co.uk/industry-insights/semiconductor-intern-and-placement-schemes-in-the-uk-2025-26-your-ultimate-guide)
