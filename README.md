




# 项目名称

mdjnulogo-Mudanjiang Normal University Logo

牡丹江师范学院校徽
# 素材来源

# 效果展示
### 不透明
![name](/Image/namer.png)
### 透明
![name_trans](/Image/name_transparent.png)
![](004182.png)
### 不透明
![Logo](/Image/Logo_043793.png)

### 透明
![Logo043793_transparent](/Image/Logo_043793_transparent.png)

素材下载自[牡丹江师范学院](http://www.mdjnu.cn/xqzl1/xxbs.htm)和[牡丹江师范学院教务处](http://jwc.mdjnu.cn/info/2039/4862.htm)

根据原素材取色校正，使用脚本对每一个像素的元素进行了检查，确保颜色的纯正。

# 转换代码

[ImageMagick](https://imagemagick.org/script/download.php)

```shell
#校正颜色
magick [input_pic_name] -fuzz 30% -fill "#xxxxxx" +opaque white -fill white +opaque "#xxxxxx" -define png:exclude-chunks=date,time [output_pic_name]
#xxxxxx 为十六进制颜色，input&output 注意导出名字

#透明背景
magick [input_pic_name] -transparent white -define png:exclude-chunks=date,time [output_pic_name]
    
```

### <mark>欢迎pr，指正 
# 作者

- [@syx-413](https://github.com/syx-413)

### Thanks - [@note286](https://github.com/note286)


