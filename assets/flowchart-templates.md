# PBL 流程图模板

> 本文件提供PBL教学流程图的SVG代码模板，供生成各类可视化教学材料时参考。

---

## 模板一：马斯特里赫特七步法流程图

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 680 520" font-family="Microsoft YaHei, PingFang SC, sans-serif">
  <rect width="680" height="520" fill="#1a1a2e"/>
  
  <text x="340" y="35" text-anchor="middle" fill="#e0e0e0" font-size="18" font-weight="600">
    马斯特里赫特七步法 PBL 流程
  </text>
  
  <defs>
    <marker id="arrow1" markerWidth="10" markerHeight="10" refX="9" refY="3" orient="auto">
      <path d="M0,0 L0,6 L9,3 z" fill="#8a8a9a"/>
    </marker>
  </defs>
  
  <!-- Step 1 -->
  <rect x="220" y="60" width="240" height="50" rx="8" fill="#16213e" stroke="#4e9af1" stroke-width="1.5"/>
  <text x="340" y="82" text-anchor="middle" fill="#e0e0e0" font-size="14" font-weight="500">Step 1: 澄清术语</text>
  <text x="340" y="100" text-anchor="middle" fill="#a0a0b0" font-size="10">5-10 min</text>
  
  <line x1="340" y1="110" x2="340" y2="130" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow1)"/>
  
  <!-- Step 2 -->
  <rect x="220" y="130" width="240" height="50" rx="8" fill="#16213e" stroke="#4e9af1" stroke-width="1.5"/>
  <text x="340" y="152" text-anchor="middle" fill="#e0e0e0" font-size="14" font-weight="500">Step 2: 定义问题</text>
  <text x="340" y="170" text-anchor="middle" fill="#a0a0b0" font-size="10">5-10 min</text>
  
  <line x1="340" y1="180" x2="340" y2="200" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow1)"/>
  
  <!-- Step 3 -->
  <rect x="220" y="200" width="240" height="50" rx="8" fill="#16213e" stroke="#5cb85c" stroke-width="1.5"/>
  <text x="340" y="222" text-anchor="middle" fill="#e0e0e0" font-size="14" font-weight="500">Step 3: 头脑风暴</text>
  <text x="340" y="240" text-anchor="middle" fill="#a0a0b0" font-size="10">15-20 min</text>
  
  <line x1="340" y1="250" x2="340" y2="270" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow1)"/>
  
  <!-- Step 4 -->
  <rect x="220" y="270" width="240" height="50" rx="8" fill="#16213e" stroke="#5cb85c" stroke-width="1.5"/>
  <text x="340" y="292" text-anchor="middle" fill="#e0e0e0" font-size="14" font-weight="500">Step 4: 结构化整理</text>
  <text x="340" y="310" text-anchor="middle" fill="#a0a0b0" font-size="10">10-15 min</text>
  
  <line x1="340" y1="320" x2="340" y2="340" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow1)"/>
  
  <!-- Step 5 -->
  <rect x="220" y="340" width="240" height="50" rx="8" fill="#16213e" stroke="#f0ad4e" stroke-width="1.5"/>
  <text x="340" y="362" text-anchor="middle" fill="#e0e0e0" font-size="14" font-weight="500">Step 5: 制定学习目标</text>
  <text x="340" y="380" text-anchor="middle" fill="#a0a0b0" font-size="10">10-15 min</text>
  
  <line x1="340" y1="390" x2="340" y2="410" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow1)"/>
  
  <!-- Step 6 -->
  <rect x="220" y="410" width="240" height="50" rx="8" fill="#16213e" stroke="#f0ad4e" stroke-width="1.5"/>
  <text x="340" y="432" text-anchor="middle" fill="#e0e0e0" font-size="14" font-weight="500">Step 6: 自主学习</text>
  <text x="340" y="450" text-anchor="middle" fill="#a0a0b0" font-size="10">2-5 days</text>
  
  <line x1="340" y1="460" x2="340" y2="480" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow1)"/>
  
  <!-- Step 7 -->
  <rect x="220" y="480" width="240" height="50" rx="8" fill="#16213e" stroke="#9b59b6" stroke-width="1.5"/>
  <text x="340" y="502" text-anchor="middle" fill="#e0e0e0" font-size="14" font-weight="500">Step 7: 汇报与综合</text>
  <text x="340" y="520" text-anchor="middle" fill="#a0a0b0" font-size="10">60-90 min</text>
