# EzOpenUIActiveXKit-Demo
Demo For EzOpenUIActiveXKit

# 快速入门

你可以通过一个简单的 [demo](github) 来快速了解EZUIKit 的用法。

   接入语言: Javascript  
   
   控件名称: EzOpenUIActiveXKit.ocx

   环境准备:
   支持 浏览器IE8 IE9 IE10
   支持 操作系统32Bit和64Bit
   
   
   
    


## 1. 创建应用

首先，你需要在控制面板中申请Appkey。请参考 [申请Appkey](appkeyUrl)。

## 2. 安装 SDK

SDK 的安装方式  
下载[EZUIKit SDK](EZUIKitSDK_URL)  
1、拷贝lib\win32\目录下dll和ocx以及bat文件到自己工程对应的依赖库目录;


## 3. 注册ocx

执行EzOpenUIKit_Register.bat, 如果有权限问题, 请"以管理员权限运行", 注册成功后会系统提示: DllRegisterServer 在EzOpenUIActiveXKit.ocx已成功


## 4. 运行 Demo

如果是IE8 请使用EzOpenUIKit_Demo_IE8.html
如果是IE8以上 请使用EzOpenUIKit_Demo_IE11.html

- Step1 Demo或者拖拽Demo到IE浏览器中
- Step2: 浏览器页面中点击"允许阻止的内容"
- Step3: 如果OCX还没有打证书, IE会提示"在此页上的ActiveX控件和本页的其他部分的交互可能不安全.n你想允许这种交互吗?", 选择"是(Y)".
- Step4: 从https://open.ys7.com/平台拿到传入参数, 格式如下
```json
{ 
 "AppKey":"596372da86f84628945da2476960ed9a", 
 "AccessToken":"at.5nn1d21p6ucmit3wbbwbgvp9copgsbhm-54uoo7yr4r-1r012n5-wgqpkksiy", 
 "Url":"ezopen://RXUVSV@open.ys7.com/701749234/1.hd.live" 
}
```
- Step5: 点击"开始播放", 如果播放成功, "播放结果" 窗口中会提示"播放成功!", 如果播放失败, "播放结果"窗口会提示播放错误码.
- Step6: 如果播放失败, 根据错误码参考[EZUIKit 错误码](EZUIKitSDK_URL)  


## 5. EzOpenUIKit 接口介绍


## 6. Demo代码  


## 7. 注意事项  

     
   
   
   
     
   
     
   
   
   
   
   
   
   
   
   
   
   




