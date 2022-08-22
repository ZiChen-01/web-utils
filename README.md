#                    sh-webutils

文档地址：<a href="https://jiangsihan.gitee.io/front_end/webutils/webutils.html">https://jiangsihan.gitee.io</a>

::: tip  前端 JavaScript 函数工具库

作者：ZiChen Jiang

邮箱：18307106535@163.com

最新版本：1.0.0

最近更新：2022-08-22


:::

## 简介

> 包含上百种`javascript`方法，检测邮箱、手机号码、字符串、数组、去重、AES/DES等.....
>
> 持续更新中.....

### 下载

`npm:`

```javascript
npm i sh-webutils
```

`cnpm:`

```javascript
cnpm i sh-webutils
```

`yarn:`

```javascript
yarn add sh-webutils
```

### 用法

```javascript
import { API , API , API } from 'sh-webutils'

//  API 为方法名，如：isEmail、isMobile等
```


## API

### 1、检测是否为邮箱

```javascript
import { isEmail } from 'sh-webutils'

isEmail('18307106535@163.com')  // true
isEmail('1111')  //false
```

### 2、检测是否为手机号

```javascript
import { isMobile } from 'sh-webutils'

isMobile('18307106535')  //true
isMobile('1111')  //false
```

### 3、检测是否为电话号码

```javascript
import { isPhone } from 'sh-webutils'

isPhone('400-670-0700')  //true
isPhone('400-670')  //false
```

### 4、检测是否为url地址

```javascript
import { isURL } from 'sh-webutils'

isURL('https://jiangsihan.cn')  //true
isURL('https://jiangsihan')  //false
```

### 5、是否字符串

```javascript
import { isString } from 'sh-webutils'

isString('hhhh')  //true
isString(123)  //false
```

### 6、是否数值

```javascript
import { isNumber } from 'sh-webutils'

isNumber(123)  //true
isNumber('123')  //false
```

### 7、是否boolean

```javascript
import { isBoolean } from 'sh-webutils'

isBoolean(true)  // true
isBoolean('123')  // false
```
### 8、是否为null

```javascript
import { isNull } from 'sh-webutils'

isNull(null) //true
isNull('123') //false
```
### 9、数组排序

```javascript
import { sort } from 'sh-webutils'

// type: 1：从小到大 2：从大到小 3：随机
sort(array,type)
```
### 10、字符串去除空格

```javascript
import { trim } from 'sh-webutils'

// type: 1-所有空格 2-前后空格 3-前空格 4-后空格
trim(str, type)	
```
### 11、字符转换

```javascript
import { changeCase } from 'sh-webutils'

// type: type: 1:首字母大写 2：首字母小写 3：大小写转换 4：全部大写 5：全部小写
changeCase(str, type)	
```
### 12、将数字转换为大写金额
```javascript
import { changeToChinese } from 'sh-webutils'

let num = 300
changeToChinese(num)	// 三百元
```
### 13、将阿拉伯数字翻译成中文的大写数字
```javascript
import { numberToChinese } from 'sh-webutils'

let num = 300
numberToChinese(num)	// 三百
```



### 文档未更新完，请稍后......
