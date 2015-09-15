# checkrandom
计算验证某个生成随机数字函数的随机性，产出结果为衡量随机性的数值；

例如内置的随机函数
```javascript
//javascript or java language
Math.random
//or javascript
window.crypto.getRandomValue()
```

`一头雾水中`
##暂时性思路
 - 利用多维空间思路拆分随机函数的数字范围，
 - 计算离散度？（离散程度越大随机性越好）
