# Visual Basic 6.0版本 中文笔记
## 提示
以下均使用VB6.0程序,不在介绍详细控件使用方式
Windows可以使用 Ctrl+F 来查找内容
macOS使用 ⌘ + F 
<br>
<br>



## 输出控件内容的状态（TEXT,LABEL）
### left & top
通常使用 Left 和 Top
Top数字为正数时向上反之向下,Left数字为正数是往左,反之同理

例如:
```
Label1.Top = 100
Label1.Left = 100

Label1.Top = -100
Label1.Left = -100
```


### 控件内容方向 Alignment的使用
用 0 1 2表示, 0是左边,1是右边,2是中间

例如:
```
Text1.Alignment = 2
Label1.Alignment = 2
```


### 隐藏
隐藏控件
```
Label1.Visible = True
```


### 颜色
控件内容颜色，vbColor是一种，还有一种是RGB的
```
Label1.ForeColor = vbBlue
```


### 倾斜状态
```
Label1.FontItalic = True
```


### 下划线的状态
```
Label1.FontUnderline = True
```


### 删除线状态
```
Label1.FontStrikethru = True
```


### 粗体状态
```
Label1.FontBold = True
```


### 标签颜色
```
Label1.BackColor = vbRed
```
