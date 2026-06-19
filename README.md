# RemoteAutomationControl
A mod for Oxygen Not Included
# Remote Automation Control (RAC) | 远程自动化控制系统

[English] | [简体中文]

---

便于完整自动化线路的建立，不需要小人物理占位或者占据时间，用远程方式进行部分工作的完成。如果你喜欢一个井井有条的（没有小人乱走捣乱的）家园，或许这能稍微帮助你。

Designed to facilitate the creation of completely automated logistics and production lines. It eliminates the need for duplicants to physically occupy stations or waste their precious time, completing tasks remotely. If you prefer a well-organized, orderly colony—free of duplicants wandering around causing chaos—this mod might be just what you need.

---

Core Concept | 核心概念

An balanced automation-overhaul mod for Oxygen Not Included (Spaced Out & Aquatic Planet Pack compatible).

RAC allows your Duplicants to remotely operate fabricators (like Electric Grills, Metal Refineries, and Polymer Presses) using a direct "Brain-Machine Interface" (BMI) in the background. Your duplicants do NOT need to travel to the machine, nor do they need to stand idle at a control desk. They can run remote operations in their brain while physically performing other tasks (like digging, building, or even sleeping)!

这是一个为《缺氧》中后期量身定制的、极具策略深度的远程操作自动化解决方案。

它允许你的复制人通过“脑机接口”在后台远程操作各种机器。小人不需要跑到机器面前，也不需要坐在固定的控制台前。他们可以一边在物理世界上干别的活（如挖掘、建造、睡觉），大脑在后台“多线程”操控远端的机器。

---

Mechanics & Balance | 核心机制与平衡性

*   **Background Parallel Processing | 真正的后台多线程：** Bypasses the physical chore engine. The machine's progress is simulated directly as long as it has electricity, raw materials, and an assigned operator.
*   **Athletics Penalty (Brain Load) | 大脑算力移速惩罚：** Controlling too many machines causes mental fatigue. Each active machine reduces the operator's movement speed (Athletics) progressively based on the number of currently active machines, preventing unlimited multi-tasking without consequences. (控制的活跃机器越多，小人的运动移速会呈阶梯式/指数级递增惩罚，避免一人无限多开。)
*   **Science/Learning Mitigation | 科学/研究属性减免：** High-intelligence Duplicants have wider brain bandwidth. The Science/Learning attribute dynamically cushions the movement speed penalty and boosts remote operations efficiency, giving high-science duplicants extreme late-game value. (高科学/研究属性的小人拥有更宽的脑部带宽，能显著等比例减免移动速度惩罚，并增加远程加工效率。这也给后期的高智商小人带来了极大的培养和实用价值。)
*   **XP Growth Loop | 双重经验获取：** Operating remotely periodically awards both the **Machine's Professional XP** and **Learning (Science) XP**, creating a perfect training loop. (脑机接口在后台运行时，小人会同时获得对应机器的专业经验以及学习/科学经验，形成完美的脑力训练成长闭环。)
*   **Prerequisites | 技能与科技门槛：** Operators must have the **Mechatronics Engineering** skill and the machine's required skills. (操作员必须掌握“机电工程”技能，且同时满足该机器原本的技能前置要求。)

---

 Contribution & Localisation | 欢迎加入协作！

This mod is an open-source project. Since we want to make it highly polished, we warmly welcome any contributions!
- **Bug hunters:** Submit an issue with your `Player.log` if things break!
- **Translators:** Help us translate the localizations to your native language (Russian, Korean, etc.).
- **Developers:** Feel free to open a Pull Request to optimize the C# code, add support for custom modded buildings, or improve UI!

这是一个完全开源的项目。欢迎社区的小伙伴们一起加入进来完善它：
- **Bug反馈**：如果遇到红字崩溃，请带上你的 `Player.log` 发送 Issue！
- **多语言适配**：欢迎帮我们补充翻译。
- **协同开发**：欢迎提交 PR 来优化 C# 逻辑、或者适配其他作者的机器 MOD。

Acknowledgements | 致谢

The core mechanics, game design, and numerical balance of this mod were fully designed by me. The underlying C# programming and technical implementation were completed with the assistance of AI. This is a proud product of Human-AI collaboration!

本 MOD 的核心机制、游戏平衡性设计均由我本人构思，底层的 C# 代码实现与查错则是在 AI 的辅助下共同完成的。这是一次非常棒的人机协作探索！

## ⚖️ License | 开源协议
This project is licensed under the **MIT License**. Feel free to use and distribute.
