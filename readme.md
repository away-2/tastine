# 塔斯汀小程序 模仿项目

- 本项目归塔斯汀所有， 只做学习所用 ， 请尊重原厂版权
- 可以去监听访问数据  fiddler  抓包工具抓取数据
- 
- 界面模仿采用markman做标记
  1. 无设计稿，如何1：1还原小程序？
  2. 拍平得到小程序截图
  3. 使用在线大小[转换工具](https://www.gaitubao.com/)，将图片改成750
    以后写项目时，直接可量像素， 因为小程序以750rpx作为
    设计稿标准大小帮我们自动适配，很好用
  4. 使用[markman](http://www.getmarkman.com/)先标注， 再写样式


  - 项目配置在根目录app.json
    - 隐藏并定制  "navigationStyle": "custom"
    - 启动定位功能
   
   
   - 使用了BEM 国际css命名规范
    一般命名 tst_banners 广告位  block
             tst_banners__img   Element


- css 技巧
  1. 能不用定位就不要用定位
     脱离文档流
  2. 移动端多用弹性布局
  