</svg>
```

---

## 模板二：三幕式案例结构图

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 680 400" font-family="Microsoft YaHei, PingFang SC, sans-serif">
  <rect width="680" height="400" fill="#1a1a2e"/>
  
  <text x="340" y="30" text-anchor="middle" fill="#e0e0e0" font-size="18" font-weight="600">
    PBL 三幕式案例结构
  </text>
  
  <defs>
    <marker id="arrow2" markerWidth="10" markerHeight="10" refX="9" refY="3" orient="auto">
      <path d="M0,0 L0,6 L9,3 z" fill="#8a8a9a"/>
    </marker>
  </defs>
  
  <!-- Act 1 -->
  <rect x="20" y="60" width="200" height="290" rx="8" fill="#16213e" stroke="#4e9af1" stroke-width="1.5"/>
  <text x="120" y="85" text-anchor="middle" fill="#4e9af1" font-size="14" font-weight="600">第一幕：首次就诊</text>
  <text x="120" y="110" text-anchor="middle" fill="#e0e0e0" font-size="11">患者信息 + 主诉</text>
  <text x="120" y="130" text-anchor="middle" fill="#e0e0e0" font-size="11">现病史 + 既往史</text>
  <text x="120" y="155" text-anchor="middle" fill="#a0a0b0" font-size="10">信息量 30-35%</text>
  <text x="120" y="180" text-anchor="middle" fill="#5cb85c" font-size="11">学习目标 3-5个</text>
  <text x="120" y="200" text-anchor="middle" fill="#5cb85c" font-size="11">Bloom L1-L3</text>
  <text x="120" y="225" text-anchor="middle" fill="#f0ad4e" font-size="11">引导问题 5-8个</text>
  <text x="120" y="250" text-anchor="middle" fill="#d9534f" font-size="11">知识锚点 3-4个</text>
  <text x="120" y="275" text-anchor="middle" fill="#a0a0b0" font-size="10">核心：激活已有知识</text>
  <text x="120" y="295" text-anchor="middle" fill="#a0a0b0" font-size="10">头脑风暴</text>
  
  <line x1="220" y1="205" x2="240" y2="205" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow2)"/>
  
  <!-- Act 2 -->
  <rect x="240" y="60" width="200" height="290" rx="8" fill="#16213e" stroke="#5cb85c" stroke-width="1.5"/>
  <text x="340" y="85" text-anchor="middle" fill="#5cb85c" font-size="14" font-weight="600">第二幕：检查与发现</text>
  <text x="340" y="110" text-anchor="middle" fill="#e0e0e0" font-size="11">体格检查 + 实验室</text>
  <text x="340" y="130" text-anchor="middle" fill="#e0e0e0" font-size="11">影像学 + 特殊检查</text>
  <text x="340" y="155" text-anchor="middle" fill="#a0a0b0" font-size="10">信息量 35-40%</text>
  <text x="340" y="180" text-anchor="middle" fill="#5cb85c" font-size="11">学习目标 3-5个</text>
  <text x="340" y="200" text-anchor="middle" fill="#5cb85c" font-size="11">Bloom L3-L5</text>
  <text x="340" y="225" text-anchor="middle" fill="#f0ad4e" font-size="11">引导问题 5-8个</text>
  <text x="340" y="250" text-anchor="middle" fill="#d9534f" font-size="11">知识锚点 4-6个</text>
  <text x="340" y="275" text-anchor="middle" fill="#a0a0b0" font-size="10">核心：鉴别诊断</text>
  <text x="340" y="295" text-anchor="middle" fill="#a0a0b0" font-size="10">机制链接</text>
  
  <line x1="440" y1="205" x2="460" y2="205" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow2)"/>
  
  <!-- Act 3 -->
  <rect x="460" y="60" width="200" height="290" rx="8" fill="#16213e" stroke="#9b59b6" stroke-width="1.5"/>
  <text x="560" y="85" text-anchor="middle" fill="#9b59b6" font-size="14" font-weight="600">第三幕：诊疗与随访</text>
  <text x="560" y="110" text-anchor="middle" fill="#e0e0e0" font-size="11">诊断 + 治疗方案</text>
  <text x="560" y="130" text-anchor="middle" fill="#e0e0e0" font-size="11">随访 + 预后评估</text>
  <text x="560" y="155" text-anchor="middle" fill="#a0a0b0" font-size="10">信息量 25-35%</text>
  <text x="560" y="180" text-anchor="middle" fill="#5cb85c" font-size="11">学习目标 3-5个</text>
  <text x="560" y="200" text-anchor="middle" fill="#5cb85c" font-size="11">Bloom L4-L6</text>
  <text x="560" y="225" text-anchor="middle" fill="#f0ad4e" font-size="11">引导问题 5-8个</text>
  <text x="560" y="250" text-anchor="middle" fill="#d9534f" font-size="11">知识锚点 5-8个</text>
  <text x="560" y="275" text-anchor="middle" fill="#a0a0b0" font-size="10">核心：综合反思</text>
  <text x="560" y="295" text-anchor="middle" fill="#a0a0b0" font-size="10">知识迁移</text>
</svg>
```

