# 650. [中等] 只有两个键的键盘

**题目链接：**[https://leetcode-cn.com/problems/2-keys-keyboard](https://leetcode-cn.com/problems/2-keys-keyboard)

---

<div class="content__1Y2H">
 <div class="notranslate">
  <p>最初在一个记事本上只有一个字符 'A'。你每次可以对这个记事本进行两种操作：</p> 
  <ol> 
   <li><code>Copy All</code> (复制全部) : 你可以复制这个记事本中的所有字符(部分的复制是不允许的)。</li> 
   <li><code>Paste</code> (粘贴) : 你可以粘贴你<strong>上一次</strong>复制的字符。</li> 
  </ol> 
  <p>给定一个数字&nbsp;<code>n</code>&nbsp;。你需要使用最少的操作次数，在记事本中打印出<strong>恰好</strong>&nbsp;<code>n</code>&nbsp;个 'A'。输出能够打印出&nbsp;<code>n</code>&nbsp;个 'A' 的最少操作次数。</p> 
  <p><strong>示例 1:</strong></p> 
  <pre class="language-text"><strong>输入:</strong> 3
<strong>输出:</strong> 3
<strong>解释:</strong>
最初, 我们只有一个字符 'A'。
第 1 步, 我们使用 <strong>Copy All</strong> 操作。
第 2 步, 我们使用 <strong>Paste </strong>操作来获得 'AA'。
第 3 步, 我们使用 <strong>Paste</strong> 操作来获得 'AAA'。
</pre> 
  <p><strong>说明:</strong></p> 
  <ol> 
   <li><code>n</code>&nbsp;的取值范围是 [1, 1000] 。</li> 
  </ol> 
 </div>
</div>

---

```java
class Solution {
    public int minSteps(int n) {
        
    }
}
```