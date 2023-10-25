

> [!TIP]
> - **视频文件名命名规范见“**[**剪辑视频文件名命名规范**](https://www.yuque.com/decmoe47/qc69ed/wyngip#e9bf48a2)**”。**
> - 关于“项目”和“子项目”的概念，见“[什么是项目和子项目？](https://www.yuque.com/decmoe47/qc69ed/ig9i3c#JnRvf)”。
> - 工作表里的下载链接是由制作进行插入的，你无需插入链接（也无法获得正确的链接）。
> 

## 使用的软件

本组一般使用**Adobe Premiere**剪辑视频 。当然你也可以使用其他软件，但必须是无水印且可更改输出设置的软件。

组内提供Pr的下载：[破解版Adobe_Premiere_Pro_2020_14.0.0.571_SP_20191023](https://mononobealice-my.sharepoint.cn/:u:/g/personal/e307220930_mononobealice_partner_onmschina_cn/EU3Vkb3hVwtKsLSgo2GLLbIBu2mP4r8Rv6mKgA9UGs-4LA?e=R44uYM)

## 剪辑要求

通过Onedrive网盘获取源视频文件后，导入Pr，剪出要剪的片段，并在首尾加上OP、ED，然后将剪辑好的序列导出。

> [!ATTENTION]
> 序列帧速率（FPS）应与视频的**保持一致**。

### OP和ED的嵌入

目前在使用的OP、ED是：

- op1(音乐完整+Alpha通道).mov
- 【新ED（推荐）】三周年新ED_1920x1080.mp4
- 【旧ED】
   - ED_paryi版(720P).mp4
   - ED_paryi版(1080P).mp4

以上文件请去工作群文件里“OP和ED”文件夹里下载，或点击[此链接](https://mononobealice-my.sharepoint.cn/:f:/g/personal/e307220930_mononobealice_partner_onmschina_cn/EtnpsrW3tm9ChG429aBh3X0Bu65D2w89P67NdscSu9gKRQ?e=jG6lk4)前去下载（密码与组内OneDrive的进入密码一样，见群公告）。

> [!WARNING]
> - 当视频为比较安静的内容（如ASMR、深夜杂谈等），OP应改为无声。
> - 当视频开头就是歌时，可以将op本身的音乐去掉，衔接开头的歌声。（同理于ED）（仅建议，非必须）
> - 一般情况下使用的OP是“op1(音乐完整+Alpha通道).mov”，用法见下。
> 
![](https://cdn.nlark.com/yuque/0/2020/png/2350898/1598150279064-fe5402f7-faed-4ac9-8ec0-7830d4bd9ca1.png#height=693&id=TzIZH&originHeight=872&originWidth=873&originalType=binary&ratio=1&size=0&status=done&style=none&width=694)
> 如果有特殊需要时，选择无Alpha通道的。
> - 注意ED有720P和1080P版本，请根据源视频的分辨率选择对应的ED。
> - OP和ED的音频增益应该调整到合适的量，并与视频内容保持相对平衡。


### 导出参数

- 导出设置的格式应为H.264。
- 比特率VBR2次，
   - 源为720P时：
      - 杂谈回目标3Mbps、最大6Mbps；
      - 游戏回目标4Mbps、最大8Mbps。
   - 源为1080P时：
      - 杂谈回目标4Mbps、最大8Mbps；
      - 游戏回目标5Mbps、最大10Mbps。
- 音频比特率320kbps，采样率48000Hz。

## ED插入推荐视频的跳转
新ED增加了推荐视频空位，在剪辑时可以在对应位置贴上封面，之后投稿时插入弹幕链接就能完成推荐视频的跳转了。

### 1. 登记
首先选择想要关联的视频，在备注中填写

![](https://gitee.com/anguvia/blogimage/raw/master/img/image-20210502223818587.png#id=ZXEdS&originHeight=145&originWidth=273&originalType=binary&ratio=1&status=done&style=none)

在B站视频简介中找到剪辑日期，到OD中寻找封面，也可以用[bilibili封面提取](https://bilicover.magecorn.com/) 来获取封面 

### 2. 制作文字贴图 
打开文字贴图psd，选择竖排文字工具。

![](https://gitee.com/anguvia/blogimage/raw/master/img/image-20210502224349148.png#id=pk00E&originHeight=784&originWidth=233&originalType=binary&ratio=1&status=done&style=none) 

字体为图中内容Resource Han Rounded SC，在时轴教程中应该能找到。

![](https://gitee.com/anguvia/blogimage/raw/master/img/image-20210502224429636.png#id=R4Q6F&originHeight=124&originWidth=431&originalType=binary&ratio=1&status=done&style=none) 

点击psd文字中即可编辑，排版随意，整齐美观即可。

![](https://gitee.com/anguvia/blogimage/raw/master/img/image-20210502224634037.png#id=dodK2&originHeight=526&originWidth=364&originalType=binary&ratio=1&status=done&style=none) 

最后导出为png即可。

### 3. 嵌入ED视频 
将封面和文字贴图导入pr，拖到工作区里。封面应该很大，自行调整即可。

![](https://gitee.com/anguvia/blogimage/raw/master/img/image-20210502225159365.png#id=Trfv4&originHeight=495&originWidth=859&originalType=binary&ratio=1&status=done&style=none) 

最好调整为上下边距之和为左边边距，文字贴图如下所示。

![](https://gitee.com/anguvia/blogimage/raw/master/img/image-20210502225334972.png#id=wlSY6&originHeight=229&originWidth=353&originalType=binary&ratio=1&status=done&style=none) 

图片设置的时长为20秒左右，文字与图片同长 。

![](https://gitee.com/anguvia/blogimage/raw/master/img/image-20210502225637915.png#id=WN0nB&originHeight=239&originWidth=197&originalType=binary&ratio=1&status=done&style=none) 

寻找插入的时间点，为ED开始后的第17秒，于此放入图片。

![](https://gitee.com/anguvia/blogimage/raw/master/img/image-20210502225848490.png#id=HkcfY&originHeight=213&originWidth=185&originalType=binary&ratio=1&status=done&style=none) 

也可以先在ED左边的图片框已经固定时嵌入图片然后再重新播放ED ，大约在图中被圈住的两个的角对齐的时间点即为图片插入时间点。

![](https://gitee.com/anguvia/blogimage/raw/master/img/image-20210502230738331.png#id=exqtX&originHeight=234&originWidth=352&originalType=binary&ratio=1&status=done&style=none) 

关于特效，封面与文字图片时间轴右侧均为交叉溶解，左侧时间轴封面图片为交叉溶解，文字图片为插入，插入特效将时间拉长为原来的两倍即可。

![](https://gitee.com/anguvia/blogimage/raw/master/img/image-20210502230128796.png#id=d99Gj&originHeight=277&originWidth=223&originalType=binary&ratio=1&status=done&style=none)

![](https://gitee.com/anguvia/blogimage/raw/master/img/image-20210502230046987.png#id=Du07v&originHeight=123&originWidth=185&originalType=binary&ratio=1&status=done&style=none)

### 4. 插入视频链接
此项由投稿人负责，剪辑不用负责。

最终效果如下：

![image.png](https://cdn.nlark.com/yuque/0/2021/png/2350898/1620363343051-5b3e37a4-85cf-4e96-aa6e-4386381ec3c7.png#clientId=u19855cc0-14cd-4&from=paste&height=447&id=uc085246d&originHeight=893&originWidth=1602&originalType=binary&ratio=1&size=2571512&status=done&style=none&taskId=ud9db1242-0745-4d1a-9ce8-fddcdb44fe1&width=801)

## 小爱丽丝进度条（可选）

- 首先根据剪辑时长选择进度条时长

![](https://cdn.nlark.com/yuque/0/2021/png/2350898/1633838314784-e99eb103-bf8d-41da-8e2a-f9e4e6f15433.png#clientId=u871e351f-2954-4&from=paste&id=u49bc6aed&originHeight=287&originWidth=684&originalType=url&ratio=1&status=done&style=none&taskId=u1c51b78a-1997-4142-85d5-cec994428fa)

![](https://cdn.nlark.com/yuque/0/2021/png/2350898/1633838314598-620e5d3f-8bfe-4c00-a8bd-f596ee36066b.png#clientId=u871e351f-2954-4&from=paste&id=u669319f4&originHeight=244&originWidth=574&originalType=url&ratio=1&status=done&style=none&taskId=u8844467b-71cd-4e45-9a52-bd8ea9c6fff)

- 导入PR，因为其自带一条无声音频，拖拽时注意不要覆盖其他音频

![](https://cdn.nlark.com/yuque/0/2021/png/2350898/1633838314621-39524fc3-4ab5-4284-afb9-e309740e7fdd.png#clientId=u871e351f-2954-4&from=paste&id=u7cd6629c&originHeight=196&originWidth=640&originalType=url&ratio=1&status=done&style=none&taskId=u393017a1-55b2-4e70-af09-053206b0cd4)

- 剪掉进度条多余的部分

![](https://cdn.nlark.com/yuque/0/2021/png/2350898/1633838314630-1ec24050-8600-4abc-b23d-a72d6891291c.png#clientId=u871e351f-2954-4&from=paste&id=u736f30a0&originHeight=288&originWidth=475&originalType=url&ratio=1&status=done&style=none&taskId=u56bad7d4-65a6-427d-bc93-96597f59b55)

- 双击选中进度条轨道，在源中点击效果控件

![](https://cdn.nlark.com/yuque/0/2021/png/2350898/1633838314672-dea6be1d-2411-454e-9dd9-ab36ac139b17.png#clientId=u871e351f-2954-4&from=paste&id=u13fe69f1&originHeight=562&originWidth=960&originalType=url&ratio=1&status=done&style=none&taskId=uffa8c079-e37b-4e7b-aa26-a813fe584a4)

![](https://cdn.nlark.com/yuque/0/2021/png/2350898/1633838315275-c0eb197f-5f90-423a-8be0-970c9170b013.png#clientId=u871e351f-2954-4&from=paste&id=u9971b3a6&originHeight=580&originWidth=965&originalType=url&ratio=1&status=done&style=none&taskId=u9590effa-cbe9-4a51-a00b-3e88aa4d739)

- 首先不要着急设置关键帧，调整位置数值为 (6 , 1048.9)，此时进度条位置刚好在左下角

![](https://cdn.nlark.com/yuque/0/2021/png/2350898/1633838315542-ed245363-146e-455f-a762-b83cd11a45be.png#clientId=u871e351f-2954-4&from=paste&id=u56503354&originHeight=86&originWidth=704&originalType=url&ratio=1&status=done&style=none&taskId=u2f583f22-fa25-4a15-b248-098940056d6)

![](https://cdn.nlark.com/yuque/0/2021/png/2350898/1633838315377-5020fd4a-8cf4-4ca7-b9da-66736e079267.png#clientId=u871e351f-2954-4&from=paste&id=uc5aaccff&originHeight=94&originWidth=778&originalType=url&ratio=1&status=done&style=none&taskId=u0e058151-951c-482e-9174-bfa8e4953c3)

- 之后将PR的工作区的进度拉到视频最开始的位置，点击效果控件中位置部分左侧的秒表图标，设置第一个关键帧

![](https://cdn.nlark.com/yuque/0/2021/png/2350898/1633838315421-2b0908a7-1117-4371-a10a-1fabf37ee048.png#clientId=u871e351f-2954-4&from=paste&id=ua05ef820&originHeight=135&originWidth=953&originalType=url&ratio=1&status=done&style=none&taskId=u67193aed-6054-4b24-8437-c680d9c4674)

- 最后将工作区的进度拉到视频结束的位置，记得在播放完的最后部分左移一帧，此时只需要调整位置的数值即可，不需要再次点击秒表图标，将位置数值调整为( 1924 , 1048.9)

![](https://cdn.nlark.com/yuque/0/2021/png/2350898/1633838315519-52430ea7-52dd-45fe-96bc-cb6dc488ea1a.png#clientId=u871e351f-2954-4&from=paste&id=ucd7826d5&originHeight=283&originWidth=138&originalType=url&ratio=1&status=done&style=none&taskId=u1f258bfe-d20d-42d3-875c-4bb36a12f22)

![](https://cdn.nlark.com/yuque/0/2021/png/2350898/1633838316048-b361cd1a-d915-49ab-a608-fe95895b094a.png#clientId=u871e351f-2954-4&from=paste&id=uaf14c6b7&originHeight=79&originWidth=701&originalType=url&ratio=1&status=done&style=none&taskId=u7b6b7eb7-4f38-4234-b53a-1127088f720)

- 进度条正好在右下角

![](https://cdn.nlark.com/yuque/0/2021/png/2350898/1633838316065-55187c20-511c-42d4-bc54-fe1a02e49457.png#clientId=u871e351f-2954-4&from=paste&id=uae8f7dbe&originHeight=41&originWidth=785&originalType=url&ratio=1&status=done&style=none&taskId=uecd9f81f-24bf-4845-a0b9-26b97358d24)

- 之后按照往常的设置导出即可

进度条下载地址在OneDrive的素材和工具→剪辑→进度条中


