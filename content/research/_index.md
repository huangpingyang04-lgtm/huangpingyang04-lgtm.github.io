---
title: "科研经历"
hideMeta: true
---

<div class="section-lead">
  <p class="eyebrow">Research</p>
  <h2>围绕器件、感知与轻量智能模型的科研训练</h2>
  <p>我的科研经历主要分为两条线索：一是面向第三代半导体器件与忆阻器的材料-器件-表征链路；二是面向 DAS 多事件识别与器件约束神经网络的智能感知建模。</p>
</div>

<div class="research-card featured">
  <div class="research-head">
    <div>
      <p class="eyebrow">Project 01</p>
      <h2>后处理诱导界面 GaOxN1-x 层调控 Ag/GaN/ITO 忆阻器开关特性</h2>
      <p class="meta-line">负责人｜2025.09 - 2026.03｜独立第一作者投稿</p>
    </div>
    <span class="status-tag">第三代半导体器件 / 忆阻器</span>
  </div>

  <div class="research-visuals two-col">
    <figure>
      <img src="/images/research/memristor-structure.png" alt="Ag/GaN/ITO 忆阻器器件结构与后处理策略示意图">
      <figcaption>器件结构、导电细丝机制与未处理 / 退火 / O2 等离子体后处理策略。</figcaption>
    </figure>
    <figure>
      <img src="/images/research/memristor-mechanism.png" alt="三组 Ag/GaN/ITO 忆阻器导电细丝机理对比图">
      <figcaption>不同界面状态下，导电细丝生长与 reset 后残余细丝形态发生分化。</figcaption>
    </figure>
  </div>

  <div class="research-columns">
    <div>
      <h3>研究问题</h3>
      <p>围绕一个核心问题展开：<strong>不改变 Ag/GaN/ITO 基本堆叠，能否仅靠表面后处理实现开关模式调控？</strong>GaN 作为第三代半导体材料，兼具宽禁带、高击穿场强与工艺兼容性，但溅射 GaN 表面常伴随颗粒、缺陷与含氧物种，Ag 细丝易随机成核，导致开关波动。</p>
    </div>
    <div>
      <h3>实验设计</h3>
      <p>采用同一器件结构 Ag / 74 nm GaN / ITO，设置<strong>未处理、350℃ 空气退火 40 min、O2 等离子体 10 W 60 s</strong>三组对照。通过 I-V 循环、set/reset 参数统计、读取稳定性，以及 SEM、AFM、XRD、XPS 建立证据链。</p>
    </div>
  </div>

  <div class="result-band">
    <strong>阶段认识：</strong>后处理诱导的界面 GaOxN1-x 层会改变局域电场与 Ag 细丝动力学，使同一结构器件表现出随机型、渐变型或突变型开关特征。论文已投稿至 <em>Journal of Materials Science: Materials in Electronics</em>。
  </div>
</div>

<div class="research-card featured">
  <div class="research-head">
    <div>
      <p class="eyebrow">Project 02</p>
      <h2>基于多时频融合与器件约束轻量模型的 DAS 多事件识别研究</h2>
      <p class="meta-line">上海交通大学人工智能学院实习生 / 项目负责人｜2026.01 - 至今</p>
    </div>
    <span class="status-tag">DAS / CNN / BNN / 忆阻器约束</span>
  </div>

  <div class="research-visuals three-col">
    <figure>
      <img src="/images/research/das-stft.png" alt="DAS 信号 STFT 时频变换示意">
      <figcaption>从原始相位差 / 强度差信号到 STFT 时频图，形成可复现实验链路。</figcaption>
    </figure>
    <figure>
      <img src="/images/research/das-confusion.png" alt="DAS 事件识别混淆矩阵示意">
      <figcaption>自动导出混淆矩阵、分类报告与错分样本清单，用于误差诊断。</figcaption>
    </figure>
    <figure>
      <img src="/images/research/das-metrics.png" alt="DAS 事件识别模型指标对比表">
      <figcaption>围绕 Accuracy、Macro-F1、模型大小、推理效率等指标进行横向比较。</figcaption>
    </figure>
  </div>

  <div class="research-columns">
    <div>
      <h3>研究内容</h3>
      <p>面向分布式光纤传感 DAS 多事件识别，构建融合 <strong>STFT、CWT、包络 STFT、空间包络</strong>的多通道 CNN / BNN 框架。大样本数据集中，SmallCNN、ResNet-18、MobileNetV3-Small、ShuffleNetV2 等模型均已跑通，并围绕精度、Macro-F1、混淆矩阵、训练效率与推理效率进行比较。</p>
    </div>
    <div>
      <h3>个人工作</h3>
      <p>独立完成 .mat / .npz 数据读取、样本整理、多通道特征生成、训练测试与报告脚本自动化；负责 SmallCNN、ResNet、MobileNet、ShuffleNet 与多通道 BNN 的适配；进一步设计忆阻器 <strong>branch-aware LUT</strong>、pointwise std 扰动、重训与 Monte Carlo 稳定性评估流程。</p>
    </div>
  </div>

  <div class="result-band">
    <strong>阶段进展：</strong>在大样本数据集上，四类模型测试准确率均达到 98% 以上；当前主线从单域/统计三通道转向多域特征融合，并继续推进 BNN 与器件感知建模。论文拟投稿至 <em>Photonic Research</em>。
  </div>
