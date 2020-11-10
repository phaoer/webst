# webst
**综合了常用的js方法**

## 使用方法

### 直接引入

```html
<script src="lib/index.js"></script>
```

### NPM

```bash
npm i --save webst
```

## API列表
- getParam(str) —— 获取链接参数的值
- Base64Encode(str) —— base64加密
- Base64Decode(str) —— base64解密
- dateFormate(fmt, date) —— 日期格式化 ("yy:MM:dd hh:mm:ss", new Date())
- getTerminal() —— 获取终端信息 return {mobile:ture, ios:true, ...}
- getEndTime(startTime, endTime) —— 获取倒计时 ("yy:MM:dd hh:mm:ss", "yy:MM:dd hh:mm:ss")

## Usage
```javascript
    console.log(webst.getParam("a"));
    console.log(webst.Base64Encode("11111111"));
    console.log(webst.Base64Decode("MTExMTExMTE="));
    console.log(webst.getTerminal());
    console.log(webst.dateFormate("yyyy-MM-dd hh:mm:ss", new Date()));
    console.log(webst.getEndTime("2020-11-09 18:00:00", "2021-11-09 18:09:59"));
```