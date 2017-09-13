## 事件传递

类型| 相关方法 | Activity |ViewGroup |View
---|--------|----------|----------|----
事件分发|	dispatchTouchEvent|	√|	√|	√|
事件拦截|	onInterceptTouchEvent|	X|	√|	X
事件消费|	onTouchEvent	|√	|√	|√

事件从上到下分发
```
Activity －> PhoneWindow －> DecorView －> ViewGroup －> ... －> View
```