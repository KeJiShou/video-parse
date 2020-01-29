# video-parse
短视频解析平台支持解析 抖音、快手、ins、faceBook、youtobe、西瓜视频、今日头条、小红书、微视、火山小视频、陌陌视频、映客视频、小咖秀、开眼、全民小视频、全民K歌、最右、小影、微博、美拍、皮皮虾等平台的短视频去水印解析API接口
## 短视频去水印解析接口(请联系微信jeenotes )

**接口描述：** 
    
	目前支持的平台 快手、抖音、火山、FaceBook、Ins、优酷、爱奇艺、腾讯视频、今日头条、西瓜视频、皮皮虾、小咖秀、趣多拍、微视、美拍、网易云、TikTok、陌陌、映客、迅雷、阳光宽频、全民K歌、刷宝、WIDE短视频、小红书、YouTube、哔哩哔哩、最右、皮皮搞笑、vue blog、全民小视频
	
	有任何疑问请联系微信 jeenotes ，请备注「接口解析」

**请求URL：** 
- ` http://api.mptask.wintp.top/xboot/qsy/parse`

**请求方式：**
- POST 

-   默认post方式调用
-   如果以其他方式调用，可能会产生无法识别参数，调用不成功等情况

### POSTMAN 请求调用示例

![](http://niceyoo.gitee.io/blog//img/2020_01_29/1580299747929_51a7136e-dab1-4c70-a850-af3aa11861da.png)

**参数：** 

|参数名|必选|类型|说明|
|:---- |:---|:----- |-----   |
|uuid |是  |string |认证标识，测试请用此值 ：230134411230711808   |
|content |是  |string | 视频连接，可以直接丢过来，不用去除中文  |

 **返回示例**

```
{
    "success": true,
    "message": "success",
    "code": 200,
    "timestamp": 1580299557795,
    "result": {
        "title": null,
        "url": "https://share.izuiyou.com/detail/154125720?zy_to=applink",
        "playUrl": "http://dlvideo.izuiyou.com/zyvd/56/66/571f-3a95-11ea-a967-00163e042306",
        "downloadUrl": "https://api.177dot.com/download/video/438010",
        "modifyDownloadUrl": "https://api.177dot.com/download/video/?id=438010&isChange=1",
        "cover": null
    }
}
```



> 解析不免费，1元2k次解析，需要测试，或者是使用该接口请联系微信 jeenotes，备注「接口解析」