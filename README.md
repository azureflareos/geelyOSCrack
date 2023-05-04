星瑞21换23车机安装第三方软件教程
此方法不需要任何拆机破解，方法来源于网络，本人不清楚来源、不清楚何人为开发者，本方法也不从任何付费渠道负责，本人也没赚钱，请勿找本人。
方法概要：从主题破解。本机xtz格式主题包中有一个名为xcscreensaver.apk的APK包，将该包替换为你想要安装的任何软件。


第一步：制作一个伪装xtz主题包。
1.下载本项目中的xtz包。下载本项目中的7zip.exe，为压缩软件。整合包需要7zip软件。
2.使用7zip解压该xtz包，得到四个文件（2个文件+2个文件夹）。
3.替换xcscreensaver.apk，注意你自己的软件需要重命名为xcscreensaver.apk。
4.选中四个文件，右键点击7zip选项，点击添加到压缩包。
5.压缩格式选择zip，压缩等级选择5-标准压缩，压缩方法选择*Deflate，其他选项不动，点击压缩。（这样压缩出来的文件头和原装xtz包一样，不兼容的概率很低，其他压缩软件自行尝试）。
6.在资源管理器中打开上方该菜单，选视图，点击“显示文件后缀名”的勾，然后将得到的zip包改名为clock.rabbit.xtz或这五个中的任何一个名字。注意不能是其他名字，description.xml也不要去改。
这样就做好了一个伪装的xtz包。

第二部：车机安装。
1.在车机拨号界面输入*# 日期+10 日期 12进制时间，例如5月4日13点，写*#150401（5+10=15，日期04，12进制时间01点）。
2.先开启ADB模式，再打开WIFI ADB模式，等待车机重启。
3.下载甲壳虫ADB助手（苹果使用atvtools，本项目不提供苹果教程），本项目已提供。（希望大家为开发者捐赠，软件很好用，开发不易，注：本人和开发者无任何关系）。并打开手机热点，车机连接手机热点。
4.重复第一步，在该界面中左边找到IP地址，如192.168.64.128，在甲壳虫中输入192.168.64.128:5555.
5.点击链接，下面会出现设备FS11-A1，没出现的多点几次连接。出现了FS11-A1就点进去。
6.将apk和刚刚做好的xtz包复制进手机，然后通过甲壳虫将安装包apk文件复制到车机/sdcard/Downloads目录，xtz包复制进/XUI/themes文件夹，如果没有themes文件夹的自行新建文件夹。
7.手机断网，一定要彻底断网，否则主题文件会自行重新下载为官方文件。在主题-屏保时钟中点击你刚刚替换的，比如你替换的是clock.rabbit.xtz，rabbit（兔子），那就点主题里的兔子时钟，点击应用，等一会会提示应用失败。（提示应用成功的就需要重新复制xtz包，第六步，直到提示应用失败为止）。
8.长按方向盘右边OK键直到车机重启。
9.车机重启后马上连接热点，手机清理后台（主要是为了杀掉甲壳虫，甲壳虫目前在我的安卓13有bug，第二次连不上，没bug的就算了）重新打开甲壳虫，点击应用，在应用里找到文件，点在设备上打开。
10.车机上会打开文件夹，然后点击左边的下载，找到你刚刚复制进去的apk包，直接点击，会进入安装，按正常安装流程走，会提示安装成功。

注意事项：
1.每次安装一个apk都需要重启一次，不能点击多个主题包应用后统一重启。
2.目前1189通过测试，1193还没测。
3.不要联系本人。本人不接受任何咨询。
4.其他压缩软件能不能行本人暂时不测试。
5.