---

## 模板三：基础-临床桥接图

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 680 460" font-family="Microsoft YaHei, PingFang SC, sans-serif">
  <rect width="680" height="460" fill="#1a1a2e"/>
  
  <text x="340" y="30" text-anchor="middle" fill="#e0e0e0" font-size="18" font-weight="600">
    基础-临床桥接路径图
  </text>
  
  <defs>
    <marker id="arrow3" markerWidth="10" markerHeight="10" refX="9" refY="3" orient="auto">
      <path d="M0,0 L0,6 L9,3 z" fill="#8a8a9a"/>
    </marker>
  </defs>
  
  <!-- Layer 1: Basic Medicine -->
  <text x="340" y="60" text-anchor="middle" fill="#4e9af1" font-size="13" font-weight="600">基础医学层</text>
  <rect x="60" y="70" width="140" height="40" rx="6" fill="#16213e" stroke="#4e9af1" stroke-width="1.5"/>
  <text x="130" y="95" text-anchor="middle" fill="#e0e0e0" font-size="12">解剖结构</text>
  <rect x="270" y="70" width="140" height="40" rx="6" fill="#16213e" stroke="#4e9af1" stroke-width="1.5"/>
  <text x="340" y="95" text-anchor="middle" fill="#e0e0e0" font-size="12">生理功能</text>
  <rect x="480" y="70" width="140" height="40" rx="6" fill="#16213e" stroke="#4e9af1" stroke-width="1.5"/>
  <text x="550" y="95" text-anchor="middle" fill="#e0e0e0" font-size="12">生化代谢</text>
  
  <!-- Layer 2: Bridge -->
  <text x="340" y="140" text-anchor="middle" fill="#f0ad4e" font-size="13" font-weight="600">桥接机制层</text>
  <rect x="60" y="150" width="140" height="40" rx="6" fill="#16213e" stroke="#f0ad4e" stroke-width="1.5"/>
  <text x="130" y="175" text-anchor="middle" fill="#e0e0e0" font-size="12">结构→症状</text>
  <rect x="270" y="150" width="140" height="40" rx="6" fill="#16213e" stroke="#f0ad4e" stroke-width="1.5"/>
  <text x="340" y="175" text-anchor="middle" fill="#e0e0e0" font-size="12">功能→异常</text>
  <rect x="480" y="150" width="140" height="40" rx="6" fill="#16213e" stroke="#f0ad4e" stroke-width="1.5"/>
  <text x="550" y="175" text-anchor="middle" fill="#e0e0e0" font-size="12">代谢→指标</text>
  
  <!-- Layer 3: Clinical -->
  <text x="340" y="220" text-anchor="middle" fill="#5cb85c" font-size="13" font-weight="600">临床推理层</text>
  <rect x="60" y="230" width="140" height="40" rx="6" fill="#16213e" stroke="#5cb85c" stroke-width="1.5"/>
  <text x="130" y="255" text-anchor="middle" fill="#e0e0e0" font-size="12">症状识别</text>
  <rect x="270" y="230" width="140" height="40" rx="6" fill="#16213e" stroke="#5cb85c" stroke-width="1.5"/>
  <text x="340" y="255" text-anchor="middle" fill="#e0e0e0" font-size="12">假设生成</text>
  <rect x="480" y="230" width="140" height="40" rx="6" fill="#16213e" stroke="#5cb85c" stroke-width="1.5"/>
  <text x="550" y="255" text-anchor="middle" fill="#e0e0e0" font-size="12">检查解读</text>
  
  <!-- Layer 4: Clinical Decision -->
  <text x="340" y="300" text-anchor="middle" fill="#9b59b6" font-size="13" font-weight="600">临床决策层</text>
  <rect x="60" y="310" width="140" height="40" rx="6" fill="#16213e" stroke="#9b59b6" stroke-width="1.5"/>
  <text x="130" y="335" text-anchor="middle" fill="#e0e0e0" font-size="12">诊断确立</text>
  <rect x="270" y="310" width="140" height="40" rx="6" fill="#16213e" stroke="#9b59b6" stroke-width="1.5"/>
  <text x="340" y="335" text-anchor="middle" fill="#e0e0e0" font-size="12">治疗决策</text>
  <rect x="480" y="310" width="140" height="40" rx="6" fill="#16213e" stroke="#9b59b6" stroke-width="1.5"/>
  <text x="550" y="335" text-anchor="middle" fill="#e0e0e0" font-size="12">预后评估</text>
  
  <!-- Arrows -->
  <line x1="130" y1="110" x2="130" y2="150" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow3)"/>
  <line x1="340" y1="110" x2="340" y2="150" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow3)"/>
  <line x1="550" y1="110" x2="550" y2="150" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow3)"/>
  <line x1="130" y1="190" x2="130" y2="230" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow3)"/>
  <line x1="340" y1="190" x2="340" y2="230" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow3)"/>
  <line x1="550" y1="190" x2="550" y2="230" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow3)"/>
  <line x1="130" y1="270" x2="130" y2="310" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow3)"/>
  <line x1="340" y1="270" x2="340" y2="310" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow3)"/>
  <line x1="550" y1="270" x2="550" y2="310" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow3)"/>
  
  <!-- Legend -->
  <rect x="20" y="380" width="640" height="60" rx="6" fill="#16213e" opacity="0.8"/>
  <rect x="35" y="395" width="16" height="16" rx="3" fill="#4e9af1"/>
  <text x="60" y="408" fill="#a0a0b0" font-size="11">基础医学知识</text>
  <rect x="165" y="395" width="16" height="16" rx="3" fill="#f0ad4e"/>
  <text x="190" y="408" fill="#a0a0b0" font-size="11">桥接机制</text>
  <rect x="280" y="395" width="16" height="16" rx="3" fill="#5cb85c"/>
  <text x="305" y="408" fill="#a0a0b0" font-size="11">临床推理</text>
  <rect x="395" y="395" width="16" height="16" rx="3" fill="#9b59b6"/>
  <text x="420" y="408" fill="#a0a0b0" font-size="11">临床决策</text>
