<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-11-26
- 运行时间：2026-11-26 02:22:41 UTC
- 运行状态：成功
- 本次总论文数：14
- 精读区：3
- 速读区：11

### 今日简报（AI）
今日扫描 14 篇机器人操作前沿论文，精读 3 篇、速读 11 篇，重点聚焦 VLA 模型如何补齐组合式操作的短板。最值得看的是两篇 9.0 分精读：一篇用 3D 技能包络让 VLA 执行、代码兜底恢复，另一篇用智能体推理把原子操作技能组合起来，思路互补。普通读者可先读这两篇的框架图，再顺着 CoT-WAM 与 CoachSI 了解训练与自改进路线。
- 详情：[/202611/26/README](/202611/26/README)

### 精读区论文标签
1. [VLAs Execute, Code Recovers: 3D Skill Envelopes Bridge the Compositional Gap in Agentic Manipulation](/202611/26/2611.32245v1-vlas-execute-code-recovers-3d-skill-envelopes-bridge-the-compositional-gap-in-agentic-manipulation)  
   标签：评分：9.0/10、query:llm-robotics
   evidence：在智能体规划器下组合冻结VLA技能并解决技能衔接问题
2. [Atomic Policy: Composing Atomic Manipulation Skills with Agentic Reasoning](/202611/26/2611.32813v1-atomic-policy-composing-atomic-manipulation-skills-with-agentic-reasoning)  
   标签：评分：9.0/10、query:llm-robotics
   evidence：VLM估计符号状态与目标，PDDL求解器规划技能并由智能体框架调用与验证
3. [RoboHarness-RL: Agentic Reinforcement Learning for VLM-Based Robot Manipulation](/202611/26/2611.32016v1-roboharness-rl-agentic-reinforcement-learning-for-vlm-based-robot-manipulation)  
   标签：评分：8.0/10、query:llm-robotics
   evidence：视觉语言模型作为高层控制器，通过工具调用完成机器人操作

### 速读区论文标签
1. [CoT-WAM: Collaborative Training of Vision-Language Models and World-Action Models via Plan Latents](/202611/26/2611.23803v2-cot-wam-collaborative-training-of-vision-language-models-and-world-action-models-via-plan-latents)  
   标签：评分：7.0/10、query:llm-robotics
   evidence：联合训练VLM与世界动作模型，融合语义规划与动作控制
2. [Lost Between Mind, Model Collaboration, and Motion: Understanding and Measuring Cross-Model Action Misalignment in Commercial Robots](/202611/26/2611.24100v1-lost-between-mind-model-collaboration-and-motion-understanding-and-measuring-cross-model-action-misalignment-in-commercial-robots)  
   标签：评分：7.0/10、query:llm-robotics
   evidence：大模型解读用户意图并协调机器人动作模型，研究语义错位
3. [CoachSI: Self-Improvement of Robot Policies with a Language Coach](/202611/26/2611.25529v1-coachsi-self-improvement-of-robot-policies-with-a-language-coach)  
   标签：评分：7.0/10、query:llm-robotics
   evidence：冻结VLM用语言指出下一步原子技能来指导策略，不直接输出动作
4. [EmbodyAgent: Post-Training Embodied VLM Agents via Distillation, SFT, and RL](/202611/26/2611.26196v1-embodyagent-post-training-embodied-vlm-agents-via-distillation-sft-and-rl)  
   标签：评分：7.0/10、query:llm-robotics
   evidence：视觉语言模型通过工具接口编写并执行控制代码充当闭环机器人控制器
5. [EmboEagle: An Efficient Agentic Embodied Framework for Long-horizon Robotic Manipulation](/202611/26/2611.31173v1-emboeagle-an-efficient-agentic-embodied-framework-for-long-horizon-robotic-manipulation)  
   标签：评分：7.0/10、query:llm-robotics
   evidence：以子任务为条件控制并结合视觉语言模型监督的智能体长程操作框架
6. [Ground, Guide, Act: Improving VLA Spatial Generalization with Multimodal Foundation Models](/202611/26/2611.31452v1-ground-guide-act-improving-vla-spatial-generalization-with-multimodal-foundation-models)  
   标签：评分：7.0/10、query:llm-robotics
   evidence：多模态基础模型负责定位与引导，VLA负责执行
7. [Reconfiguring Procedural Knowledge for Compositional Robot Skill Adaptation](/202611/26/2611.22174v1-reconfiguring-procedural-knowledge-for-compositional-robot-skill-adaptation)  
   标签：评分：6.0/10、query:llm-robotics
   evidence：依据高层任务规范重构可复用过程知识以组合技能
8. [CoBoVLA: Decoupling Language from Action with Discrete Codes for Robust and Interpretable Robot Manipulation](/202611/26/2611.22395v1-cobovla-decoupling-language-from-action-with-discrete-codes-for-robust-and-interpretable-robot-manipulation)  
   标签：评分：6.0/10、query:llm-robotics
   evidence：在VLA内解耦语言理解、规划与控制
9. [Verify2Act: Critic-Guided Latent World Models for Verifying Language-Conditioned Manipulation Plans](/202611/26/2611.25243v1-verify2act-critic-guided-latent-world-models-for-verifying-language-conditioned-manipulation-plans)  
   标签：评分：6.0/10、query:llm-robotics
   evidence：VLM提出多步操作计划并由潜世界模型验证
10. [PGX: Physically Grounded Execution for Long-Horizon Humanoid Loco-Manipulation](/202611/26/2611.26596v1-pgx-physically-grounded-execution-for-long-horizon-humanoid-loco-manipulation)  
   标签：评分：6.0/10、query:llm-robotics
   evidence：用状态机将长程任务分解为分阶段技能执行
11. [A Glimpse of Training VLMs as Foundation Models for Robotic Manipulation](/202611/26/2611.29338v1-a-glimpse-of-training-vlms-as-foundation-models-for-robotic-manipulation)  
   标签：评分：6.0/10、query:llm-robotics
   evidence：将视觉语言模型训练为操作基础模型并使用语义动作原语


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
