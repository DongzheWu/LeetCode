```python
#1 queue = [] 生成一个队列
#2 queue.append(A)往queue里面添加一个元素A
#3 len(queue)求当前queue的大小
#4 queue[0]查看第一个元素
#5 queue.pop(0)移除一个元素


queue = []

queue.append(1)
#queue = [1]

size = len(queue)
#size = 1

queue.append(2)
#queue = [1, 2]

size = len(queue)
#size = 2

firstElement = queue[0]
#firstElement = 1

removeElement = queue.pop(0)
#removeElement = 1, queue = [2]

size = len(queue)
#size = 1

removeElement = queue.pop(0)
#removeElement = 2, queue = []

size = len(queue)
#size = 0
```