</svg>
```

---

## 模板四：PBL评估流程图

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 680 400" font-family="Microsoft YaHei, PingFang SC, sans-serif">
  <rect width="680" height="400" fill="#1a1a2e"/>
  
  <text x="340" y="30" text-anchor="middle" fill="#e0e0e0" font-size="18" font-weight="600">
    PBL 评估流程图
  </text>
  
  <defs>
    <marker id="arrow4" markerWidth="10" markerHeight="10" refX="9" refY="3" orient="auto">
      <path d="M0,0 L0,6 L9,3 z" fill="#8a8a9a"/>
    </marker>
  </defs>
  
  <!-- Student Self-assessment -->
  <rect x="30" y="70" width="180" height="60" rx="8" fill="#16213e" stroke="#4e9af1" stroke-width="1.5"/>
  <text x="120" y="95" text-anchor="middle" fill="#e0e0e0" font-size="13" font-weight="500">学生自评</text>
  <text x="120" y="115" text-anchor="middle" fill="#a0a0b0" font-size="10">7维度 × 5级评分</text>
  
  <!-- Peer assessment -->
  <rect x="250" y="70" width="180" height="60" rx="8" fill="#16213e" stroke="#5cb85c" stroke-width="1.5"/>
  <text x="340" y="95" text-anchor="middle" fill="#e0e0e0" font-size="13" font-weight="500">小组互评</text>
  <text x="340" y="115" text-anchor="middle" fill="#a0a0b0" font-size="10">5维度 × 5级评分</text>
  
  <!-- Tutor assessment -->
  <rect x="470" y="70" width="180" height="60" rx="8" fill="#16213e" stroke="#f0ad4e" stroke-width="1.5"/>
  <text x="560" y="95" text-anchor="middle" fill="#e0e0e0" font-size="13" font-weight="500">导师评价</text>
  <text x="560" y="115" text-anchor="middle" fill="#a0a0b0" font-size="10">8维度 × 5级评分</text>
  
  <!-- Arrows to synthesis -->
  <line x1="120" y1="130" x2="280" y2="180" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow4)"/>
  <line x1="340" y1="130" x2="340" y2="170" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow4)"/>
  <line x1="560" y1="130" x2="400" y2="180" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow4)"/>
  
  <!-- Synthesis -->
  <rect x="220" y="180" width="240" height="60" rx="8" fill="#16213e" stroke="#9b59b6" stroke-width="1.5"/>
  <text x="340" y="205" text-anchor="middle" fill="#e0e0e0" font-size="13" font-weight="500">综合评分</text>
  <text x="340" y="225" text-anchor="middle" fill="#a0a0b0" font-size="10">自评20% + 互评30% + 导师50%</text>
  
  <line x1="340" y1="240" x2="340" y2="270" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow4)"/>
  
  <!-- Grade -->
  <rect x="220" y="270" width="240" height="50" rx="8" fill="#16213e" stroke="#d9534f" stroke-width="1.5"/>
  <text x="340" y="292" text-anchor="middle" fill="#e0e0e0" font-size="13" font-weight="500">等级评定</text>
  <text x="340" y="310" text-anchor="middle" fill="#a0a0b0" font-size="10">A/B/C/D/F</text>
  
  <line x1="340" y1="320" x2="340" y2="345" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow4)"/>
  
  <!-- Feedback -->
  <rect x="220" y="345" width="240" height="40" rx="8" fill="#16213e" stroke="#4e9af1" stroke-width="1.5"/>
  <text x="340" y="370" text-anchor="middle" fill="#e0e0e0" font-size="12">反馈与改进 → 下一轮PBL</text>
</svg>
```

