# swagger
how to use swagger ,know more about swagger specification

## in path
解释：参数是端点路径的一部分，因此需要在端点路径中明确提及它们

## in body
解释：参数的类型需要封装到schema关键字中。这与type直接使用的query / path / header / form参数不同


##swagger的写法结构
- 定义路径

- 定义https方法


- 定义响应内型
```
get/persons这个接口返回一组用户信息，我们通过响应消息中的模式（schema）
属性来描述清楚具体的返回内容。一组用户信息就是一个用户信息对象的数组（array）
，每一个数组元素则是一个用户信息对象（object），该对象包含三个string类型的
属性：姓氏、名字、用户名，其中用户名必须提供（required）
```
