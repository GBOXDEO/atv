# 自动获取酒店源 #
复制过来的，不知什么原因，一直运行不正常啊。

2024.02.17更新，增加时间标签；因频道太多，cctv、卫视及其它频道均修改为单独的文件运行；修改为每四小时运行，更新更及时。

2024.02.11更新，修复部分频道错误。

2024.02.07更新，增加生成m3u文件。因手边无电脑，仅python文件更新，windows文件夹下文件未更新。

2024.02.04更新，可以每日自动运行了。每日早4点运行。

2024.02.01更新，增加单步执行的文件。itv_all.py及在window目录下的itv_all.exe。因频道太多，总运行时间大概50分钟。

2024.01.31更新，整理所有代码，更新如下：

1. 推荐在本地电脑运行，不推荐在github运行。因为github运行服务器不在国内，获得的数据不准确，测速不准。
2. windows目录下为可在win10独立运行的文件，无需python，只需要电脑安装最新的chrome(121.0.6167.85)，同时执行文件目录下要有对应版本的chromedriver.exe即可运行，否则报错。
3. 以前文件全部归到temp。
4. 最终生成的itvlist.txt文件只取了同一频道测速最快的前5个，可以最终使用。
5. 生成的全部频道文件，如itv.txt及itv_speed.txt不建议使用，因为频道太多，在diyp或派大星等软件中使用时播放会卡顿。此卡顿与频道的播放速度无关，是因为频道太多导致。

2024.01.26更新，对获取的ip地址第四位从1~255均尝试获取，能获取到隐藏的酒店源。采用了多线程，速度有大的提升。
