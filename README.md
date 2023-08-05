# GVL
简介：这个项目是由本地部署的text generation（文本生成模型）结合vits（音频生成模型）结合Lived2D在unity平台实现带人格的虚拟角色

使用方法：

1、本地部署文本生成模型的webui并打开api功能，参考https://github.com/oobabooga/text-generation-webui

2、本地部署带api的音频生成模型的webui，参考https://github.com/Artrajz/vits-simple-api

3、导入给出的自定义包到unity

4、在test.cs和vits.cs能修改模型推理的参数，注意，因为两个模型的webui默认是同一个端口的，需要修改其中一个端口

5、拖入一个live2D模型到samplescene，导入live2D模型时插件会自动将模型文件转化为预制体，注意，相机需要修改正交和透视的设置，不然live2D显示会出错
