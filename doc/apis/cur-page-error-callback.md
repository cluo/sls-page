# 当前页码设置错误时回调

### 等设置的当前页<1或者>=总页数时，并且设置了curPageError:true,这个回调将被调用

这个回调返回三个参数

- cur	你设置的当前页
- count	总页数
- type	错误类型。2:大于总页数;3:小于1