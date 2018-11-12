---
description: 数据类型转换
---

# 10.Python数据类型转换

## **Python数据类型转换**

有时候，我们需要对数据内置的类型进行转换，数据类型的转换，你只需要将数据类型作为函数名即可。

| **函数** | **描述** |
| :--- | :--- |
| [int\(x \[,base\]\)](http://www.runoob.com/python3/python-func-int.html) | 将x转换为一个整数 |
| [float\(x\)](http://www.runoob.com/python3/python-func-float.html) | 将x转换到一个浮点数 |
| [complex\(real \[,imag\]\)](http://www.runoob.com/python3/python-func-complex.html) | 创建一个复数 |
| [str\(x\)](http://www.runoob.com/python3/python-func-str.html) | 将对象 x 转换为字符串 |
| [repr\(x\)](http://www.runoob.com/python3/python-func-repr.html) | 将对象 x 转换为表达式字符串 |
| [eval\(str\)](http://www.runoob.com/python3/python-func-eval.html) | 用来计算在字符串中的有效Python表达式,并返回一个对象 |
| [tuple\(s\)](http://www.runoob.com/python3/python3-func-tuple.html) | 将序列 s 转换为一个元组 |
| [list\(s\)](http://www.runoob.com/python3/python3-att-list-list.html) | 将序列 s 转换为一个列表 |
| [set\(s\)](http://www.runoob.com/python3/python-func-set.html) | 转换为可变集合 |
| [dict\(d\)](http://www.runoob.com/python3/python-func-dict.html) | 创建一个字典。d 必须是一个序列 \(key,value\)元组。 |
| [frozenset\(s\)](http://www.runoob.com/python3/python-func-frozenset.html) | 转换为不可变集合 |
| [chr\(x\)](http://www.runoob.com/python3/python-func-chr.html) | 将一个整数转换为一个字符 |
| [ord\(x\)](http://www.runoob.com/python3/python-func-ord.html) | 将一个字符转换为它的整数值 |
| [hex\(x\)](http://www.runoob.com/python3/python-func-hex.html) | 将一个整数转换为一个十六进制字符串 |
| [oct\(x\)](http://www.runoob.com/python3/python-func-oct.html) | 将一个整数转换为一个八进制字符串 |

示例：

```python
>>>aTest = '255'
>>>bTest = int(aTest)
>>>print(bTest)
>>>255
```

