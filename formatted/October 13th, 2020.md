
### #[RoamCN meetup](RoamCN meetup.md) Round 1 [October 18th, 2020](October 18th, 2020.md)
    - **[P1分享](P1分享.md):** 拟定**主题**进行分享讨论
        - 主题：{{query 的用法
        - 发起者
            
#@Jessie
    - **[P2讨论](P2讨论.md):** 围绕{{query 主题进行用例的延伸
    - **[P3 collective intelligence的pitching](P3 collective intelligence的pitching.md):** 有一些需要大家参与的公共graph项目（比如#[ℹ︎DeFi 词典](ℹ︎DeFi 词典.md) 可以来交流想法
    - 活动行链接：http://hdxu.cn/DqdJy
- [x] 面对面第五期的录制⏺️  @8pm [Roam面对面🍜 第五期](Roam面对面🍜 第五期.md)
    - 大家都要露脸啊🤩 
    - 看一下改版之后的效果，讨论和沉淀都重要
- [Batapha](Batapha.md) 在roam的官方页面找到的关于query的视频-主题：{{query 的用法[youtube视频](https://www.youtube.com/watch?v=LJZBGJOzhUY&feature=emb_logo&ab_channel=RobertHaisfield)
    - “and”语法是包含RoamCN与Jessie的page/block
        - {{[query](query.md): {and: [RoamCN meetup](RoamCN meetup.md) [@Jessie](@Jessie.md)}}}
    - “or”语法是包含RoamCN或Jessie的page/block
        - {{[query](query.md): {or: [RoamCN meetup](RoamCN meetup.md) [@Jessie](@Jessie.md)}}}
    - 前面的“and”是与后面的“or”的结果相交，或者叫交集。简单的理解就是包含Jessie的页面中选出带有RoamCN meetup或者是带有roam面对面的页面
        - {{[query](query.md): {and: [@Jessie](@Jessie.md) {or: [RoamCN meetup](RoamCN meetup.md) [roam面对面](roam面对面.md)}}}}
    - “not”语法就是不包含什么。在包含Jessie的页面中去除含有roam面对面的页面。
        - {{[query](query.md): {and: [@Jessie](@Jessie.md) {not: [roam面对面](roam面对面.md)]}}}}
