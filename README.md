# Mark
仿 Mark 应用页面的微信小程序

小程序个人开发功能限制太多，无法完全上线，为了过审核都要费尽心思。原想项目完全上线了再开源的，方便大家看效果，但疲于过审核，算了，直接开源再一步一步完善吧。

你要是喜欢这清爽的界面，又觉得功能不够强悍，体验又不是很美观，我强烈建议你去体验原生应用 Mark。各大应用商店都可下载（搜索“Mark”）

![效果图1](http://opz28dn03.bkt.clouddn.com/images/IMG_1558.JPG?imageslim&imageView2/2/h/300)
![效果图2](http://opz28dn03.bkt.clouddn.com/images/IMG_1559.JPG?imageslim&imageView2/2/h/300)
![效果图3](http://opz28dn03.bkt.clouddn.com/images/CTJB2779.GIF?imageslim&imageView2/2/h/300)

**注意事项：**
此小程序因没有后台服务，数据都是网络静态数据和本地存储。

## 运行
没有使用其它打包工具，无需额外的环境配置，直接 clone 本项目，使用微信 Web 开发工具打开 `dist` 文件夹即可看见效果。

## 项目结构
```
...
├── components  组件化 Component
├── images  静态图片资源
├── pages  页面
|    └── common 模板 template
├── style  静态样式资源
└── utils  封装的工具
└── app.js  应用入口
└── app.json
└── app.wxss
└── config.js 配置常量
```

## 资源
1. [weui-wxss(微信官方UI样式)](https://github.com/Tencent/weui-wxss/)
2. [wxParse(富文本解析, 支持HTML和Markdown)](https://github.com/icindy/wxParse)
3. [小程序使用外部字体](http://www.wxapp-union.com/forum.php?mod=viewthread&tid=1211)
4. [微信小程序自定义组件wux](https://github.com/skyvow/wux)