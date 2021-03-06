## 系统架构师可以替代软件测试架构师吗

系统架构师也是我们非常熟悉的角色之一。在介绍软件测试在技术上的发展方向时就是通过将软件测试架构师和系统架构师进行对比的方法来表述的。可见软件测试架构师和系统架构师有一定的对等性，但是软件测试架构师服务的对象是产品测试而系统架构师服务的对象是产品开发。产品测试和产品开发本来就不是独立的两个活动，其中最简单的关系就是，产品开发出来的产品，会作为产品测试的输入，

产品测试的输出结果(如发现的产品缺陷，产品质量评估).又会反过来影响产品开发(修复缺陷，甚至是新需求的提出)。
所以软件测试架构师和系统架构师也有很多交集的地方:</br>
1. 对产品价值的理解。</br>
2. 对产品场景的理解。</br>
3. 对产品系统框架的理解。</br>
4. ... ... ... ... ...</br>

但是拥有很多交集并不代表系统架构师可以取代软件测试架构师。就像产品开发人员不能取代产品测试人员一样。GlenfordJMyers在他的著作《软件测试艺术》中，曾经从心理学的角度对上述问题的本质进行了分析。这是因为，产品开发的工作是“生成性”的是从无到有去创建一个产品；而产品测试找bug的过程却是“破坏性”的。很少有人可以做到客观地去创造一个东西，然后再客观地去毁坏一个东西。系统架构师和软件测试架构师也有以下类似的状态。

系统架构师理解产品的价值，是为了正确地创造并实现产品；软件测试架构师理解产品的价值，是为了验证产品是否真的实现了应有的价值，是否存在错误。

系统架构师理解产品场景，是为了分析出产品的特性和功能，为产品实现做准备；软件测试架构师理解产品场景，是为了验证产品是否满足用户在该场景中的使用需要，在该场景下产品是否存在质量缺陷。

系统架构师理解产品的系统框架，是为了产品最终能够顺利实现；软件测试架构师理解产品的系统框架，是为了测试设计和测试执行能够更有效，验证产品实现是否和架构的设计是一致的，是否存在问题。

可见，不同的关注视角使得软件测试架构师和系统架构师即使是在同一件事物的同个领域，也会出现巨大的不同。所以系统架构师并不能替代软件测试架构师，而是应该在以下方面相互协作。

系统架构师可以和软件测试架构师一起对产品价值进行讨论，相互理解。系统架构师需要和软件测试架构师一起整理用户使用场景，软件测试架构师对用户的潜在需求的理解，对友商同类产品的使用经验和曾经与用户沟通接触的经历都可以帮助系统架构师更好地确定用户使用场景，确定产品需求。


系统架构师还需要和软件测试架构师就产品的系统设计进行交流，
其实只有软件测试架构师对产品的实现理解得越深和越透，才能越准确地把握测试的重点，减少无效的测试而系统设计正是对产品实现理解的第一步。
软件测试架构师也可以根据产品的失效规律为系统架构师在产品架构设计上提供参考，进行缺陷预防。
所以，系统架构师和软件测试架构师应该成为产品研发中最亲密无间的挚友。

* * *
:bug: 
