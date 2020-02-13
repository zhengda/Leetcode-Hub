# 818. [困难] 赛车

**题目链接：**[https://leetcode-cn.com/problems/race-car](https://leetcode-cn.com/problems/race-car)

---

<div class="content__1Y2H">
 <div class="notranslate">
  <p>你的赛车起始停留在位置 0，速度为 +1，正行驶在一个无限长的数轴上。（车也可以向负数方向行驶。）</p> 
  <p>你的车会根据一系列由 A（加速）和 R（倒车）组成的指令进行自动驾驶&nbsp;。</p> 
  <p>当车得到指令 "A" 时, 将会做出以下操作：&nbsp;<code>position += speed, speed *= 2</code>。</p> 
  <p>当车得到指令 "R" 时, 将会做出以下操作：如果当前速度是正数，则将车速调整为&nbsp;<code>speed = -1</code>&nbsp;；否则将车速调整为&nbsp;<code>speed = 1</code>。&nbsp; (当前所处位置不变。)</p> 
  <p>例如，当得到一系列指令 "AAR" 后, 你的车将会走过位置 0-&gt;1-&gt;3-&gt;3，并且速度变化为&nbsp;1-&gt;2-&gt;4-&gt;-1。</p> 
  <p>现在给定一个目标位置，请给出能够到达目标位置的最短指令列表的<strong>长度</strong>。</p> 
  <pre class="language-text"><strong>示例 1:</strong>
<strong>输入:</strong> 
target = 3
<strong>输出:</strong> 2
<strong>解释:</strong> 
最短指令列表为 "AA"
位置变化为 0-&gt;1-&gt;3
</pre> 
  <pre class="language-text"><strong>示例 2:</strong>
<strong>输入:</strong> 
target = 6
<strong>输出:</strong> 5
<strong>解释:</strong> 
最短指令列表为 "AAARA"
位置变化为 0-&gt;1-&gt;3-&gt;7-&gt;7-&gt;6
</pre> 
  <p><strong>说明: </strong></p> 
  <ul> 
   <li><code>1 &lt;= target（目标位置） &lt;= 10000</code>。</li> 
  </ul> 
 </div>
</div>

---

```java
class Solution {
    public int racecar(int target) {
        
    }
}
```