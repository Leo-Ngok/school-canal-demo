# xr-frame-demo

微信小程序`xr-frame`系统的示例集。

## 准备工作

目前需要下载最新的[Nightly版本工具](https://developers.weixin.qq.com/miniprogram/dev/devtools/nightly.html)，最新的客户端（安卓8.0.29，iOS8.0.29），以及基础库（2.27.1）。

## 直接体验

二维码以及部分样例的扫描图片详见：[官方文档-示例](https://developers.weixin.qq.com/miniprogram/dev/component/xr-frame/overview/index#示例)。

https://user-images.githubusercontent.com/7337763/199401152-d3e14ca2-bcde-41aa-902c-dc0fbd6b6358.mp4

### 模版

| 模版名称                                         | 截图                                       | 描述         |
|-----------------------------------------------|:------------------------------------------------:|:------------------:|
|[通信案例](./xr-template-message/) | ![](/screenshot/template-message.jpeg) | 通过小程序按钮事件，传递速度变量到 xr-Frame 控制小球移动，并将小球状态同步到小程序侧显示。（工具存在同层渲染问题，请于真机体验） |
|[加载案例](./xr-template-loading/) | ![](/screenshot/template-loading.png) | 点击按钮进行对应资源的加载与使用。（目前视频纹理属于beta状态，真机情况下，多张视频纹理不可以同时加载与渲染，但是可以取消一份后渲染另外一份） |
|[多Tracker案例](./xr-template-message/) | ![](/screenshot/template-tracker1.png) ![](/screenshot/template-tracker2.jpeg) ![](/screenshot/template-tracker3.jpeg)| 点击按钮，对应不同识别效果 Marker 的添加与删除。视频纹理加载过程会有白色透明层，加载完成后直接播放。视频目前属于beta阶段，存在加载失败超时的情况，为了避免目前版本的Crash问题，每次扫描会重新拉取视频。 |



## 版权

实例中用到的所有资源：

https://sketchfab.com/3d-models/borboleta-azul-butterfly-ab9192b6bc8f49e3baed63e984c7073a  
https://sketchfab.com/3d-models/just-a-girl-b2359160a4f54e76b5ae427a55d9594d  
https://sketchfab.com/3d-models/metal-table-60f8c279c7b64fce8241220178e543ec  
https://sketchfab.com/3d-models/fiesta-tea-8bde490c80444157b4545471d067423c  
https://sketchfab.com/3d-models/ship-in-clouds-c475323dc7f24e26ba2009c08c8e1941  
https://sketchfab.com/3d-models/cloud-station-26f81b24d83441ba88c7e80a52adbaaf  
https://sketchfab.com/3d-models/shiteyanyo-hatsune-miku-0f4029ba805c4751933bba24dc72dd24  
https://sketchfab.com/3d-models/miku-8b8028fa527549629b620752517812ac  
https://sketchfab.com/3d-models/pokemon-frlg-loreleis-arena-ce7397e95ec9458b8df3c1453e4d0b82  
https://sketchfab.com/3d-models/10th-attract-genderless-attraction-fc5548bb511e45748c393184ecbad26b  
https://sketchfab.com/3d-models/camera-limits-demo-van-gogh-bedroom-in-arles-daefab319a584e559443e39ff05e84fa  
https://sketchfab.com/3d-models/night-car-landscape-be4011aeb09740948bf30d33936c875b  
https://sketchfab.com/models/b81008d513954189a063ff901f7abfe4  
http://www.alexandre-pestana.com/pbr-textures-sponza/  
https://sketchfab.com/3d-models/jokers-mask-persona-5-81669910c0b74f41a3a58febfd514794

