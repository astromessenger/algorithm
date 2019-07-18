# algorithm
算法

### 请把该数据整理为树状结构, 该树每个节点的结构如下, 
```javascript
var data = [
    { parentId: 0, id: 1, value: '1' }, 
    { parentId: 3, id: 2, value: '2' },
    { parentId: 0, id: 3, value: '3' },
    { parentId: 1, id: 4, value: '4' }, 
    { parentId: 1, id: 5, value: '5' },
    { parentId: 11, id: 6, value: '6' },
    { parentId: 10, id: 7, value: '7' },
    { parentId: 10, id: 8, value: '8' },
    { parentId: 11, id: 9, value: '9' },
    { parentId: 11, id: 10, value: '10' },
    { parentId: 2, id: 11, value: '11' },
];
```
```javascript
node = {
    children: [],
    id: id,
    value: value
}
```

### 结果截图
![结果截图](https://github.com/astromessenger/algorithm/blob/master/QQ%E6%88%AA%E5%9B%BE20190718130532.jpg)