</div>

<div class="research-card">
  <div class="research-head">
    <div>
      <p class="eyebrow">Project 03</p>
      <h2>第三代半导体生物芯片研制及其应用研究</h2>
      <p class="meta-line">省级大学生创新创业训练计划项目负责人｜2024.12 - 2026.03</p>
    </div>
    <span class="status-tag">GaN HEMT / 微流控芯片</span>
  </div>

  <div class="research-visuals two-col compact">
    <figure>
      <img src="/images/research/biochip-structure.png" alt="内置 HEMT 器件微流控芯片结构示意图">
      <figcaption>微流控-氮化镓异质集成生物芯片结构示意。</figcaption>
    </figure>
    <figure>
      <img src="/images/research/biochip-device.png" alt="微流控芯片实物图">
      <figcaption>微流控芯片实物与封装验证。</figcaption>
    </figure>
  </div>

  <div class="research-columns">
    <div>
      <h3>研究内容</h3>
      <p>围绕“半导体芯片怎么制作、怎么封装、怎么稳定工作”展开，设计完成<strong>微流控-氮化镓异质集成生物芯片</strong>，探索第三代半导体芯片与微流控技术的集成，推进从底层器件到系统封装的技术链路。</p>
    </div>
    <div>
      <h3>个人工作</h3>
      <p>负责 GaN HEMT 器件微纳加工与制备实验，独立执行匀胶、光刻、套刻、磁控溅射镀膜、等离子体处理、高温退火等工艺；参与 ICP 台面刻蚀、欧姆接触电极制作、CAD 版图绘制与封装验证。</p>
    </div>
  </div>

  <div class="result-band">
    <strong>阶段成果：</strong>以第一发明人公开国家发明专利一项：CN120169453A；以第一著作权人授权软件著作权两项，并支撑优秀本科生基础研究课题与科创竞赛成果。
  </div>
</div>

<div class="research-card">
  <div class="research-head">
    <div>
      <p class="eyebrow">Project 04</p>
      <h2>基于实体状态微调的时序知识图谱长效预测框架研究</h2>
      <p class="meta-line">核心成员｜2025.10 - 2026.01｜ACL 2026 接收</p>
    </div>
    <span class="status-tag">Temporal Knowledge Graph / EST</span>
  </div>

  <div class="research-visuals single">
    <figure>
      <img src="/images/research/est-analysis.png" alt="EST 超参数分析与结构编码器对比图">
      <figcaption>围绕历史长度、时间嵌入维度、结构编码器等关键超参数进行敏感性分析。</figcaption>
    </figure>
  </div>

  <div class="research-columns">
    <div>
      <h3>研究内容</h3>
      <p>提出通用框架 EST，通过双轨记忆机制解决时序图谱预测中的“情景性遗忘”问题。在多个数据集上优于对比方法，其中在噪声较大的 GDELT 数据集上较顶尖基线提升近 20%。</p>
    </div>
    <div>
      <h3>个人工作</h3>
      <p>负责论文超参数分析部分的实验验证、数理分析及数据可视化；通过控制变量比较不同超参数变化的贡献，形成可复现的 sweep 实验与结果解释。</p>
    </div>
  </div>

  <div class="result-band">
    <strong>训练收获：</strong>这段经历让我把“调参”理解为面向复杂系统的工艺窗口搜索，可迁移到膜厚、退火温度、刻蚀功率、器件尺寸等光电器件研发场景中的参数优化。
  </div>
</div>
