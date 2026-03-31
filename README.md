# FlyAI Travel Skills

基于 [flyai](https://github.com/alibaba-flyai/flyai-skill) 的旅行场景 skills，提供智能行程规划、周末逃跑计划和城市漫游三种旅行场景解决方案。

## Skills

### 1. trip-planner（智能行程规划师）

一句话生成完整旅行方案，整合航班、酒店、景点数据。

**使用场景**：
- "帮我规划去云南的5天行程"
- "暑假想带爸妈去北京玩"
- "去成都吃火锅，四天三晚"

**安装**：
```bash
npx skills add YunhanLi7/flyai-skills@trip-planner
```

### 2. weekend-escape（周末逃跑计划）

周五晚出发、周日晚返回的短途旅行方案，不用请假也能享受诗和远方。

**使用场景**：
- "这周末想逃离北京"
- "明天周末了，还没安排"
- "想去看海，预算1000"

**安装**：
```bash
npx skills add YunhanLi7/flyai-skills@weekend-escape
```

### 3. city-walker（城市漫游者）

发现城市隐藏角落的半日步行路线，重新爱上脚下的城市。

**使用场景**：
- "下午有空，想随便逛逛"
- "公司在国贸，午休想出去走走"
- "想带女朋友在上海压马路"

**安装**：
```bash
npx skills add YunhanLi7/flyai-skills@city-walker
```

## 前置依赖

所有 skills 都依赖 flyai CLI，请先安装：

```bash
npm i -g @fly-ai/flyai-cli
```

## 目录结构

```
flyai-skills/
├── trip-planner/
│   └── SKILL.md
├── weekend-escape/
│   └── SKILL.md
├── city-walker/
│   └── SKILL.md
└── README.md
```

## 许可证

MIT
