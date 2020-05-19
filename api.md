@[TOC](api)
## 首页
### 每日推荐
 - 简要描述:随便4个商品
 - 请求URL: 
` https://yuyangstudy.xyz/home/recommend`
 - 请求方式: GET
 - 参数: 无
 - 返回参数: 
参数名 | 类型 | 说明
   -|-|-
goods_name | string|商品名字|
image_src |string | 图片路径|
goods_id | number|商品id|
- 返回示例: 
```
{
	"message":[
		{
			"image_src":"https://yuyangstudy.xyz/static/picture1.jpg"
			"goods_name": "二手相机"
			"goods_id":1
		}
		{
			"image_src":"https://yuyangstudy.xyz/static/picture1.jpg"
			"goods_name": "二手相机"
			"goods_id":1
		}
		{
			"image_src":"https://yuyangstudy.xyz/static/picture1.jpg"
			"goods_name": "二手相机"
			"goods_id":1
		}
		{
			"image_src":"https://yuyangstudy.xyz/static/picture1.jpg"
			"goods_name": "二手相机"
			"goods_id":1
		}
	]
}
```
### 最新挂出
- 简要描述: 最新挂出的4个商品
- 请求URL:
` https://yuyangstudy.xyz/home/newgoods`
- 请求方式: GET
- 参数: 无
- 返回参数, 返回示例同上
### 最新需求
- 描述: 最新挂出的4个需求
- URL: 
` /home/newdemand`
- 请求方式: GET
- 参数: 无
- 返回参数
参数名 | 类型 | 说明
   -|-|-
  demands_detail|string|需求基本信息
demands_time|string|发布时间
demands_position|string|需求地点
demands_id|number|需求id
- 返回示例
```
{
	[
		
	]
}
```
 
## 商品
## 需求
## 我的
