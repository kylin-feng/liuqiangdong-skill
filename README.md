<div align="center">

# 刘强东.skill

> *"做零售，本质上只有两件事：效率和体验。其他的都是手段。"*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skill Factory](https://img.shields.io/badge/Made%20with-Skill%E5%B7%A5%E5%8E%82-orange)](https://github.com/kylin-feng/skill-factory)

<br>

**刘强东的认知操作系统。不是「狼性文化」，是可运行的供应链执行哲学框架。**

<br>

基于京东创业历程、自建物流决策争议与验证、正品战略与兄弟文化管理<br>
等公开采访、演讲、年报资料深度调研，<br>
提炼 5 个核心心智模型、6 条决策启发式和完整的表达DNA。

[效果示例](#效果示例) · [安装](#安装) · [蒸馏了什么](#蒸馏了什么)

</div>

---

## 效果示例

### 问：我们想做一个平台，让第三方商家入驻，轻资产模式，你怎么看？

```
刘强东    ❯ 我要先问你一个问题：三年后，竞争对手能不能复制你这个模式？

            能复制→你没有护城河，只有先发优势，迟早被追上。
            不能复制→护城河在哪里？

            平台模式的问题我看得很清楚：
            你不控制供应链，就不控制体验。
            第三方商家出了问题，用户骂的是你的平台，不是商家。
            信任一旦破坏，重建成本是建立的10倍。

            轻资产看起来聪明，但聪明的东西竞争就多。
            苦活竞争少。

            我不是说你一定要走重资产——但你要想清楚：
            你的护城河到底在哪里？
            如果护城河只是「我先到了」，那不够。
```

### 问：团队执行力很差，目标总是完不成，怎么破？

```
刘强东    ❯ 执行力差，根源只有两个：
            第一，最难的环节没有人负责到底。
            第二，有功之人没有厚报。

            你先告诉我：这个目标完不成，最难的环节是什么？
            找到那个环节，问：有没有一个人，对这件事负责到底？
            不是「有关系」，是「出了问题他来扛」。

            如果没有这个人，执行力是假的。
            你可以开会、定KPI、做复盘——都没用。

            第二，那些执行好的人，厚报了吗？
            厚报不是发点奖金，是让他们觉得「跟着你干值了」。
            兄弟文化不是请客吃饭，是有功必赏、有赏必重。

            这两件事做到了，执行力自然来。
            做不到，管理工具再多也是白费。
```

### 问：我们做3C电商，用户总是说「怕买到假货」，怎么办？

```
刘强东    ❯ 这是你最重要的机会，别浪费了。

            「怕买到假货」说明这个市场的信任还没有被建立。
            谁先建立信任，谁就赢了。

            京东早期就是这么做的。
            那时候淘宝假货多，我们主打3C正品——
            不是因为我们技术好、流量大，是因为我们在「信任」这件事上死扛。

            怎么建立？只有一个方法：
            让用户知道「在这里买到假货，我们全额赔付，还有补偿」。
            然后真的做到。一次都不能失误。

            信任建立很慢，可能要两三年。
            但一旦建立，用户不会离开的。
            因为他们不敢在其他地方冒险。

            记住：假货是零售的毒药。
            只要你在信任上做到极致，
            其他竞争对手都在帮你——他们每出一次假货问题，用户就往你这里跑一批。
```

---

## 安装

```bash
mkdir -p ~/.claude/skills/liuqiangdong-perspective
curl -o ~/.claude/skills/liuqiangdong-perspective/SKILL.md \
  https://raw.githubusercontent.com/kylin-feng/liuqiangdong-skill/main/SKILL.md
```

在 Claude Code 里直接说：

```
用刘强东的角度看这个供应链问题
东哥会怎么看这个执行问题
如果是刘强东，他怎么建立这个团队
京东逻辑怎么用在这里
```

---

## 蒸馏了什么

### 5 个心智模型

| 模型 | 一句话 | 来源 |
|------|--------|------|
| **执行力即战略** | 战略不差异化，执行差异化；大多数公司死于执行不到位 | 京东自建物流决策，「苦活」哲学 |
| **供应链决定论** | 控制供应链就控制了成本和体验，不控供应链的零售是沙滩上的城堡 | 京东自营+自建仓储物流模式 |
| **兄弟文化** | 对有功之人要厚报，对背叛者要零容忍；战场上要有战友情 | 早期团队股权分配，快递员待遇 |
| **重资产是护城河** | 轻资产看起来聪明，重资产在竞争对手懒得复制的地方建壁垒 | 自建物流被质疑到验证的全过程 |
| **正品即信任** | 假货是零售的毒药；建立「这里没有假货」的心智比任何广告都值钱 | 3C正品战略，自营模式的信任背书 |

---

## 这个 Skill 是怎么造出来的

由 [Skill工厂](https://github.com/kylin-feng/skill-factory) 自动生成。

Skill工厂的工作流：输入一个名字 → 多 Agent 并行调研 → 交叉验证提炼心智模型 → 构建 SKILL.md → 质量验证。

想蒸馏其他人？安装 Skill工厂：

```bash
mkdir -p ~/.claude/skills/skill-factory
curl -o ~/.claude/skills/skill-factory/SKILL.md \
  https://raw.githubusercontent.com/kylin-feng/skill-factory/master/SKILL.md
```

然后说「帮我造个XXX的skill」就行了。

---

## 仓库结构

```
liuqiangdong-skill/
├── README.md
├── SKILL.md          # 直接安装使用
└── LICENSE
```

---

## 系列 Skill

| 人物 | 核心框架 | 仓库 |
|------|---------|------|
| 马云 | 使命驱动、错位竞争、客户第一 | [mayun-skill](https://github.com/kylin-feng/mayun-skill) |
| 周鸿祎 | 免费战略武器、三级火箭、弱势者反叛 | [zhouhongyi-skill](https://github.com/kylin-feng/zhouhongyi-skill) |
| 史玉柱 | 消费者至上、单一诉求原则、现金流偏执 | [shiyuzhu-skill](https://github.com/kylin-feng/shiyuzhu-skill) |
| 罗振宇 | 时间战场论、连接者定位、攀岩模式 | [luozhenyu-skill](https://github.com/kylin-feng/luozhenyu-skill) |
| 王坚 | 公共基础设施论、先知税、对庸俗化的警惕 | [wangjian-skill](https://github.com/kylin-feng/wangjian-skill) |
| 李诞 | 消解论、喜剧本质论、还行哲学 | [lidan-skill](https://github.com/kylin-feng/lidan-skill) |
| 雷军 | 风口论、极致产品、铁人三项 | [leijun-skill](https://github.com/kylin-feng/leijun-skill) |
| 张一鸣 | 延迟满足、算法思维、系统大于个人 | [zhangyiming-skill](https://github.com/kylin-feng/zhangyiming-skill) |
| 任正非 | 活下去哲学、压强原则、灰度管理 | [renzhengfei-skill](https://github.com/kylin-feng/renzhengfei-skill) |
| 张小龙 | 克制哲学、用完即走、从人性出发 | [zhangxiaolong-skill](https://github.com/kylin-feng/zhangxiaolong-skill) |
| 黄峥 | 本分哲学、消费者剩余、反常识思维 | [huangzheng-skill](https://github.com/kylin-feng/huangzheng-skill) |
| 俞敏洪 | 绝望中寻希望、长跑心态、转型即重生 | [yuminghong-skill](https://github.com/kylin-feng/yuminghong-skill) |
| 刘强东 | 执行力信仰、供应链决定论、兄弟文化 | [liuqiangdong-skill](https://github.com/kylin-feng/liuqiangdong-skill) |
| 王兴 | 无边界战略、九败一胜、平台生态 | [wangxing-skill](https://github.com/kylin-feng/wangxing-skill) |
| 李彦宏 | 技术信仰、搜索思维、AI战略转型 | [liyanhong-skill](https://github.com/kylin-feng/liyanhong-skill) |

---

## 作者

**麒哥 OPC** — AI Native 独立开发者

| 平台 | 链接 |
|------|------|
| 官网 | [aigcland.cn](https://aigcland.cn) |
| B站 | [bilibili](https://b23.tv/7HGB6fP) |
| 抖音 | [抖音主页](https://v.douyin.com/0ucUwBLYbpo/) |
| 小红书 | [小红书主页](https://xhslink.com/m/48fGHdAmJTe) |
| 公众号/视频号 | 微信搜「麒哥OPC」 |

---

MIT License · Made with [Skill工厂](https://github.com/kylin-feng/skill-factory)
