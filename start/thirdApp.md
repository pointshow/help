# 第三方应用


## 在线应用

### 使用方法
1. 新建节目，选择网址组件。
2. 网址组件的网址填入在线应用地址。


### 乐茵商城

应用地址：https://s.pointshow.net/mkt/a/kzMall/index.html?categoryId=19

|应用参数|名称|值|必须|说明|
|--|--|--|--|--|
|分类ID|fGoodsCategroyId||Y|咨询乐茵商家获取|
|商户id|merchantId|LSLYYSH|N|固定值|
|来源|resource|LSLYYSH|N|固定值|
|秘钥|secretKey|1L+ajdQqZGWZPFeCnMsSjjc1hmidckLU|N|固定值|
|接口地址|api|http://49.4.27.85:8092/kzPlatformOut/mallGoodsShelfCtrl/queryMallGoodsShelfListByShopCode|N|必须使用encodeURIComponent编码后使用|


门店号的使用
1. 如何获取门店号？
咨询乐茵商家获取。
2. 商户系统中如何使用门店号？
设备管理创建网点时，填写网点号使用对应的门店号。


