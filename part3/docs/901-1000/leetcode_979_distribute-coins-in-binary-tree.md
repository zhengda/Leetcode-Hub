# 979. [中等] 在二叉树中分配硬币

**题目链接：**[https://leetcode-cn.com/problems/distribute-coins-in-binary-tree](https://leetcode-cn.com/problems/distribute-coins-in-binary-tree)

---

<div class="content__1Y2H">
 <div class="notranslate">
  <p>给定一个有 <code>N</code> 个结点的二叉树的根结点 <code>root</code>，树中的每个结点上都对应有 <code>node.val</code> 枚硬币，并且总共有 <code>N</code> 枚硬币。</p> 
  <p>在一次移动中，我们可以选择两个相邻的结点，然后将一枚硬币从其中一个结点移动到另一个结点。(移动可以是从父结点到子结点，或者从子结点移动到父结点。)。</p> 
  <p>返回使每个结点上只有一枚硬币所需的移动次数。</p> 
  <p>&nbsp;</p> 
  <p><strong>示例 1：</strong></p> 
  <p><strong><img style="height: 142px; width: 150px;" src="/aliyun-lc-upload/uploads/2019/01/19/tree1.png" alt=""></strong></p> 
  <pre class="language-text"><strong>输入：</strong>[3,0,0]
<strong>输出：</strong>2
<strong>解释：</strong>从树的根结点开始，我们将一枚硬币移到它的左子结点上，一枚硬币移到它的右子结点上。
</pre> 
  <p><strong>示例 2：</strong></p> 
  <p><strong><img style="height: 142px; width: 150px;" src="/aliyun-lc-upload/uploads/2019/01/19/tree2.png" alt=""></strong></p> 
  <pre class="language-text"><strong>输入：</strong>[0,3,0]
<strong>输出：</strong>3
<strong>解释：</strong>从根结点的左子结点开始，我们将两枚硬币移到根结点上 [移动两次]。然后，我们把一枚硬币从根结点移到右子结点上。
</pre> 
  <p><strong>示例 3：</strong></p> 
  <p><strong><img style="height: 142px; width: 150px;" src="/aliyun-lc-upload/uploads/2019/01/19/tree3.png" alt=""></strong></p> 
  <pre class="language-text"><strong>输入：</strong>[1,0,2]
<strong>输出：</strong>2
</pre> 
  <p><strong>示例 4：</strong></p> 
  <p><strong><img style="height: 156px; width: 155px;" src="/aliyun-lc-upload/uploads/2019/01/19/tree4.png" alt=""></strong></p> 
  <pre class="language-text"><strong>输入：</strong>[1,0,0,null,3]
<strong>输出：</strong>4
</pre> 
  <p>&nbsp;</p> 
  <p><strong>提示：</strong></p> 
  <ol> 
   <li><code>1&lt;= N &lt;= 100</code></li> 
   <li><code>0 &lt;= node.val &lt;= N</code></li> 
  </ol> 
 </div>
</div>

---

```java
/**
 * Definition for a binary tree node.
 * public class TreeNode {
 *     int val;
 *     TreeNode left;
 *     TreeNode right;
 *     TreeNode(int x) { val = x; }
 * }
 */
class Solution {
    public int distributeCoins(TreeNode root) {
        
    }
}
```