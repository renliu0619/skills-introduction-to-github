# 测试代码（pytest）

下面是一个简单的 Python 测试示例：

```python
# test_example.py
def add(a, b):
    return a + b

def sub(a, b):
    return a - b

def test_add():
    assert add(2, 3) == 5

def test_sub():
    assert sub(5, 3) == 2
```

运行：
```
pytest -q
```testdsdsdsdsd

