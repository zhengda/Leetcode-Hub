# 658. [中等] 找到 K 个最接近的元素

**题目链接：**[https://leetcode-cn.com/problems/find-k-closest-elements](https://leetcode-cn.com/problems/find-k-closest-elements)

---

<div class="content__1Y2H">
 <div class="notranslate">
  <p>给定一个排序好的数组，两个整数 <code>k</code> 和 <code>x</code>，从数组中找到最靠近 <code>x</code>（两数之差最小）的 <code>k</code> 个数。返回的结果必须要是按升序排好的。如果有两个数与 <code>x</code> 的差值一样，优先选择数值较小的那个数。</p> 
  <p><strong>示例&nbsp;1:</strong></p> 
  <pre class="language-text"><strong>输入:</strong> [1,2,3,4,5], k=4, x=3
<strong>输出:</strong> [1,2,3,4]
</pre> 
  <p>&nbsp;</p> 
  <p><strong>示例 2:</strong></p> 
  <pre class="language-text"><strong>输入:</strong> [1,2,3,4,5], k=4, x=-1
<strong>输出:</strong> [1,2,3,4]
</pre> 
  <p>&nbsp;</p> 
  <p><strong>说明:</strong></p> 
  <ol> 
   <li>k 的值为正数，且总是小于给定排序数组的长度。</li> 
   <li>数组不为空，且长度不超过 10<sup>4</sup></li> 
   <li>数组里的每个元素与&nbsp;x 的绝对值不超过 10<sup>4</sup></li> 
  </ol> 
  <p>&nbsp;</p> 
  <p><strong>更新(2017/9/19):</strong><br> 这个参数 <em>arr</em> 已经被改变为一个<strong>整数数组</strong>（而不是整数列表）。<strong><em>&nbsp;请重新加载代码定义以获取最新更改。</em></strong></p> 
 </div>
</div>

---

```java
class Solution {
    public List<Integer> findClosestElements(int[] arr, int k, int x) {

    }
}
```

```java
import java.util.Arrays;
import java.util.List;
import java.util.stream.Collectors;

public class Solution {
    public List<Integer> findClosestElements(int[] arr, int k, int x) {
        return Arrays.stream(arr)
                .boxed()
                .sorted((o1, o2) -> o1.equals(o2) ? 0 : Math.abs(o1 - x) - Math.abs(o2 - x))
                .collect(Collectors.toList())
                .subList(0, k)
                .stream()
                .sorted()
                .collect(Collectors.toList());
    }

//    public static void main(String[] args) {
//        int[] arr1 = {1, 2, 3, 4, 5};
//        int k1 = 4, x1 = 3;
//        int k2 = 4, x2 = -1;
//        Solution658 solution = new Solution658();
//        solution.findClosestElements(arr1, k1, x1).forEach(System.out::print);
//        solution.findClosestElements(arr1, k2, x2).forEach(System.out::print);
//    }
}
```
