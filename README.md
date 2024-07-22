# LeetCode 热题 100

暴力，无冗余计算，剪枝；暴力，有冗余计算，动归；

# 刷题八极拳：坑爹用例全出来 双分单哈滑递动

## 第一拳：坑爹用例全出来

最重要的一拳，你要是少考虑了一种情况，整个算法函数就偏了，折腾半天就白耍了。卡在中间用例，或者死循环上，真噎人！即便你想到了后面的7拳，还是白耍！事实上差不多有一半的题目，它故意在例子上误导你，让你简单化算法，然后就偏了。

用例，用例！第一拳打在用例上，我觉得考虑全了，面试官，你看还漏不漏？

# 后七拳：双分单哈滑递动

绝大多数题目都是1000条数据以上，这就意味着你的算法效率必须低于O(N^2)，要不会超时。想运行的快速，O(N)级的算法都给套一遍：

- 双指针：一快一慢，两端往中间走，中间往两端走，行不行吧？
- 二分：排个序，单侧加倍二分，双侧二分，中间往两边分，有没有答案？
- 单调栈：双侧单调栈刷一刷
- 哈希集合：万能的字典集合，不用白不用
- 滑动串口：左滑一下，右滑一下，可能就过去了
- 递归：无论多少条数据，都可以万物归一递归下去，你就考虑一条的时候怎么整
- 动态规划：证明证明，我要做数学推拿

面对新题目，你不可能很快想到思路，就给他耍一套八级拳，可以框住绝大多数中高难度的题目了。耍不出来的话，再耍一遍，一定是变形的题目，拳是对的，发错位置打空气了，找面试官确认哪一拳打空了？！！
