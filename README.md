# mobile-share.js 社交分享组件([demo](http://www.biehaipa.com:8080/native/))
一个在手机端调用分享原生功能的组件，适配包括QQ，微信，UC，Safrai所有手机浏览器。
此插件基于[nativeShare](https://github.com/JefferyWang/nativeShare.js)进行了二次扩展，添了除调起UC，QQ浏览器内置分享组件之外的其他浏览器适配。

## 依赖
* 本插件不依赖任何其他的js库和组件。

## 使用方式
请注意，这里的`new nativeShare('nativeShare',config) `中的`nativeShare`是绑定触发按钮的，这里和原来插件使用方式不同的地方。
其他的`config`配置如下，详细的请参考index.html
```
<script>
    var config = {
        url:'http://blog.wangjunfeng.com',// 分享的网页链接
        title:'王俊锋的个人博客',// 标题
        desc:'王俊锋的个人博客',// 描述
        img:'http://www.wangjunfeng.com/img/face.jpg',// 图片
        img_title:'王俊锋的个人博客',// 图片标题
        from:'王俊锋的博客' // 来源
    };
    var share_obj = new nativeShare('nativeShare',config);
```
========
## 效果图
![MacDown Screenshot](https://github.com/caixiaojia/wxshare/blob/master/WechatIMG1.jpeg)
![MacDown Screenshot](https://github.com/caixiaojia/wxshare/blob/master/WechatIMG2.jpeg)
![MacDown Screenshot](https://github.com/caixiaojia/wxshare/blob/master/WechatIMG3.jpeg)