---

## 模板五：PBL教学环节流程图

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 680 460" font-family="Microsoft YaHei, PingFang SC, sans-serif">
  <rect width="680" height="460" fill="#1a1a2e"/>
  
  <text x="340" y="30" text-anchor="middle" fill="#e0e0e0" font-size="18" font-weight="600">
    PBL 教学环节流程（中国本土化模型）
  </text>
  
  <defs>
    <marker id="arrow5" markerWidth="10" markerHeight="10" refX="9" refY="3" orient="auto">
      <path d="M0,0 L0,6 L9,3 z" fill="#8a8a9a"/>
    </marker>
  </defs>
  
  <!-- Session 1 -->
  <rect x="20" y="60" width="640" height="40" rx="6" fill="#16213e" stroke="#4e9af1" stroke-width="1"/>
  <text x="340" y="85" text-anchor="middle" fill="#4e9af1" font-size="13" font-weight="600">课时1（90分钟）</text>
  
  <rect x="30" y="115" width="120" height="45" rx="6" fill="#16213e" stroke="#4e9af1" stroke-width="1.5"/>
  <text x="90" y="135" text-anchor="middle" fill="#e0e0e0" font-size="11">案例阅读</text>
  <text x="90" y="150" text-anchor="middle" fill="#a0a0b0" font-size="9">5 min</text>
  
  <rect x="170" y="115" width="120" height="45" rx="6" fill="#16213e" stroke="#4e9af1" stroke-width="1.5"/>
  <text x="230" y="135" text-anchor="middle" fill="#e0e0e0" font-size="11">术语澄清</text>
  <text x="230" y="150" text-anchor="middle" fill="#a0a0b0" font-size="9">10 min</text>
  
  <rect x="310" y="115" width="120" height="45" rx="6" fill="#16213e" stroke="#5cb85c" stroke-width="1.5"/>
  <text x="370" y="135" text-anchor="middle" fill="#e0e0e0" font-size="11">头脑风暴</text>
  <text x="370" y="150" text-anchor="middle" fill="#a0a0b0" font-size="9">20 min</text>
  
  <rect x="450" y="115" width="120" height="45" rx="6" fill="#16213e" stroke="#f0ad4e" stroke-width="1.5"/>
  <text x="510" y="135" text-anchor="middle" fill="#e0e0e0" font-size="11">学习目标</text>
  <text x="510" y="150" text-anchor="middle" fill="#a0a0b0" font-size="9">20 min</text>
  
  <line x1="150" y1="137" x2="170" y2="137" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow5)"/>
  <line x1="290" y1="137" x2="310" y2="137" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow5)"/>
  <line x1="430" y1="137" x2="450" y2="137" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow5)"/>
  
  <rect x="190" y="180" width="300" height="40" rx="6" fill="#16213e" stroke="#f0ad4e" stroke-width="1.5"/>
  <text x="340" y="205" text-anchor="middle" fill="#e0e0e0" font-size="12">自主学习任务安排 + 资源推荐（15 min）</text>
  
  <line x1="510" y1="160" x2="340" y2="180" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow5)"/>
  
  <!-- Self-study period -->
  <rect x="190" y="245" width="300" height="40" rx="6" fill="#16213e" stroke="#f0ad4e" stroke-width="1.5" stroke-dasharray="5,3"/>
  <text x="340" y="265" text-anchor="middle" fill="#f0ad4e" font-size="12">自主探究间隔期（2-5天）</text>
  <text x="340" y="280" text-anchor="middle" fill="#a0a0b0" font-size="10">文献检索 · 知识整合 · 汇报准备</text>
  
  <line x1="340" y1="220" x2="340" y2="245" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow5)"/>
  
  <!-- Session 2 -->
  <rect x="20" y="305" width="640" height="40" rx="6" fill="#16213e" stroke="#9b59b6" stroke-width="1"/>
  <text x="340" y="330" text-anchor="middle" fill="#9b59b6" font-size="13" font-weight="600">课时2（90分钟）</text>
  
  <line x1="340" y1="285" x2="340" y2="305" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow5)"/>
  
  <rect x="30" y="360" width="120" height="45" rx="6" fill="#16213e" stroke="#9b59b6" stroke-width="1.5"/>
  <text x="90" y="380" text-anchor="middle" fill="#e0e0e0" font-size="11">汇报</text>
  <text x="90" y="395" text-anchor="middle" fill="#a0a0b0" font-size="9">40 min</text>
  
  <rect x="170" y="360" width="120" height="45" rx="6" fill="#16213e" stroke="#9b59b6" stroke-width="1.5"/>
  <text x="230" y="380" text-anchor="middle" fill="#e0e0e0" font-size="11">第二幕讨论</text>
  <text x="230" y="395" text-anchor="middle" fill="#a0a0b0" font-size="9">20 min</text>
  
  <rect x="310" y="360" width="120" height="45" rx="6" fill="#16213e" stroke="#9b59b6" stroke-width="1.5"/>
  <text x="370" y="380" text-anchor="middle" fill="#e0e0e0" font-size="11">诊断治疗</text>
  <text x="370" y="395" text-anchor="middle" fill="#a0a0b0" font-size="9">15 min</text>
  
  <rect x="450" y="360" width="120" height="45" rx="6" fill="#16213e" stroke="#9b59b6" stroke-width="1.5"/>
  <text x="510" y="380" text-anchor="middle" fill="#e0e0e0" font-size="11">反思总结</text>
  <text x="510" y="395" text-anchor="middle" fill="#a0a0b0" font-size="9">15 min</text>
  
  <line x1="150" y1="382" x2="170" y2="382" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow5)"/>
  <line x1="290" y1="382" x2="310" y2="382" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow5)"/>
  <line x1="430" y1="382" x2="450" y2="382" stroke="#4a5568" stroke-width="1.5" marker-end="url(#arrow5)"/>
</svg>
```

---

## 使用说明

1. 以上SVG模板可直接嵌入Markdown或HTML中展示
2. 修改文字内容即可适配具体案例
3. 颜色方案遵循暗色主题（dark theme）
4. viewBox宽度固定680px，高度根据内容调整
5. 可根据需要增加或减少节点
6. 箭头方向和连接线可根据流程调整
