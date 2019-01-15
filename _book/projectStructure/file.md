# 第一节、文件夹结构

[参考连接](https://docs.cocos.com/creator/manual/zh/getting-started/project-structure.html)



```
├──assets 资源文件夹 项目编辑的所有资源(脚本，图片，音频等)                                 ***
├──build 构建后的项目文件，当构建完成时，我们在这个文件夹里面找所需要的资源（文件夹或者apk或其他格式文件）
├──library assets导入后生成的，被处理成发布所需的格式，如果这个文件夹有问题，删除即可
├──local  本地设置，编辑器信息，布局，显示位置等
├──settings 项目设置 例如构建发布设置，                                                 ***
├──temp  缓存文件    
└──project.json  一个编辑器的关联通知文件                                              ***
└──creator.d.ts   vs code 智能提示文件
└──jsconfig.json  编辑器 ->开发者->vs工作流里面的配置
└──template.json   编辑器 ->开发者->vs工作流里面的配置
```



上面 标注***都是项目的必须文件，在合作开发时，非必需文件不需要上传

