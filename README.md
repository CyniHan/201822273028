# 201822273028
>1.在一个游戏中，主办方在三个门中任选一个，在门后放了一个奖品，另外两个门之后是空的。选手要在三个门中选择一个抽奖。 当选手选择了一个门，未曾打开门之前，主办方打开了另外两个门中没有奖品的那个门，并向选手说， 他可以改变他的选择，即转为选择剩下一个没有打开的门。 请问，如果选手此时改变选择， 他会提高或降低获奖的可能性么？提高多少？请给出你的分析。

答：
改变选择后获奖的可能性增加了。较原来增加了一倍。分析如下：
我们称选中奖品为事件 A, 选不中奖品为事件 B, 更改选择为 C, 不更改选择为 D 
1) 我们称第一次就选中奖品为事件 A1. 很显然 P(A1)=1/3. 
在 A1 的前提下, 如果更改选择, 得到奖品的概率是 0. P(A2|A1&C)=0. 
在 A1 的前提下, 如果不更改选择, 得到奖品的概率是 1. P(A2|A1&D)=1. 
2) 我们称第一次没有选中奖品为事件 B1. 有 P(B1)=2/3. 
在 B1 的前提下, 如果更改选择, 得到奖品的概率是 1. P(A2|B1&C)=1. 
在 B1 的前提下, 如果不更改选择, 得到奖品的概率是 0. P(A2|B1&D)=0. 
我们要比较 P(A2|C) 和 P(A2|D) ，很容易算出来 P(A2|C)=2/3, P(A2|D)=1/3. 
因此改变选择后。获奖的可能性会增加。

>2.如何看待 “中文房间” 问题，中文房间有智能么？它有什么样水平的智能？如何才能让它具有人类水平的智能？

答：
在我的理解中，中文房间”思想实验是用来反驳电脑和其他人工智能能够真正思考的观点的。房间里的人不会说中文，不能够用中文思考，但因为他拥有某些特定的工具，他甚至可以让以中文为母语的人以为他能流利的说中文。而实际上中文房间里人的所作所为，都谈不上思维和理解。这就像电脑一样，它们无法真正的理解接收到的信息，但它们可以运行一个程序，处理信息，然后给出一个智能的印象。在此印象之上，我们也可以说中文房间是有智能的，但只是表象的智能。
 塞尔思辨直接的结论是“中文房间实现的不是强人工智能”，一般化的推论是“不可能通过字符操作，从语言形式（syntax）得到语义内容（semantic）”。具有人类水平的智能，也可以说是“强人工智能”，这需要机器拥有深度学习的能力。这种能力要基于大数据的处理与运用。尽管人工智能虽然可以在某些方面超越人类,但想让机器完成人类能做到的一切工作，具有人类水平的智能，在目前还是难以实现的。

>3.学生根据讲课的内容和参考文献，用 NABCD 的模板，描述你心目中一个人工智能的创新项目。

答：
美食助手项目
1) Need：现代人很重视自己的饮食，但是很多人存在着对营养的误区和饮食恶习，严重影响了人们的营养健康。同时，对于美食的需求越来越丰富，烹饪爱好者也需要更符合他们追求的食物。
2) Approach：此app会根据输入的食材种类质量，自动统计出营养成分如热量维生素含量等，并计算是否均衡，和给出建议。另一个功能是根据历史数据和个人选择，智能推荐符合用户口味的菜谱，展示出详细的步骤。
3) Benefit：用户使用此app 可以获得合理科学的做法，避免营养成分不均衡，做出更健康的食物，做出更美味的食物，同时这个软件有一定的社交功能，问答他人，拜师学艺，切磋厨艺，营造一个烹饪爱好者交流心得的线上社区。
4) Competitors：做菜类软件普便普及率低，这个app也有着与众不同比较亮眼的功能，可以靠特色与传统做菜类app争夺市场，亦或是合作共享资源，使软件更成熟，内容更丰富。
5) Delivery：通过微博,bilibil等网络平台联系一些比较知名的美食博主up主，让他们进行宣传，把推广融合到自己做的视频里，这样的受众刚好会有许多是烹饪爱好者，同时年龄也偏向年青人，更乐意尝试智能软件。
