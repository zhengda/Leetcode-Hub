# 941. [简单] 有效的山脉数组

**题目链接：**[https://leetcode-cn.com/problems/valid-mountain-array](https://leetcode-cn.com/problems/valid-mountain-array)

---

<div class="content__1Y2H">
 <div class="notranslate">
  <p>给定一个整数数组&nbsp;<code>A</code>，如果它是有效的山脉数组就返回&nbsp;<code>true</code>，否则返回 <code>false</code>。</p> 
  <p>让我们回顾一下，如果 A 满足下述条件，那么它是一个山脉数组：</p> 
  <ul> 
   <li><code>A.length &gt;= 3</code></li> 
   <li>在&nbsp;<code>0 &lt; i&nbsp;&lt; A.length - 1</code>&nbsp;条件下，存在&nbsp;<code>i</code>&nbsp;使得： 
    <ul> 
     <li><code>A[0] &lt; A[1] &lt; ... A[i-1] &lt; A[i] </code></li> 
     <li><code>A[i] &gt; A[i+1] &gt; ... &gt; A[B.length - 1]</code></li> 
    </ul> </li> 
  </ul> 
  <p>&nbsp;</p> 
  <p><strong>示例 1：</strong></p> 
  <pre class="language-text"><strong>输入：</strong>[2,1]
<strong>输出：</strong>false
</pre> 
  <p><strong>示例 2：</strong></p> 
  <pre class="language-text"><strong>输入：</strong>[3,5,5]
<strong>输出：</strong>false
</pre> 
  <p><strong>示例 3：</strong></p> 
  <pre class="language-text"><strong>输入：</strong>[0,3,2,1]
<strong>输出：</strong>true</pre> 
  <p>&nbsp;</p> 
  <p><strong>提示：</strong></p> 
  <ol> 
   <li><code>0 &lt;= A.length &lt;= 10000</code></li> 
   <li><code>0 &lt;= A[i] &lt;= 10000&nbsp;</code></li> 
  </ol> 
  <p>&nbsp;</p> 
  <p>&nbsp;</p> 
 </div>
</div>

---

```java
class Solution {
    public boolean validMountainArray(int[] A) {
        
    }
}
```