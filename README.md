<tr>
<h1>Python程式設計-期中報告</h1>
<h3>11124232卓柏宇、11124230葉承諺</h3>
</tr>
<h4>用字典實現學生成績管理{'A':84, 'B':90, 'C':75, 'D':82}，求出最高分，最低分，總人數，平均分。</h4>

<h4>創建一個字典</h4>

```python
mark = {'A':84,'B':90,'C':75,'D':82}
```

<h4>使用max、min獲取列表的最大最小值</h4>

```python
print(max(mark.values()))
print(min(mark.values()))
```
<h4>在使用len獲取列表長度</h4>

```python
print(len(mark))
```
<h4>最後再用sum獲取總和再除以總人數就可獲得平均</h4>

```python
print(sum(mark.values())/len(mark))
```

<h3>輸出結果</h3>

![image](https://github.com/qwertidy/report/blob/main/python.png)
