# Milvaneth

Milvaneth 计划，取名自[乌尔达哈的密尔瓦内斯礼拜堂](https://ffxiv.gamerescape.com/wiki/Milvaneth_Sacrarium)，是中国版本的跨服物价共享平台（类似国际服的 mogboard.com）。由于国服目前没有手机 App（丝瓜：在做了在做了），Milvaneth 计划会独立研发一套新的物价获取技术，并在 App 发布时尽快支持通过 App 接口获取物价信息。

# Languages

You can view English version of README [here](https://github.com/menphnia/Milvaneth/blob/master/README.md).

If there is a content difference, the Chinese version of README shall prevail.
如存在内容差异，以中文版本的 README 为准。

# 开源政策

鉴于国服也有工作室和不良玩家，而且之前国际服出过相关的事情，Milvaneth 会选择性地开源不会被不当利用的部分：

1. 没有既有开源替代产品的“两用”组件，例如内存分析器和一些其他部分，将会限制对源代码的访问，并可能在发布二进制程序时使用保护手段。（注）

2. 统计和预测算法，如果算法本身是公开的，那么相应的代码也会被开源。

3. 不在上述两条的管辖范围内的部分，例如网络包分析器和 UI 一类，会一律开源。

注：如果在未来有开源的替代产品出现，那么对应的部分也会开源。

目前预计 Milvaneth 的源代码会发布于 Ms-PL (Microsoft Public License) 许可证下。这是一个来自微软的弱 Copyleft 许可证。

# 关于服务

Milvaneth 是一个公开且免费的公益项目。可能会在正式运营后接受捐赠。

Milvaneth 目前预计不会采用增值付费制。但，出于运行成本或者个人经济状况限制，不排除在不损害既有免费用户权益的情况下推出增值服务。

# 时间框架

七月上旬前：封闭测试与初始发行版

八月中旬前：开放测试与原始数据收集

八月中旬后：未定

正式运营时间不会晚于国服 4.57 版本发布时间。

# TODOs

下列目标是在初始发行版发布后会逐步实现的目标：

- [ ] 网页版物价浏览

- [ ] ACT 插件版本及对应 Overlay

- [ ] 使用手机 App 的 API（目前无法实现）

- [ ] 自定义物价监控和提醒

- [ ] 账户和雇员所有权登记和自定义列表

- [ ] 支持“销售招募版”和私信/聊天功能（在上一条实现后）

- [ ] “军票性价比”和“多玛重建性价比”计算器（若游戏后续版本推出其他物品交换功能，会追加相应计算器）

- [ ] 制作物品原料总价计算器和采购路线规划器

- [ ] 未完待续……