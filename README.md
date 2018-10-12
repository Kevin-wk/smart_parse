# smart_parse
javascript 收货地址智能识别demo
## 执行parse之前必须操作一次parseArea生成专用数据
## 支持以下数据格式

1. 王志超,1351111111,陕西省西安市雁塔区创业咖啡街区海归楼3楼
2. 王志超1351111111陕西省西安市雁塔区创业咖啡街区海归楼3楼
3. 陕西省西安市雁塔区创业咖啡街区海归楼3楼1351111111王志超
4. 陕西省西安市雁塔区创业咖啡街区海归楼3楼150-0000-0000王志超
## 生成数据格式
```
{
addr: "创业咖啡街区海归楼3楼"
area: "雁塔区"
city: "西安"
detail: ""
mobile: "15000000000"
name: "王志超"
phone: ""
province: "陕西"
result: undefined
zip_code: ""
}
```
### 预览地址https://wzc570738205.github.io/boke/smartparse.html
