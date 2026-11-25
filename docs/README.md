<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-10-27 ~ 2026-11-25
- 运行时间：2026-11-25 06:05:02 UTC
- 运行状态：成功
- 本次总论文数：17
- 精读区：6
- 速读区：11

### 今日简报（AI）
本期共处理 17 篇论文，其中精读 6 篇、速读 11 篇，重点集中在具身指令跟随与 LLM-VLA 智能体自我进化两个方向。

最值得关注的是两篇 9.0 分精读：AtomTree 用分层框架处理状态感知的具身指令跟随，ESI 提出面向 LLM-VLA 的自我改进飞轮；速读中 RoboCoEvo 的智能体-策略协同进化（8.0）也值得延伸。

建议普通读者先读这两篇 9.0 分文章，再通过 RoboCoEvo 和 Reasoning on Call 快速了解长程机器人操作与能力扩展的实现路径。
- 详情：[/20261027-20261125/README](/20261027-20261125/README)

### 精读区论文标签
1. [AtomTree: A Hierarchical Framework for State-Aware Embodied Instruction Following with LLMs](/20261027-20261125/2610.38744v1-atomtree-a-hierarchical-framework-for-state-aware-embodied-instruction-following-with-llms)  
   标签：评分：9.0/10、query:llm-robotics
   evidence：大模型分层状态感知任务规划，分解子目标与动作
2. [ESI: An Embodied Self-Improvement Flywheel for LLM-VLA Agents](/20261027-20261125/2611.18176v2-esi-an-embodied-self-improvement-flywheel-for-llm-vla-agents)  
   标签：评分：9.0/10、query:llm-robotics
   evidence：LLM规划子任务并调用VLA技能接口执行
3. [Body and Soul: Decoupling Robotic Brain and Policy with RoboHarness-Zero](/20261027-20261125/2611.30550v1-body-and-soul-decoupling-robotic-brain-and-policy-with-roboharness-zero)  
   标签：评分：9.0/10、query:llm-robotics
   evidence：VLM外层框架包裹冻结VLA以串联多项技能
4. [LLM-Guided Compositional Continual Learning for Robot Manipulation with Gated Low-Rank Experts](/20261027-20261125/2611.30667v1-llm-guided-compositional-continual-learning-for-robot-manipulation-with-gated-low-rank-experts)  
   标签：评分：9.0/10、query:llm-robotics
   evidence：冻结的本地大模型将指令分解为子任务并路由到技能专家
5. [Just-in-Time Skill Retrieval via Long-Horizon State Tracking](/20261027-20261125/2611.01701v1-just-in-time-skill-retrieval-via-long-horizon-state-tracking)  
   标签：评分：8.0/10、query:llm-robotics
   evidence：大模型智能体在执行过程中动态从技能库检索技能
6. [Think with Skills: Pseudocode Planning Before Execution for Advanced Reasoners](/20261027-20261125/2611.02830v1-think-with-skills-pseudocode-planning-before-execution-for-advanced-reasoners)  
   标签：评分：8.0/10、query:llm-robotics
   evidence：训练推理模型将技能描述转为伪代码计划并安排技能顺序

### 速读区论文标签
1. [RoboCoEvo: Expanding Robot Capabilities through Agent-Policy Co-Evolution](/20261027-20261125/2611.19081v1-robocoevo-expanding-robot-capabilities-through-agent-policy-co-evolution)  
   标签：评分：8.0/10、query:llm-robotics
   evidence：基于MLLM的智能体与机器人基础模型协同进化以扩展机器人能力
2. [Reasoning on Call: Efficient Agentic Robot Control for Long-Horizon Robot Manipulation](/20261027-20261125/2611.26341v1-reasoning-on-call-efficient-agentic-robot-control-for-long-horizon-robot-manipulation)  
   标签：评分：8.0/10、query:llm-robotics
   evidence：高层推理智能体监控子任务进展并协调低层策略完成长时程执行
3. [RoboAuto: Autonomous Robot Program Search through Multi-Level Physical Understanding](/20261027-20261125/2610.36533v1-roboauto-autonomous-robot-program-search-through-multi-level-physical-understanding)  
   标签：评分：7.0/10、query:llm-robotics
   evidence：大模型智能体在多层级物理理解下搜索模块化机器人程序
4. [Learning from Physical Experience:Context-Space Adaptation for Robotic Manipulation](/20261027-20261125/2610.41320v1-learning-from-physical-experiencecontext-space-adaptation-for-robotic-manipulation)  
   标签：评分：7.0/10、query:llm-robotics
   evidence：通用推理大模型作为操作策略并承担任务级规划
5. [META-Robot: Self-Cognition and Capability Scaling in Agentic Robots](/20261027-20261125/2610.41868v2-meta-robot-self-cognition-and-capability-scaling-in-agentic-robots)  
   标签：评分：7.0/10、query:llm-robotics
   evidence：大模型智能体生成机器人控制程序并扩展技能库
6. [Asynchronous Robot Policies](/20261027-20261125/2611.05155v1-asynchronous-robot-policies)  
   标签：评分：7.0/10、query:llm-robotics
   evidence：异步解耦高层VLM语义推理与低层动作生成
7. [Toward the Era of Agentic Embodied Intelligence](/20261027-20261125/2611.09124v1-toward-the-era-of-agentic-embodied-intelligence)  
   标签：评分：7.0/10、query:llm-robotics
   evidence：MetaBrain智能体提供运行时指导并调用VLA动作策略完成具身任务
8. [ReSkill: Selective Self-Improvement for Robot Manipulation](/20261027-20261125/2611.10510v1-reskill-selective-self-improvement-for-robot-manipulation)  
   标签：评分：7.0/10、query:llm-robotics
   evidence：编码智能体由指令与技能库构建任务图并修订技能
9. [MATCH: Execution-Aware Hierarchical Reinforcement Learning for Vision-and-Language Navigation in Continuous Environment](/20261027-20261125/2610.38248v1-match-execution-aware-hierarchical-reinforcement-learning-for-vision-and-language-navigation-in-continuous-environment)  
   标签：评分：6.0/10、query:llm-robotics
   evidence：语言条件规划器选择原语动作执行器的执行请求
10. [Generate-then-Rank: Learning Symbolic Goal Interpretation for Embodied Agents](/20261027-20261125/2611.07825v1-generate-then-rank-learning-symbolic-goal-interpretation-for-embodied-agents)  
   标签：评分：6.0/10、query:llm-robotics
   evidence：用大模型将指令转为可供具身规划器执行的符号目标
11. [PRISM: Primitive Routing via In-context Skill Mixing for Retentive VLA Adaptation](/20261027-20261125/2611.08917v1-prism-primitive-routing-via-in-context-skill-mixing-for-retentive-vla-adaptation)  
   标签：评分：6.0/10、query:llm-robotics
   evidence：通过基元路由实现VLA技能保持与长程技能组合


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
