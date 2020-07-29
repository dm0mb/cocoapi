## coco 数据集操作索引文档
---------------------------------------------

`COCO API-http://cocodataset.org/`  

COCO是一个大型图像数据集，专门用于对象检测，分割，人员关键点检测，东西分割和字幕生成。该软件包提供了Matlab，Python和Lua API，可帮助加载，解析和可视化COCO中的注释。请访问    `http://cocodataset.org/`了解有关COCO的更多信息，包括数据，论文和教程。注释的确切格式在COCO网站上也有描述。 Matlab和Python API都很完整，Lua API仅提供基本功能。  

除了此API外，请同时下载COCO图像和注释，以便运行演示并使用API​​。两者都可以在项目网站上找到。  
-请下载图片，解压缩图片并将其放在以下位置：`coco/images/`   
-请下载注释并将其放置在：`coco/annotations/`    
有关API的更多详细信息，请参见http://cocodataset.org/#download。  

下载图像和注释后，运行Matlab，Python或Lua演示进行示例用法。  

安装：  
-对于Matlab，将`coco/MatlabApi`添加到Matlab路径（提供了OSX / Linux二进制文件）   
-对于Python，在`coco/PythonAPI`下运行“ make”   
-对于Lua，请在coco/下运行“ `luarocks make LuaAPI/rocks/coco-scm-1.rockspec `    
