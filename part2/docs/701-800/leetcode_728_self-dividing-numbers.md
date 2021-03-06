# 728. [简单] 自除数

**题目链接：**[https://leetcode-cn.com/problems/self-dividing-numbers](https://leetcode-cn.com/problems/self-dividing-numbers)

---

<div class="content__1Y2H">
 <div class="notranslate">
  <p><em>自除数&nbsp;</em>是指可以被它包含的每一位数除尽的数。</p> 
  <p>例如，128 是一个自除数，因为&nbsp;<code>128 % 1 == 0</code>，<code>128 % 2 == 0</code>，<code>128 % 8 == 0</code>。</p> 
  <p>还有，自除数不允许包含 0 。</p> 
  <p>给定上边界和下边界数字，输出一个列表，列表的元素是边界（含边界）内所有的自除数。</p> 
  <p><strong>示例 1：</strong></p> 
  <pre class="language-text"><strong>输入：</strong> 
上边界left = 1, 下边界right = 22
<strong>输出：</strong> [1, 2, 3, 4, 5, 6, 7, 8, 9, 11, 12, 15, 22]
</pre> 
  <p><strong>注意：</strong></p> 
  <ul> 
   <li>每个输入参数的边界满足&nbsp;<code>1 &lt;= left &lt;= right &lt;= 10000</code>。</li> 
  </ul> 
 </div>
</div>

---

```java
class Solution {
    public List<Integer> selfDividingNumbers(int left, int right) {
        
    }
}
```

```java
import java.util.ArrayList;
import java.util.List;

class Solution {
    public List<Integer> selfDividingNumbers(int left, int right) {
        List<Integer> list = new ArrayList<>();
        for (int i = left; i <= right; i++) {
            if (isSelfDividingNum(i)) {
                list.add(i);
            }
        }
        return list;
    }

//    public boolean selfDividing(int num) {
//        for (char ch : String.valueOf(num).toCharArray()) {
//            if (ch == '0' || (num % (ch - '0') > 0))
//                return false;
//        }
//        return true;
//    }

    static boolean isSelfDividingNum(int num) {
        int tmp = num;
        while (tmp != 0) {
            int cur = tmp % 10;
            if (cur == 0 || num % cur != 0) {
                return false;
            }
            tmp /= 10;
        }
        return true;
    }

//    public static void main(String[] args) {
//        System.out.println(isSelfDividingNum(10));
//        System.out.println(isSelfDividingNum(22));
//
//        Solution728 solution = new Solution728();
//
//        System.out.println(solution.selfDividingNumbers(1, 22));
//    }
}
```