---
layout: default
title: 个人简历
---

## 关于我
<div class="grid">
  <div class="card">
    <h3 class="card__title"><span><i class="fa-solid fa-user-astronaut"></i> 简介</span><span class="badge">2026</span></h3>

- 长安大学 电子信息硕士在读（研究：可见光室内融合定位/视觉），本科通信工程  
- 方向：ROS / 定位融合 / SLAM / 嵌入式联调  
- 习惯工程化落地：可复现（rosbag/日志）、可观测（指标/误差曲线）、可部署（参数/脚本）

<p class="small">；投递 PDF/邮件再提供完整联系方式</p>
  </div>

  <div class="card">
    <h3 class="card__title"><span><i class="fa-solid fa-screwdriver-wrench"></i> 技能概览</span><span class="badge">Tech</span></h3>

<div class="skills">
  <div class="skill">
    <div class="skill__name">Linux / 工具链</div>
    <div class="skill__bar"><div class="skill__fill" style="width:80%"></div></div>
    <div class="skill__pct">80%</div>
  </div>
  <div class="skill">
    <div class="skill__name">ROS / Gazebo</div>
    <div class="skill__bar"><div class="skill__fill" style="width:70%"></div></div>
    <div class="skill__pct">70%</div>
  </div>
  <div class="skill">
    <div class="skill__name">算法：EKF / PSO</div>
    <div class="skill__bar"><div class="skill__fill" style="width:70%"></div></div>
    <div class="skill__pct">70%</div>
  </div>
  <div class="skill">
    <div class="skill__name">嵌入式：STM32</div>
    <div class="skill__bar"><div class="skill__fill" style="width:75%"></div></div>
    <div class="skill__pct">75%</div>
  </div>
</div>

<div class="pillrow">
  <span class="pill">C</span>
  <span class="pill">Python</span>
  <span class="pill">MATLAB</span>
  <span class="pill">SPI / I2C / UART</span>
  <span class="pill">ESP8266</span>
</div>
  </div>
</div>

---

## 教育经历
<div class="card">
  <h3 class="card__title"><span><i class="fa-solid fa-graduation-cap"></i> 长安大学</span><span class="badge">Education</span></h3>

- **硕士｜电子信息**（2025.08 - 至今）  
  研究方向：可见光室内条件下的融合定位（视觉）

- **本科｜通信工程**（2021.08 - 2025.06）  
  主修：微机原理、DSP、数电/模电、通信原理、计算机网络、FPGA 等  
  荣誉：陕西省高等数学竞赛二等奖
</div>

---

## 实习经历
<div class="card">
  <h3 class="card__title"><span><i class="fa-solid fa-microchip"></i> 嵌入式工程师（实习）｜西安软通动力</span><span class="badge">2024.07 - 2024.09</span></h3>

**项目：基于 STM32 的环境监测节点**
- 传感器采集：DHT11、MQ-2、光照等；OLED 显示；熟悉 SPI / I2C / UART 外设联调
- 无线上云：ESP8266 上传云端；APP 订阅阿里云平台展示数据
- 工程闭环：采集 → 处理 → 显示 → 上报 → 可视化，具备端到端联调与故障定位经验
</div>

---

## 项目经历
<div class="grid">
  <div class="card">
    <h3 class="card__title"><span><i class="fa-solid fa-robot"></i> EKF SLAM / 融合定位仿真验证</span><span class="badge">MATLAB + ROS/Gazebo</span></h3>

- MATLAB 仿真中实现 EKF 融合定位流程：轨迹估计、地图重建、数据关联
- 设计 8 字回环路径与噪声观测数据；搭建轨迹/误差/地标可视化，对比 EKF 与纯推算精度
- Linux + ROS 下搭建 Gazebo 场景完成算法功能验证与性能测试，形成可复现的验证流程（建议你后续沉淀成脚本/说明）

<div class="thumb">
  <!-- 你可以把图放到 assets/img/ 下，比如 assets/img/ekf.png -->
  <!-- 然后把下面的占位图路径改掉 -->
  <img src="{{ '/assets/img/ekf.png' | relative_url }}" alt="ekf result">
  <div class="caption">配图建议：误差曲线 / 轨迹对比 / Gazebo 场景截图（没有图也可以先删掉这个块）</div>
</div>

  </div>

  <div class="card">
    <h3 class="card__title"><span><i class="fa-solid fa-lightbulb"></i> 可见光 RSS 定位：PSO 优化求解</span><span class="badge">Algorithm Engineering</span></h3>

- 主导 PSO 主算法模块研发：算法架构、核心逻辑、参数调优与稳定性验证
- 改进机制：动态参数调整、子群并行更新、跨子群精英交换、早停策略，提高收敛效率与稳定性
- 完成与 LED 定位场景、室内环境参数的适配，保障工程落地可用

<div class="thumb">
  <!-- 你可以放一张收敛曲线/误差分布图 assets/img/pso.png -->
  <img src="{{ '/assets/img/pso.png' | relative_url }}" alt="pso result">
  <div class="caption">配图建议：收敛曲线 / 误差热力图 / 不同参数对比（没有图先删掉该块）</div>
</div>

  </div>
</div>

---

## 证书与其他
<div class="card">
  <h3 class="card__title"><span><i class="fa-solid fa-award"></i> 证书</span><span class="badge">Cert</span></h3>

- CSIG 会员（中国图像图形学会）
- 普通话：二级乙等
- 计算机：二级
- 英语：CET-4 / CET-6
</div>
