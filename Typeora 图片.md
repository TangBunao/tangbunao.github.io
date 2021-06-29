### Typeora 文章中的图片

> - 使用 **Github** 作为图床。
> - 使用 **PicGo** 上传图片到 Github 并获取图片链接。
> - 设置 **Typeora** 的上传服务。



#### 一、Github 作为图床

> 1. 创建 ***Repository*** 用于存储图片。
> 2. 生成 ***Access Token*** 用于 **PicGo** 上传图片到 **GitHub**。

1. 创建 ***Repository*** ：

   ![](https://cdn.jsdelivr.net/gh/TangBunao/picture-library/img/20210629101851.png)

   

2. 生成 ***Access Token***：

   ![](https://cdn.jsdelivr.net/gh/TangBunao/picture-library/img/20210629102114.png)

   

   ![](https://cdn.jsdelivr.net/gh/TangBunao/picture-library/img/20210629102115.png)

   

   ![](https://cdn.jsdelivr.net/gh/TangBunao/picture-library/img/20210629102116.png)

   


   ![](https://cdn.jsdelivr.net/gh/TangBunao/picture-library/img/20210629102117.png)

#### 二、PicGo 上传工具

> 1. 下载 **PicGo**。
> 2. 设置 **Github** 图床。

1. 下载 **PicGo** ：[PicGo 官网](https://molunerfinn.com/PicGo/)

2. 设置 **GitHub** 图床：

   打开 **PicGo**，选择 **图床设置** 页签，然后选择 **GitHub图床**，填写在 **GitHub** 上新创建的 ***Repository*** 以及新生成的 ***Access Token***，点击 **确定**。

   ![](https://cdn.jsdelivr.net/gh/TangBunao/picture-library/img/20210629102757.png)

3. 上传一张图片进行测试：

   ![](https://cdn.jsdelivr.net/gh/TangBunao/picture-library/img/20210629102934.png)

   

   **PicGo** 提示上传成功，然后打开 **GitHub** 对应的 ***Repository***，查看图片已经成功上传：

   ![](https://cdn.jsdelivr.net/gh/TangBunao/picture-library/img/20210629103244.png)

#### 三、Typeora 设置

> 设置 **Typeora** 的上传服务。

打开 **Typeora** 的 **偏好设置** ：**文件** -> **偏好设置**，选择 **图像** 页签，在 **上传服务** 下拉框中选择 **PicGO (app)** 选项，然后选择 **PicGo 路径**，最后点击 **验证图片上传选项** 。

![](https://cdn.jsdelivr.net/gh/TangBunao/picture-library/img/20210629103655.png)


![](https://cdn.jsdelivr.net/gh/TangBunao/picture-library/img/20210629104103.png)


![](https://cdn.jsdelivr.net/gh/TangBunao/picture-library/img/20210629104201.png)

![](https://cdn.jsdelivr.net/gh/TangBunao/picture-library/img/20210629105409.png)



#### 四、Typeora 插入图片体验

> 已经全部设置好了，打开 **Typeora** 试一下。

在 **Typeora** 中新建文件，然后复制本地图片到 **Typeora** 中，此时可以看到文件的路径是本地路径。右键图片，然后选择上传图片，等待一会儿，**Typeora**就可以通过 **PicGo** 将图片上传到 **GitHub**了，而且上传成功后还会自动替换文件的路径为 **GitHub** 的路径，这样写文章的时候就不用担心图片的问题了。

![](https://cdn.jsdelivr.net/gh/TangBunao/picture-library/img/20210629104932.png)


![](https://cdn.jsdelivr.net/gh/TangBunao/picture-library/img/20210629105258.png)


![](https://cdn.jsdelivr.net/gh/TangBunao/picture-library/img/20210629105323.png)


![](https://cdn.jsdelivr.net/gh/TangBunao/picture-library/img/20210629105352.png)
