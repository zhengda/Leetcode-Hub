# $286. [中等] 墙与门

**题目链接：**[https://leetcode-cn.com/problems/walls-and-gates](https://leetcode-cn.com/problems/walls-and-gates)

---

<div class="content__1Y2H">
 <div class="notranslate">
  <p>你被给定一个&nbsp;<em>m × n</em>&nbsp;的二维网格，网格中有以下三种可能的初始化值：</p> 
  <ol> 
   <li><code>-1</code>&nbsp;表示墙或是障碍物</li> 
   <li><code>0</code>&nbsp;表示一扇门</li> 
   <li><code>INF</code>&nbsp;无限表示一个空的房间。然后，我们用&nbsp;<code>2<sup>31</sup> - 1 = 2147483647</code>&nbsp;代表&nbsp;<code>INF</code>。你可以认为通往门的距离总是小于&nbsp;<code>2147483647</code>&nbsp;的。</li> 
  </ol> 
  <p>你要给每个空房间位上填上该房间到&nbsp;<em>最近&nbsp;</em>门的距离，如果无法到达门，则填&nbsp;<code>INF</code>&nbsp;即可。</p> 
  <p><strong>示例：</strong></p> 
  <p>给定二维网格：</p> 
  <pre class="language-text">INF  -1  0  INF
INF INF INF  -1
INF  -1 INF  -1
  0  -1 INF INF
</pre> 
  <p>运行完你的函数后，该网格应该变成：</p> 
  <pre class="language-text">  3  -1   0   1
  2   2   1  -1
  1  -1   2  -1
  0  -1   3   4
</pre> 
 </div>
</div>

---

```java
class Solution {
    public void wallsAndGates(int[][] rooms) {
        
    }
}
```