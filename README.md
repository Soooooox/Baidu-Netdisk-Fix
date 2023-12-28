# 小声BB

开了百度会员还要看广告，新版本添加了很多没用的功能，不需要。  
本教程是使用旧版本，去除广告，让PC端windows界面更加清爽简洁。

# 百度云盘调教指南

## 屏蔽自动更新

1. 找到百度云盘安装目录
2. 删除以下更新文件
   1. 文件夹：`AutoUpdate`
   2. exe文件：`autoDiagnoseUpdate.exe`
   3. exe文件：`kernelUpdate.exe`

## 百度云盘历史版本

> 百度云官网的历史版本页面：https://pan.baidu.com/disk/version  

**官网下载链接样式**：(PC客户端)  
`https://issuepcdn.baidupcs.com/issue/netdisk/yunguanjia/BaiduNetdisk_X.X.X.X.exe`

**下载历史版本**：  
将上述下载链接的`X.X.X.X`替换成历史版本号 ，然后回车进行下载  
<span class="exp">https://issuepcdn.baidupcs.com/issue/netdisk/yunguanjia/BaiduNetdisk_7.2.8.9.exe</span>  

> **推荐版本**：7.2.8.9——最后一个未添加工作空间、大小仅66mb  
> **Tips**：在每次下载百度云盘的时候注意下百度下载链接，为后续版本下载使用  

## 界面设置

**修改前后对比图**：  

<center>
<img src="https://raw.githubusercontent.com/Soooooox/Image/main/202312071603674.png" alt="image-20231207160314536" width="49%"/>
<img src="https://raw.githubusercontent.com/Soooooox/Image/main/202312071627048.png" alt="image-20231207162722994" width="49%"/>
</center>

</br>

**设置区域**：
<center><img src="https://raw.githubusercontent.com/Soooooox/Image/main/202312071614006.png" alt="image-20231207161444948" width="70%"/></center>

> 设置区域分为3块：  
> 1. 序号1：工具侧边栏
> 2. 序号2：文件侧边栏
> 3. 序号3：标题栏

---

### 工具侧边栏

<span class="step">Step1：</span>对侧边工具栏右键  

<span class="step">Step2：</span>点击`从侧栏移除`  
<img src="https://raw.githubusercontent.com/Soooooox/Image/main/202312071606273.png" alt="image-20231207160626228" width="25%"/>

<span class="step">Step3：</span>依次重复移除  

---

### 文件侧边栏

<span class="step">Step1：</span>对侧边文件右键  

<span class="step">Step2：</span>点击`从侧栏移除`  
<img src="https://raw.githubusercontent.com/Soooooox/Image/main/202312071607540.png" alt="image-20231207160710506" width="25%"/>

<span class="step">Step3：</span>依次重复移除  

---

### 标题栏

> 不想自己删除的，可以直接下载我给的 duiengineskin.zip 文件

<span class="step">Step1：</span>打开百度云盘的目录  

<span class="step">Step2：</span>找到`BaiduNetdisk/skin`路径下的皮肤文件：  
<img src="https://raw.githubusercontent.com/Soooooox/Image/main/202312071659280.png" alt="image-20231207165912246" width="60%"/>

<span class="step">Step3：</span>用解压包软件打开，进入`duiengineskin.zip\xml\MainPanel\`对以下文档进行修改

> **注意**：对压缩包一定要用右键使用压缩包打开，然后进行修改

- 删除`ToolbarBubbleAdDlg.xml`和`AdCardWnd.xml`
- 修改`TitlePanel.xml`：  
<img src="https://raw.githubusercontent.com/Soooooox/Image/main/202312071811375.png" alt="image-20231207181148298" width="90%"/>

- 修改`UserCardWnd.xml`：  
<img src="https://raw.githubusercontent.com/Soooooox/Image/main/202312071815873.png" alt="image-20231207181503825" />
<img src="https://raw.githubusercontent.com/Soooooox/Image/main/202312071816795.png" alt="image-20231207181605750" />
<img src="https://raw.githubusercontent.com/Soooooox/Image/main/202312071817463.png" alt="image-20231207181724410" />

- 到`TransPanel\`文件夹下，修改`TransLeftPanel.xml`：  
<img src="https://raw.githubusercontent.com/Soooooox/Image/main/202312071820153.png" alt="image-20231207182038091" />

<span class="step">Step4：</span>将`duiengineskin.zip`属性设置为`只读`  

> 最好修改前先复制一份`duiengineskin.zip`，避免程序崩溃需要重装

# 参考链接

> - [删除自动更新](https://zhuanlan.zhihu.com/p/645259468)
> - [网盘一个清爽的界面](https://www.bilibili.com/video/BV1QK4y1n7Qz)
> - [百度云盘历史版本](https://www.bilibili.com/read/cv22449371/)

<details>
<summary>11111</summary>

这就是折叠内容

</details>

