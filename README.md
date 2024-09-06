# obs-studio 美颜+无绿幕抠图+贴纸
基于最新 obs-studio 30.2.2开发的美颜抠图滤镜，可以实现无绿幕直接抠图。<br>

## 安装使用流程如下<br>
### 1、先根据自己的系统选择文件下载<br>
苹果M芯片下载地址：[https://down.koudaiqiche.com/obs-beauty-1.1-apple.dmg](https://down.koudaiqiche.com/obs-beauty-1.1-apple.dmg)<br>
windows下载地址：[https://down.koudaiqiche.com/obs-beauty-win-1.0-x64.exe](https://down.koudaiqiche.com/obs-beauty-win-1.0-x64.exe)<br>
【windows第一次安装需要安装 [https://aka.ms/vs/17/release/vc_redist.x64.exe](https://aka.ms/vs/17/release/vc_redist.x64.exe) 】<br>
目前只支持苹果M芯片和windows64位系统，安装好后请先微信扫码登录<br>
### 2、安装文件<br>
如果win装了360会提醒，需全部点允许<br>
### 3、启动程序，mac启动obs,win启动桌面的obs-beauty<br>
### 4、第一次会出现二维码扫码框，拿出手机微信扫码<br>
### 5、扫码关注公账号后，程序会自动启动。扫码一次后下次使用就不需要了<br>
### 6、进入后点右下角设置<br>
mac启动后会去获取屏幕录制、麦克风、摄像头和辅助功能都需要点允许。如果没有获取到权限可以点击菜单obs studio > 检查应用权限。<br>
![img23.png](assets/img23.png)<br>
![img24.png](assets/img24.png)<br>
无障碍环境如果获取不了权限，可以先把列表里的obs选中再点下面的－移除，然后再点+重新添加obs就可以了
![img25.png](assets/img25.png)<br>
点设置操作<br>
![img.png](assets/img.png)<br>
点左边的输出，录像格式这里选择 分片MP4<br>
![img2.png](assets/img2.png)<br>
视频这里 基础和输出都选 **1920x1080** 🌟🌟 很重要一定要设置🌟🌟<br>
![img20.png](assets/img20.png)<br>
### 7、添加场景来源<br>
![img3.png](assets/img3.png)<br>
添加视频采集设备<br>
![img4.png](assets/img4.png)<br>
选择对应的摄像头<br>
![img5.png](assets/img5.png)
### 8、添加滤镜<br>
点中视频采集设备再点击滤镜<br>
![img6.png](assets/img6.png)<br>
在音视频滤镜  **美颜+抠图** 滤镜<br>
![img7.png](assets/img7.png)<br>
**设置如下图**<br>
![1](assets/1.jpg)<br>
并勾选 **开启背景处理**，可以调整美颜设置<br>
还需要在效果滤镜里添加 **色度键**  这样背景就透明了（最好在灯光比较亮的环境操作，背景环境不要太深，最好是全白之类的）<br>
![img8.png](assets/img8.png) ![img9.png](assets/img9.png)<br>
**最终效果如下图**<br>
![2](assets/2.jpg)<br>
### 9、先打开ppt选择幻灯片播放，然后切换到obs(win是ALT+TAB快捷键，mac是command+tab快捷键)再继续在场景来源里添加屏幕采集，方式选择窗口采集，勾选名称为空和显示全屏，然后在窗口中选择对应的 幻灯片放映<br>
![img21.png](assets/img21.png)<br>
![img22.png](assets/img22.png)<br>
然后在工作区调整视频区域位置，在工作区选中屏幕采集，调整好宽度到100%，再把屏幕拖上点的位置，ppt上部恰好沿着边缘；一定要注意第6步的视频设置都需要设置1920x1080<br>
![img10.png](assets/img10.png)<br>
在场景来源里选中屏幕采集，点击下面的向下按钮把屏幕采集放下面，视频采集就放到上层了。<br>
![img13.png](assets/img13.png)<br>
然后再调整视频稍微靠右，视频需要全身像的就需要拉满高度，不需要就放到右下角。都测试好后可以在来源哪里点击锁定，避免挪动了位置。<br>
### 10、全部设置好后就可以开始录制，然后ptt 幻灯片播放，录制完成后再停止录制，点菜单里的文件显示录像就可以看到刚才录制的视频文件，然后使用剪映等工具进行剪辑。(如果window系统装了360安全卫士会提醒，都点允许就好)<br>
![img15.png](assets/img15.png)<br>
如果不需要摄像头直接点击这个眼睛隐藏，位置调整好后可以点击锁定锁定位置。<br>
![img16.png](assets/img16.png)<br>
停止录制<br>
![img17.png](assets/img17.png)<br>
显示录像可以打开录像视频存储文件夹，可以看到所有录制视频列表<br>
![img18.png](assets/img18.png)
![img19.png](assets/img19.png)<br>
还可以去 设置 > 快捷键 里设置开始录制和停止录制的快捷键，这样就可以直接快捷键操作了！<br>
![img26.png](assets/img26.png)<br>

