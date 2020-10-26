### 排序函数

- sorted有返回对象，接受任何可迭代对象
- sort返回None，只接受list，原位排序
- python2

```python
def cmp(a, b):
  # 如果逻辑上认为 a < b ，返回 -1
  # 如果逻辑上认为 a > b , 返回 1
  # 如果逻辑上认为 a == b, 返回 0 
  pass

a = [2,3,1,2]
a = sorted(a, cmp)
```

- python3：无cmp，只存key。两种自定义排序规则的做法。

```python
import functools
def cmp(a, b):
    if b < a:
        return -1
    if a < b:
        return 1
    return 0
a = [1, 2, 5, 4]
print(sorted(a, key=functools.cmp_to_key(cmp)))
```

```python
class LargerNumKey(str):
    def __lt__(x, y):
        return x+y > y+x
        
class Solution:
    def largestNumber(self, nums):
        largest_num = ''.join(sorted(map(str, nums), key=LargerNumKey))
        return '0' if largest_num[0] == '0' else largest_num
```